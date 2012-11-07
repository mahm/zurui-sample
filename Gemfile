source 'https://rubygems.org'

gem 'rails', '3.2.8'
gem 'pg', group: :production
gem 'thin'

gem 'sqlite3'

#--------------------------------------------------------------------------------
# Assets
#--------------------------------------------------------------------------------
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'bootstrap-sass', :git => "git@github.com:machida/bootstrap-sass.git", branch: 'master'
  gem 'compass-rails'
  gem 'sassy-buttons'
  gem 'font-awesome-sass-rails'
  gem "compass-rgbapng", :require => "rgbapng"
  gem "zurui-sass-rails", path: "/Users/mah_lab/dev/workspace/zurui-sass-rails"

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

#--------------------------------------------------------------------------------
# View
#--------------------------------------------------------------------------------
gem 'haml'
gem 'haml-rails'
gem 'jquery-rails'

#--------------------------------------------------------------------------------
# View Helpers
#--------------------------------------------------------------------------------
gem 'simple_form'
# gem 'kaminari', git: 'git://github.com/amatsuda/kaminari.git'

#--------------------------------------------------------------------------------
# Active Record
#--------------------------------------------------------------------------------
gem 'devise'
gem "default_value_for"
# gem "active_attr"
# gem "hashie"
# gem "meta_search"

#--------------------------------------------------------------------------------
# Operation
#--------------------------------------------------------------------------------
gem "heroku_backup_task", git: "git://github.com/mataki/heroku_backup_task.git"
gem "heroku"
gem 'newrelic_rpm'
# gem "airbrake"

#--------------------------------------------------------------------------------
# Development & Test Tools
#--------------------------------------------------------------------------------
group :development do
  gem 'heroku_san'
  gem 'erb2haml'
  gem "quiet_assets"
  gem "letter_opener"
  # gem 'i18n_generators'
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'fuubar'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'pry'

  # if necessary js unit tests
  # gem 'jasmine-rails'
  # gem 'jasmine-headless-webkit'
end
