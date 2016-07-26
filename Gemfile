source 'https://rubygems.org'

gem 'rails', '4.2.6'
# Use PostgreSQL as the database for Active Record
gem 'pg', '>=0.18.4'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'bootstrap-sass', '~>3.3'
gem 'font-awesome-rails', '~> 4.5'
gem 'simple_form', '~> 3.2', '>= 3.2.1'
gem 'devise', '~> 3.5.6'
gem "pundit", '~> 1.1.0'
gem "searcher", github: "radar/searcher"

gem 'carrierwave', '~> 0.11.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Using rspec for testing
  gem "rspec-rails", "~> 3.4.2"
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem "capybara", "~> 2.4"
  gem "factory_girl_rails", "~>4.7"
  gem "selenium-webdriver", "~> 2.53"
  gem "database_cleaner", "~> 1.5.3"
  gem "email_spec", "~> 2.1.0"
end
