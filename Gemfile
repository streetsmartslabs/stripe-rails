source 'https://rubygems.org'

# Specify your gem's dependencies in stripe-rails.gemspec
gemspec

gem 'rake'

group :development, :test do
  gem 'm'
end

group :test do
  gem 'mocha'
  gem 'simplecov', '< 0.18', require: false
  gem 'stripe-ruby-mock'
  gem 'webmock'
  # Required for system tests
  gem 'capybara'
  gem 'webdrivers'
  gem 'puma'
  gem 'selenium-webdriver'
end