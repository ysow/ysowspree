source 'https://rubygems.org'

ruby '2.7.4'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6.0.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

gem 'mini_racer'

gem 'bootsnap', require: false

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Puma as the app server
gem 'puma'

gem 'awesome_print'

group :development, :test do
  gem 'dotenv-rails', '~> 2.7', '>= 2.7.6'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'listen'

  gem 'rspec_junit_formatter'

  # monitoring
  gem 'bullet'
  gem 'rack-mini-profiler', require: false
  gem 'flamegraph'
  gem 'stackprof'
  gem 'memory_profiler'

  gem 'webmock'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 4.1', '>= 4.1.0'

  gem 'letter_opener'
end

group :test do
  gem 'vcr'
end

# Heroku fix
group :production do
  gem 'rack-timeout'
  gem 'font_assets'
end

# file uploades & assets
gem 'aws-sdk-s3', require: false

# caching
gem 'dalli' # memcache
gem 'rack-cache' # http caching

# sidekiq
gem 'sidekiq'

# Spree gems
spree_opts = '~> 4.3.0.rc1'
gem 'spree', spree_opts
gem 'spree_frontend', spree_opts
gem 'spree_backend', spree_opts
gem 'spree_sample', spree_opts
gem 'spree_emails', spree_opts
gem 'spree_gateway'
gem 'spree_auth_devise', '>= 4.3.4'
gem 'spree_i18n', '>= 5.0.1'
gem 'spree_dev_tools', '>= 0.1.8', require: false, group: %w[test development]

# Sentry Client
gem 'sentry-raven'

# Scout Client
gem 'scout_apm'

# feature toggle
gem 'flipper'
gem 'flipper-active_record'
gem 'flipper-redis'
gem 'flipper-ui'

# SendGrid
gem 'sendgrid-actionmailer'

# logging
gem 'remote_syslog_logger'

gem 'activerecord-nulldb-adapter'

# improved JSON rendering performance
gem 'oj'
