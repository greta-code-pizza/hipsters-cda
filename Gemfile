source "https://rubygems.org"

gem "rails", "~> 6.0.4.8"

gem "mysql2"

# uncomment to use PostgreSQL
# gem "pg"

# rails
gem 'scenic', '>= 1.5.4'
gem 'scenic-mysql_adapter', '>= 1.0.1'
gem "activerecord-typedstore"
gem 'sprockets-rails', '2.3.3'

gem 'dotenv-rails', '>= 2.7.6', groups: [:development, :staging, :test]

# js
gem "jquery-rails", "~> 4.4", ">= 4.4.0"
gem "json"
gem "uglifier", ">= 1.3.0"

# deployment
gem "actionpack-page_caching", ">= 1.2.3"
gem "exception_notification", ">= 4.4.3"
gem "puma", ">= 5.3.1"

# security
gem "bcrypt", "~> 3.1.2"
gem "rotp"
gem "rqrcode"

# parsing
gem "pdf-reader"
gem "nokogiri", ">= 1.11.0.rc4"
gem "htmlentities"
gem "commonmarker", "~> 0.14"

gem "oauth" # for twitter-posting bot
gem "mail" # for parsing incoming mail
gem "ruumba" # tests views
gem "sitemap_generator" # for better search engine indexing
gem "svg-graph", require: 'SVG/Graph/TimeSeries' # for charting, note workaround in lib/time_series.rb
gem 'transaction_retry' # mitigate https://github.com/lobsters/lobsters-ansible/issues/39
# Font icons
gem "font-awesome-rails"
# API
gem 'rack-cors'
gem 'http-accept'

group :test, :development, :staging do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'good_migrations', '>= 0.0.2'
  gem "listen"
  gem "rspec-rails", ">= 5.0.1"
  gem "factory_bot_rails", ">= 6.1.0"
  gem "rubocop", "0.81", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "faker"
  gem "byebug"
  gem "rb-readline"
  gem "vcr"
  gem "webmock" # used to support vcr
  gem 'simplecov', require: false
  gem 'pry-rails'

  # perf
  gem 'flamegraph'
  gem 'memory_profiler'
  gem 'rack-mini-profiler'
  gem 'stackprof'
end

gem "bugsnag", "~> 6.20"
