source "https://rubygems.org"

ruby '3.1.4'

gem 'rails', '~> 7.1.3'
gem "pg", "~> 1.6"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'mini_racer', platforms: :ruby
gem "redis", ">= 4.0.1"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem "image_processing", "~> 1.13"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem 'brakeman'
  gem 'dotenv-rails', '~> 3.1'
  gem 'rubocop', '~> 1.23'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'selenium-webdriver', '~> 4.10.0'
  gem 'pry'
  gem 'pry-remote'
end

group :development do
  gem "foreman"
  gem "web-console"
  gem "letter_opener"
  gem 'solargraph'
  gem 'solargraph-rails'
  gem 'ruby-lsp'
  gem 'ruby-lsp-rails'
end

group :test do
  gem 'rails-controller-testing'
end

gem 'sidekiq'
gem "devise"
gem 'sentry-ruby'
gem 'sentry-rails'
gem 'sentry-sidekiq'

# Spree Gems (Pinned versions to avoid issues)
gem "spree", "5.1.0"
gem "spree_emails", "5.1.0"
gem "spree_sample", "5.1.0"
gem "spree_admin", "5.1.0"
gem "spree_storefront", "5.1.0"
gem "spree_i18n"
