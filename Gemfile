source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'spork', '0.9.0.rc9'

group :development do
  gem 'rspec-rails'
end

group :production do
  # gems specifically for Heroku go here
  if (Gem.available?('pg'))
    gem "pg"
  end
end

group :test do
  gem 'rspec'
end

gem 'sqlite3'
gem 'webrat'

gem 'jquery-rails'
