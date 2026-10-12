
source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

# Bundle edge Rails instead:
gem "rails", "~> 7.0.8", ">= 7.0.8.1"

# The original asset pipeline for Rails
gem "sprockets-rails"

# Use the Puma web server
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps
gem "importmap-rails"

# Build JSON APIs with ease
gem "jbuilder"

# Windows does not include zoneinfo files
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching
gem "bootsnap", require: false

# SQLite for development and test
group :development, :test do
  gem "sqlite3", "~> 1.4"
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

# PostgreSQL for Heroku production
group :production do
  gem "pg"
end

group :development do
  gem "web-console"
end
