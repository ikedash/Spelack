ruby '2.2.3'

source 'https://rubygems.org' do
  gem 'actioncable', github: 'rails/actioncable', branch: 'archive'
  gem 'amazon-ec2'
  gem 'carrierwave'
  gem 'coffee-rails'
  gem 'devise'
  gem 'google-api-client'
  gem 'jbuilder'
  gem 'jquery-rails'
  gem 'link_thumbnailer'
  gem 'mysql2', '~> 0.3.20'
  gem 'paperclip'
  gem 'puma'
  gem 'rails', '4.2.4'
  gem 'react-rails'
  gem 'sass-rails'
  gem 'sidekiq'
  gem 'slim-rails'
  gem 'uglifier'

  group :doc do
    gem 'yard'
  end
  group :development do
    gem 'web-console', '~> 2.0'
  end

  group :development, :test do
    gem 'better_errors'
    gem 'bullet'
    gem 'factory_girl_rails'
    gem 'ffaker'
    gem 'pry-byebug'
    gem 'pry-rails'
    gem 'rubocop', require: false
  end

  group :test do
    gem 'capybara'
    gem 'capybara-screenshot'
    gem 'database_rewinder'
    gem 'json_expressions'
    gem 'poltergeist'
    gem 'rspec-rails'
    gem 'rspec_junit_formatter'
    gem 'simplecov', require: false
    gem 'validation_examples_matcher'
  end

  group :production do
    gem 'unicorn', '~> 4.9.0'
  end
end
