source 'https://rubygems.org'
ruby "2.3.0"

gem 'rails', '4.2.4'

gem 'pg'


gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
	# bundle exec rake doc:rails generates the API under doc/api.
	gem 'sdoc', require: false
end

group :development do
	gem 'brakeman', :require => false
end

	# =========================================================
	# sample-milia-app specific stuff
	# =========================================================
	# Bundle the extra gems:

	gem 'haml-rails'
	gem 'html2haml', :git => 'git://github.com/haml/html2haml.git'  # "2.0.0.beta.2",

	# stuff that heroku likes to have
	gem 'thin'
	gem "SystemTimer", :require => "system_timer", :platforms => :ruby_18
	gem "rack-timeout"
	gem 'rails_12factor'


	gem 'web-app-theme', :git => 'git://github.com/dsaronin/web-app-theme.git'
	gem 'devise', '~>3.2'
	gem 'milia', :git => 'git://github.com/dsaronin/milia.git', :branch => 'v1.0.1'

	# airbrake is optional and configured by config.use_airbrake in milia initializer
	# default is false; if you change it to true, uncomment out the line below
	# gem 'airbrake'   # uncomment this if you will use airbrake for exception notifications

	# recaptcha is optional and configured by config.use_recaptcha in milia initializer
	# default is true; if you change it to false, comment out the line below

gem 'recaptcha', :require => "recaptcha/rails"
gem "activerecord-session_store", github: "rails/activerecord-session_store"
