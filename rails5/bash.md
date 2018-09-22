# REST and tests with rails

## Prepare environment
	cd path/to/project
	rbenv
	rbenv local
	rbenv versions
	rbenv local 2.4.1
	bundle init

## Install rails
	cat 'gem "rails"' >> Gemfile
	bundle install

## Create app with rails
	bundle exec rails new todos-app --api -T
