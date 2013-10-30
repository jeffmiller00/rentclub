source 'https://rubygems.org'

ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Servers
gem 'puma'
gem 'unicorn'

gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'

# Multi-environment configuration
# gem 'simpleconfig'

# API
# gem 'rabl'

gem 'pg', :require => 'pg'

# Performance and Exception management
# gem 'airbrake'
# gem 'newrelic_rpm'

# Security
# gem 'secure_headers'

# Miscellanea
# gem 'google-analytics-rails'
# gem 'haml'
# gem 'http_accept_language'
gem 'jquery-rails'
gem 'nokogiri'
# gem 'resque', require: 'resque/server' # Resque web interface

# Assets
gem 'coffee-rails', '~> 4.0.0'
# gem 'haml_assets'

# gem 'handlebars_assets'
gem 'i18n-js'
gem 'jquery-turbolinks'
gem 'less-rails'
gem 'sass-rails', '~> 4.0.0'
gem 'therubyracer'
gem 'turbolinks'
gem 'twitter-bootstrap-rails', github: 'diowa/twitter-bootstrap-rails', branch: 'fontawesome-3.2.1'
#gem 'twitter-bootstrap-rails'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'debugger'
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'pry'
  gem 'pry-rails'
  
  #gem 'spork-rails'
  gem 'awesome_print'
end

group :development do
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'

  gem 'chronic'
  gem 'admin_view'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false

  gem 'cucumber-rails', :require => false
  gem 'shoulda'
end

group :staging, :production do
  gem 'rails_12factor'
end

group :production, :development do
  gem 'thin'
end

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
#gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  #gem 'sdoc', require: false
end

# Use Capistrano for deployment
# gem 'capistrano', group: :development


# Base-app Gems -------
gem 'devise'
gem 'kaminari'
gem 'carrierwave'
#Doesn't play nicely
#gem 'meta_search'
gem 'dynamic_form'
gem 'heroku'
#gem 'less-rails-bootstrap'
