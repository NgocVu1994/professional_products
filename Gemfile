source "https://rubygems.org"

gem "rails", "~> 4.2", ">= 4.2.7.1"

# Authentication
gem "devise", git: "https://github.com/nguyenngoc2505/devise"
gem "omniauth-facebook"
gem "koala", "~> 2.2"

# Authorization
gem "cancancan"

# Layout
gem "bootstrap-sass"
gem "bourbon"
gem "material_icons"
gem "font-awesome-rails"

# Common
gem "sass-rails", "~> 5.0.4"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.1.0"
gem "jquery-rails"
gem "kaminari"
gem "draper"

# ORM
gem "mysql2", "0.3.21"
gem "makara"

# Redis
gem "redis-rails"

# Search
gem "searchkick"
gem "ransack"

# Mail sending
gem "mandrill-api"
gem "gibbon"

# Support
gem "dotenv-rails"
gem "config"
gem "carrierwave", git: "https://github.com/hnam2812/carrierwave"
gem "carrierwave-aws"
gem "cloudfront-signer"
gem "faraday_middleware-aws-signers-v4",
  git: "https://github.com/framgia/faraday_middleware-aws-signers-v4.git"
gem "rubyXL", "~> 3.3", ">= 3.3.21"
gem "geocoder"
gem "gaffe"

# Read Spreadsheets
gem "roo", "~> 2.4.0"

# Deployment
gem "unicorn"
gem "unicorn-worker-killer"
gem "capistrano", "3.6.0"
gem "capistrano-rails"
gem "capistrano-rvm"
gem "capistrano-sidekiq"
gem "capistrano-resque", require: false
gem "capistrano-bundler"
gem "capistrano3-unicorn"
gem "aws-sdk", "~> 2.3.9"
gem "simple_form"
gem "ckeditor"
gem "mini_magick"
gem "sidekiq"

# Suppport insert bulk data
gem "activerecord-import"

# Data Migration Tool
group :test, :staging, :staging_framgia, :production do
  gem "tiny_tds", "1.0.4"
end

# Soft delete
gem "paranoia", "~> 2.0"
gem "deep_cloneable", "~> 2.2.1"

# I18n
gem "i18n-js", "~> 2.1", ">= 2.1.2"

group :development, :test, :staging, :staging_framgia do
  gem "pry-rails"
  gem "pry-byebug"
  gem "better_errors"
  gem "rack-mini-profiler", require: false
  gem "shoulda-matchers"
  gem "faker"
end

group :test do
  gem "rspec-rails", "~> 3.3.3"
  gem "rspec-collection_matchers"
  gem "factory_girl_rails"
  gem "simplecov"
  gem "simplecov-rcov"
end

group :development do
  gem "rubocop", "~> 0.40.0", require: false
  gem "foreman"
  gem "rubocop-checkstyle_formatter"
  gem "brakeman"
  gem "reek"
  gem "bundler-audit", "~> 0.4.0"
  gem "rails_best_practices"
  gem "bullet"
end

gem "rails_admin"
gem "barcodes"
gem "resque"
gem "resque-scheduler"
gem "resque-web", require: "resque_web"
