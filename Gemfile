source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '>= 5.0.0.rc1', '< 5.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5.x'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
 
# Front endy stuff. 
# 
# Use Bootstrap 4 and all that. 
gem 'bootstrap', '~> 4.0.0.alpha3'
gem 'rails-assets-tether', '>= 1.1.0'
gem 'font-awesome-sass', '~> 4.6.2'

gem 'gon' # Connect ruby straight to JS vars. 
gem "d3-rails" # Cuz D3. 
gem "chartkick" # Or simpler, Highcharts easyfied. 
gem "groupdate" # Group by times and dates with ease. 
gem "hightop" # Best sellers. 

# Middle scenes stuff. 
# 
gem 'devise' # An authentication standard. https://github.com/plataformatec/devise
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave' # File uploads. https://github.com/carrierwaveuploader/carrierwave
gem "fog-aws" # For CarrierWave S3 file storage. Needs to be configured in initializers/carrierwave.rb. Look it up. 
gem 'jquery-fileupload-rails' # Pretty file uploads. 
gem 'mini_magick' # If you want to do resizing uploads. (Don't forget `$ brew install imagemagick`).
gem 'nokogiri' # For parsing shit. 
gem 'redcarpet' # Markdown rendering. 
gem 'descriptive_statistics', :require => 'descriptive_statistics/safe' # Do math. 
gem 'impressionist' # Popularity contestifier.
# gem 'counter_culture', '~> 0.1.33' # Count children of x. Should fix double counting on belong_to counter_cache. As of 4.2 Rails this issue is still unresolved in the master branch, with no obvious workaround. 
gem 'friendly_id', '~> 5.1.0' # Generate sexy slugs.

# Behind the scenes stuff. 
# 
gem 'rack-cors', :require => 'rack/cors' # For opening API so you can do headers and tokens and stuff. 
gem 'table_print' # Convienent for looking at tables in rails console. 
gem 'ahoy_matey' # Traffic tracking. 
gem 'figaro' # Secret things in application.yml. 
gem 'timeliness' # Fast date/time parsing for the control freak. http://github.com/adzap/timeliness
gem 'rails_12factor', group: :production # I don't know exactly what it does but Heroku likes it for logs. 
gem 'query_diet', group: :development # Mind dose queries. 
gem 'colorize' # Make ruby output colored. Fancy. 


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

  # Live Reload per https://mattbrictson.com/lightning-fast-sass-reloading-in-rails
  # Then `$ guard -P livereload` in separate terminal adjacent to server. 
  gem "guard", ">= 2.2.2", :require => false
  gem "guard-livereload",  :require => false
  gem "rack-livereload"
  gem "rb-fsevent",        :require => false

  gem 'seed_dump' # Dump db data into seeds.rb. 
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

ruby '2.3.1'