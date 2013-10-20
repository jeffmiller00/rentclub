source 'https://rubygems.org'

ruby '2.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

gem 'pg', :require => 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
group :assets do
  gem 'therubyracer', platforms: :ruby
end

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


# Base-app Gems -------
gem 'devise'
gem 'omniauth-facebook'
gem 'kaminari'
gem 'carrierwave'
gem 'meta_search'
gem 'dynamic_form'
gem 'heroku'
gem 'less-rails'
gem 'less-rails'
gem 'less-rails-bootstrap'
gem 'twitter-bootstrap-rails'

group :test, :development do
  gem 'rspec-rails'
  gem 'spork-rails'
  gem 'debugger'
  gem 'awesome_print'
end

group :development do
  gem 'chronic'
  gem 'admin_view'
  gem 'debugger'
end

group :test do
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'shoulda'
  gem 'email_spec'
end

group :production, :development do
  gem 'thin'
end
