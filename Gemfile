source 'https://rubygems.org'

gem 'rails', '4.0.0'
gem 'bcrypt', '~> 3.1.2'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
group :production do
	gem 'pg'
end
gem 'thin'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
	gem 'rspec-rails', '~> 2.0'
	gem 'sqlite3'
end

group :test do
	gem 'capybara', '~>2.1.0'
	gem 'shoulda-matchers'
end
