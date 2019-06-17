source 'https://rubygems.org'
git_source(:github) {|repo| "https://github.com/#{repo}.git"}

ruby '2.5.3'

gem 'rails', '~> 5.2.2'
gem 'puma', '~> 3.11'

gem 'jquery-rails'
gem 'coffee-script', '~> 2.4', '>= 2.4.1'
gem 'twitter-bootstrap-rails'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'lightbox-bootstrap-rails', '5.1.0.1'

gem 'devise', '~> 4.6'
gem 'devise-i18n'
gem 'rails-i18n'
gem 'carrierwave', '~> 1.3', '>= 1.3.1'
gem 'rmagick'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'turbolinks', '~> 5.2'

group :development, :test do
  gem 'sqlite3', '< 1.4'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :production do
  gem 'pg'
  gem 'fog-aws'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
end
