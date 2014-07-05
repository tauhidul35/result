source 'https://rubygems.org'
ruby '1.9.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '3.2.15'

# Use sqlite3 as the database for Active Record
gem 'mysql2', '0.3.14'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

# user define
gem 'nokogiri'

group :assets do
# Use SCSS for stylesheets
  gem 'sass-rails', '~> 3.2.3'
# Use Uglifier as compressor for JavaScript assets
  gem 'uglifier', '>= 1.0.3'
# Use jquery as the JavaScript library
  gem 'jquery-rails', '2.3.0'
end

group :development do
  gem 'thin', '1.6.1'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
  gem 'guard'
  gem 'guard-rubocop'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  gem 'unicorn', '~> 4.6.3'
end

group :staging do
  gem 'thin', '1.6.1'
end