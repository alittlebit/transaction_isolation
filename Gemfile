source "http://rubygems.org"

# Specify your gem's dependencies in kontolib.gemspec
gemspec

group :test do
  # Use the gem instead of a dated version bundled with Ruby
  gem 'minitest', '5.3.4'
  
  gem 'simplecov', :require => false

  gem 'mysql2', '~> 0.5'
  gem 'pg'
  gem 'sqlite3', '~> 1.4'
end

group :development do
  gem 'rake'
  # enhance irb
  gem 'awesome_print', :require => false
  gem 'pry', :require => false
end
