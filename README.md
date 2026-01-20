# midnight-hotpot-club.github.io

## Development
1. Use the correct Ruby version (see `.ruby-version`).
   Example with rbenv:
   ```bash
   rbenv install $(cat .ruby-version)
   rbenv local $(cat .ruby-version)
   ```
2. Install dependencies.
   ```bash
   gem install bundler -v 2.4.22
   bundle _2.4.22_ install
   ```
3. Run the dev server.
   ```bash
   bundle exec jekyll serve --config _config.yml,_config-dev.yml
   ```
