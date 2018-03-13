﻿source 'https://rubygems.org'

ruby "2.4.2"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '5.1.3'


# Use Puma as the app server
group :development, :test do
  gem 'puma', '~> 3.7'
end

#
gem 'mysql2'

#
gem 'devise', '4.3.0' #, '3.5.6'


if Bundler::WINDOWS
  #gem 'bcrypt-ruby', '~> 3.0.0', require: false
  gem 'bcrypt-ruby', '3.1.1.rc1', :require => 'bcrypt'
else
  gem 'bcrypt', '~> 3.1.10', require: false
end

gem 'net-ssh', '3.2.0' # for backup gem
#gem 'net-ssh', '4.0.1' #ok - 2017-aug
#gem 'net-ssh', '3.1.1', github: 'maxivak/net-ssh', :branch => '3-1-release'

#
gem 'omniauth'
gem 'omniauth-facebook'
gem 'omniauth-twitter'
gem 'omniauth-linkedin'
#gem 'certified'

#
#gem 'activeadmin', '1.0.0.pre2' # bad
#gem 'activeadmin', github: 'activeadmin'
#gem 'inherited_resources', github: 'activeadmin/inherited_resources'
#gem "active_admin-sortable_tree"


gem 'optimacms', '0.3.23'
#gem 'optimacms', github: 'maxivak/optimacms'
#gem 'optimacms', path: '/data/projects/myrails/cms/site'

#gem 'rails_themes_bootstrap', '0.0.2',:git => 'git://github.com/maxivak/rails_themes_bootstrap.git'

gem 'backup', '5.0.0.beta.2'
#gem 'backup', '4.4.0'
gem 'backup-remote', '0.0.18'
#gem 'backup-remote', '0.0.17', path: '/data/projects/backup-remote'
gem 'optimacms_backups', '0.0.12'



gem 'globalize', github: 'globalize/globalize'
gem 'activemodel-serializers-xml'
gem 'globalize-accessors'


#
gem 'haml-rails', '1.0.0'
gem 'sass-rails', '~> 5.0.6'
gem 'uglifier', '3.2.0'
gem 'jquery-rails', '4.3.1' # '4.2.2','4.0.3'
gem 'font-awesome-rails', '~>4.7'

# bootstrap v4
#gem 'bootstrap', '~> 4.0.0.beta'


#
gem 'rails-i18n', '~> 5.0'

#
gem 'rack-cache'
gem 'redis-rails'



# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
#gem 'turbolinks', '~> 5'


gem 'jbuilder'



# See https://github.com/sstephenson/execjs#readme for more supported runtimes
#gem 'therubyracer', platforms: :ruby
#gem 'execjs'
#gem 'json' #, '1.8.5'



gem 'kaminari'

gem 'simple_form', '3.5.0'
gem 'simple_search_filter', '0.1.1'
#gem 'simple_search_filter', '~>0.0.31', github: 'maxivak/simple_search_filter', branch: 'bootstrap4'
gem 'bootstrap_autocomplete_input', '0.2.0'


gem 'paperclip', '~> 5.2.0'
gem 'ancestry'


# tinymce
gem 'tinymce-rails'#, '4.1.6'

# editor
gem 'el_finder', '1.1.12'

#
gem 'redis'
gem "simple_events_redis", '1.0.1'
gem 'sidekiq'


gem 'slack-notifier'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data'



group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end


# deployment
group :development do
  gem 'capistrano',  '3.10.0'
  gem 'capistrano-rails', '1.1.7'
  gem 'capistrano-bundler', '1.1.4'
  gem 'capistrano-rvm',   '0.1.2'

  gem 'slackistrano'
  gem 'capistrano-yarn'

  #gem 'capistrano-passenger'
  #gem 'capistrano-touch-linked-files'
  #gem 'capistrano-upload-config'

end


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri

  # Access an IRB console on exception pages or by using <%= console %> in views
  #gem 'web-console', '~> 2.0'

  gem 'rspec-rails'#, '3.1.0'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'faker'
  gem 'capybara'
  #gem "capybara-webkit"
  #gem 'selenium-webdriver'

end


