source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use sqlite3 as the database for Active Record

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'listen'
  gem 'byebug', '9.0.6', platform: :mri
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', ' ~> 0.18'
  gem 'rails_12factor', '0.0.2'
end