﻿source 'https://rubygems.org'

ruby "2.2.4"

gem 'rails', '4.2.5.2'


gem 'mysql2', '0.3.20'

#gem 'net-ssh', '3.1.1'
gem 'net-ssh', '3.1.1', :git => 'https://github.com/maxivak/net-ssh', :branch => '3-1-release'

#gem 'net-ssh', '4.0.0.alpha3'

#
gem 'devise', '3.5.6'
gem 'devise-async'
gem 'bcrypt-ruby', '3.1.1.rc1', :require => 'bcrypt'

gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-linkedin'
#gem 'certified'

#
gem 'activeadmin', '1.0.0.pre2'
#gem "activeadmin-sortable-tree", :github => "nebirhos/activeadmin-sortable-tree", :branch => "master"
gem "activeadmin-sortable-tree", :github => "maxivak/activeadmin-sortable-tree", :branch => "master"


gem 'optimacms', '0.2.2'
#gem 'optimacms', '0.2.1', path: '../optimacms'
#gem 'optimacms', '0.2.1', :git => 'https://github.com/maxivak/optimacms.git', :branch => 'bootstrap_v4_alpha'

#gem 'rails_themes_bootstrap', '0.0.2',:git => 'git://github.com/maxivak/rails_themes_bootstrap.git'



#
gem 'haml-rails', '~>0.9.0'

gem 'uglifier'

gem 'coffee-script-source', '1.8.0'

gem 'coffee-rails'
gem 'jquery-rails','4.0.3'
gem 'font-awesome-rails', '4.3.0.0'

gem 'sass-rails', '5.0.4'
gem 'compass-rails', '2.0.5'
gem 'sprockets-rails', '2.3.3'

gem 'bootstrap-sass', '3.3.4.1'



# bootstrap v4 alpha
#gem 'jekyll', '~> 3.0.1'
#gem 'jekyll-redirect-from', '~> 0.9.0'
#gem 'jekyll-sitemap', '~> 0.9.0'
#gem 'sass', '>= 3.4.19'
#gem 'sass-rails', '4.0.3'
#gem 'scss_lint', '~> 0.43'


#gem 'bootstrap', '~> 4.0.0.alpha3'



#
gem 'rails-i18n', '4.0.8' # For 4.0.x

#
gem 'rack-cache'
gem 'redis-rails'



# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'


# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'


# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby


gem 'paperclip', '~> 4.2'
gem 'kaminari'
gem 'kaminari-bootstrap', '~> 3.0.1'

gem 'simple_form'
gem 'simple_search_filter', '0.0.31'
gem 'bootstrap3_autocomplete_input', '0.1.7'


gem 'ancestry'


# tinymce
gem 'tinymce-rails', '4.1.6'

# editor
gem 'el_finder', '1.1.12'


#
#gem 'callback_request_bootstrap'

#
gem 'redis'
gem "simple_events_redis", '1.0.1'
gem 'sidekiq'


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]



group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  #gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  #gem 'web-console', '~> 2.0'

  gem 'rspec-rails', '3.1.0'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'faker'
  #gem "capybara-webkit"
  #gem 'selenium-webdriver'
end


# deployment
group :development do
  gem 'capistrano',  '3.4.0'
  gem 'capistrano-rails', '1.1.3'
  gem 'capistrano-bundler', '~> 1.1'
  gem 'capistrano-rvm',   '~> 0.1'

  #gem 'capistrano-passenger'
  #gem 'capistrano-touch-linked-files'
  #gem 'capistrano-upload-config'

end
