source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'mysql2'
gem 'jquery-rails'
gem "devise", ">= 2.2.3"
gem "figaro", ">= 0.5.3"

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end
group :development do
  gem "quiet_assets", ">= 1.0.1", :group => :development
  gem "better_errors", ">= 0.3.2", :group => :development
  gem "binding_of_caller", ">= 0.6.8", :group => :development
end
group :test do
  gem "database_cleaner", ">= 0.9.1"
  gem "email_spec", ">= 1.4.0"
  gem "cucumber-rails", ">= 1.3.0", :require => false
  gem "launchy", ">= 2.1.2"
  gem "capybara", ">= 2.0.2"
end
group :development, :test do
  gem "rspec-rails", ">= 2.12.2"
  gem "factory_girl_rails", ">= 4.2.0"
  gem 'debugger'
end
group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'


# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
