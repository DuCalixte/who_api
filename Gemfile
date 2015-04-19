source "http://rubygems.org"

gem 'rake', '~> 10.4'
gem 'thor', '~> 0.19'


# Web Service & Application DSL
gem 'sinatra', '~> 1.4'

gem 'multi_json', '~> 1.11'
gem 'sinatra-activerecord', '~> 2.0'
gem 'delayed_job', '~> 4.0'
gem 'delayed_job_active_record', '~> 4.0'
gem 'workless', '~> 1.2'
gem 'pagination', '~> 0.3'
gem 'dice_bag', '~> 0.8'


group :production do
	# Tiny fast web server
	gem 'thin', '~> 1.6'
end

group :development, :test do
	gem 'byebug', '~> 4.0'
	gem 'yard', '~> 0.8.7'
	gem 'simplecov', '~> 0.10'
	gem 'brakeman', '~> 3.0'
	gem 'rubocop', '~> 0.30'
	gem 'pry', '~> 0.10'
	gem 'activesupport', '~> 4.2'
	gem 'ZenTest', '~> 4.11'
	gem 'rspec', '~> 3.2'
	gem 'factory_girl', '~> 4.5'
	gem 'nokogiri', '~> 1.6.6'
	gem 'autotest-fsevent', '~> 0.2'
	gem 'autotest-growl', '~> 0.2'
end

group :test do
	gem 'cucumber', '~> 2.0'
	gem 'pickle', '~> 0.5'
end

