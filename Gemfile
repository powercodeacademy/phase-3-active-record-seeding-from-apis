source "https://rubygems.org"

ruby "3.3.5"
# An object-relational mapper
# https://guides.rubyonrails.org/active_record_basics.html
gem "activerecord"

# Configures common Rake tasks for working with Active Record
# https://github.com/sinatra-activerecord/sinatra-activerecord
gem "sinatra-activerecord"

# Run common tasks from the command line
# https://github.com/ruby/rake
gem "rake"

# Provides functionality to interact with a SQLite3 database
# https://github.com/sparklemotion/sqlite3-ruby
gem "sqlite3"

# Require all files in a folder
# https://github.com/jarmo/require_all
gem "require_all"

# Used to make network requests
# https://github.com/rest-client/rest-client
gem "rest-client"

gem "ostruct"

gem "rubocop"

# These gems will only be used when we are running the application locally
group :development do
  gem "pry"
end

# These gems will only be used when we are running tests
group :test do
  gem "database_cleaner"
  gem "rspec"
end
gem "fiddle"
gem "logger"

gem "rubocop-rake", "~> 0.7.1"

gem "rubocop-rspec", "~> 3.7"
