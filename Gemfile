source 'https://rubygems.org'

gem 'rails', '3.2.3'

group :assets do
  gem 'sass-rails', '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem "bootstrap-sass", '~> 2.0.2'

end

group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
end

gem "therubyracer"
group :development, :test do
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem "shoulda-matchers"

  # cucumber gems
  gem "cucumber"
  gem "capybara"
  gem "database_cleaner"
  gem "spork"
  gem "launchy" # So you can do Then show me the page
  gem "minitest" # currently breaks without this
  gem "minitest-reporters"
end

group :development do
  gem "rails3-generators"
  gem 'thin'
  gem 'cheat'
  gem 'guard'
  gem 'ruby_gntp'

end

group :test do
  gem "cucumber-rails", require: false
  gem "simplecov", ">=0.3.8", :require => false
  gem "email_spec"
end

gem 'jquery-rails'


gem 'pg'
gem 'debugger'

gem "haml"
gem "haml-rails"
gem "tabs_on_rails"

gem "devise"
gem "cancan"

gem "capistrano-ext"
gem "capistrano"
gem "capistrano_colors"
gem "colorize"

gem "metrical"

#gem "paperclip", "~> 2.0"
#gem 'delayed_job_active_record'
#gem 'daemons'
#gem 'prawn'
#gem 'decent_exposure'
#gem 'will_paginate', '> 3.0'
#gem 'will_paginate-bootstrap'