source 'https://rubygems.org'

ruby '2.2.2'

gem 'rails', '4.2.1'
gem 'pg'
group :production do
  gem 'rails_12factor'
end

gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'jquery-rails'

gem 'jbuilder', '~> 2.0'

gem 'exception_notification'
gem 'postmark-rails'
gem 'newrelic_rpm'

gem 'devise'
gem 'omniauth'

gem 'puma'

group :development do
  gem 'rvm-capistrano'

  gem 'better_errors'
  gem 'binding_of_caller', platforms: [ :mri ]
  gem 'brakeman'
  gem 'sandi_meter'
  gem 'railroady'
end

group :development, :test do
  gem 'pry-rails'
  gem 'awesome_print'

  gem 'faker'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'factory_girl_rails'
  gem 'fabrication'
  gem 'capybara'

  gem 'byebug'
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

group :test do
  gem 'simplecov'
end

group :development, :heroku do
  gem 'yaml_db'                           # for syncing heroku db
end

gem 'sdoc', '~> 0.4.0', group: :doc
