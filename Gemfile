source 'https://rubygems.org'

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
#gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'rails_bootstrap_navbar'
gem 'devise'
gem 'toastr-rails'
gem 'omniauth-facebook'
gem "paperclip", "~> 5.0.0"
gem 'dropzonejs-rails'
gem "figaro", "~> 1.1.0"
gem 'aws-sdk', '~> 2.3'

# Use sqlite3 as the database for Active Record
gem 'sqlite3', groups: %w(test development), require: false
gem 'pg', groups: %w(production), require: false

#group :production do 
#	gem 'pg'
#	gem 'rails_12factor'
#end
#
#group :development, :test do 
#	gem 'sqlite3'
#end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
