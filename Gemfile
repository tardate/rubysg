ruby '2.0.0'
source 'https://rubygems.org'

# Heroku specific
# https://devcenter.heroku.com/articles/rails4-getting-started
gem 'rails_12factor', group: :production
gem 'puma'
gem 'foreman'

gem 'rails', '4.0.1'
gem 'pg'

gem 'haml-rails'
gem 'sass-rails'
gem 'jquery-rails'
gem 'coffee-rails'
gem 'uglifier'
gem 'turbolinks'

gem 'httparty'

gem 'bourbon'
gem 'neat'

group :production do
  gem 'runtimeerror_notifier'
end

group :development, :test do
  gem 'dotenv-rails'

  gem 'spring'
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'pry-rails'

  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'shoulda'

  gem 'capybara'
  gem 'poltergeist'

  gem 'better_errors'
  gem 'binding_of_caller'
end

group :test do
  gem 'vcr'
  gem 'webmock'
end
