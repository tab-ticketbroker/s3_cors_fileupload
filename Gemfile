source 'https://rubygems.org'
ruby '2.0.0'

group :development do
  gem 'rdoc'
  gem 'gem-release'
end

group :test do
  # dependencies for S3CorsFileUpload
  gem 'rails', '~> 3.2.15'
  gem 'aws-sdk', '~> 1.0'
  gem 'sqlite3' # the database driver for rails
  gem 'jquery-rails' # for including jQuery into the dummy app

  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'generator_spec'
  gem 'ffaker'
  gem 'capybara'
  gem 'poltergeist' # to use as JS driver for Capybara
end
