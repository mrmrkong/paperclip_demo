source 'https://rubygems.org'

gem 'rails', '~> 4.0.0'

gem 'aws-sdk'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'paperclip'
gem 'pg'
gem 'sass-rails'
gem 'uglifier'

group :production, :staging do
  gem 'pg'
  gem 'rails_12factor'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'sqlite3'
  gem 'launchy'
end

group :test do
  gem 'capybara'
  gem 'shoulda-matchers'
end
