source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails", "~> 7.0.6"
gem "pg"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "bootsnap", require: false
gem 'dotenv'
gem "superconfig"

group :development, :test do
  gem "pry-meta"
end

group :development do
  gem "rubocop"
  gem "rubocop-rails"
  gem 'rubocop-performance'
  gem "rubocop-fnando"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"end
