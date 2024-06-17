### Running the Docker Image

You can pull the image from `khulnasoft/bfsc:latest`

Run it with `docker run --detach --publish 3000:3000 khulnasoft/bfsc:latest`

This repo has the same tags as the parent BFSC repo.

## Development

```
bundle install
# Make sure redis is running and available at localhost:6379
# This initializes the redis server
bundle exec ruby init.rb
bundle exec rackup
```

Your server should now be accessible at `http://localhost:9292`

## License

Code is licensed under the MIT License. See LICENSE file for details. Everything under the `data/` directory is available under the Public Domain.
