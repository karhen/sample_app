source 'https://rubygems.org'
ruby "1.9.3"
# added config stmts below at instruction of Guard install
#require 'rbconfig'
#  if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
#    gem 'wdm', '>= 0.1.0'
#  end

# gem 'strong_parameters' causing problems - leave it out for now
gem 'rails', '4.0.8'
gem 'bootstrap-sass', '2.3.2'
gem 'sprockets', '2.11.0'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do
	gem 'sqlite3', '1.3.8' 
	gem 'rspec-rails', '2.13.1'
# leftover- not sure if needed
	gem 'guard-rspec', '1.2.1'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "sass", "~> 3.2.5"
  gem 'sass-rails'
  gem 'coffee-rails', '4.0.1'
  gem 'uglifier', '2.1.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby
end

group :test do
# latest tutorial update
	gem 'selenium-webdriver', '2.35.1'
	gem 'capybara', '2.1.0'
# leftover - not sure if needed
	gem 'rb-fchange', '0.0.5'
	gem 'rb-notifu', '0.0.4'
	gem 'win32console', '1.3.2'
end

group :doc do
	gem 'sdoc', '0.3.20', require: false
end

group :production do
	gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
