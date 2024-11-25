source "https://rubygems.org"

gem "rails", "~> 8.0.0"
gem "devise"           # For user authentication
gem "image_processing" # For image resizing
gem "propshaft"
gem "sqlite3", ">= 2.1"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  # Choose either rubocop-rails-omakase OR rubocop/rubocop-rails, not both
  gem "rubocop-rails-omakase", require: false
  # gem 'rubocop'
  # gem 'rubocop-rails'
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end