source 'https://rubygems.org'

gem 'sinatra'
gem 'rake'
gem 'rack', '1.5.2'
gem 'activerecord', :require => 'active_record'
gem 'sinatra-activerecord', :require => 'sinatra/activerecord'
gem 'sinatra-reloader'
gem 'require_all'
gem 'thin'
gem 'bcrypt'
gem 'tux'

group :development, :test do
  gem 'sqlite3'
	gem 'shotgun'
end

group :production do
	gem 'turbo-sprockets-rails3'
  gem 'mysql2', '0.3.16'
end
