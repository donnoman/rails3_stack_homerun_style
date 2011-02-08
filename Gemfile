source 'http://rubygems.org'

gem 'rails', '3.0.3'
if File.exists?(recipes_path = "../cap-recipes")
  gem 'cap-recipes', :path => recipes_path, :require => false
else
  gem 'cap-recipes', :git => "git@github.com:donnoman/cap-recipes.git", :branch => "testing",  :require => false
end

#gem 'sqlite3-ruby', :require => 'sqlite3'
gem "unicorn"
gem "haml"
gem "haml-rails"
gem 'resque'
#gem "simple_form"
#gem "responders"
#gem "devise"
#gem "will_paginate", "~> 3.0.pre2"
#gem 'acts-as-taggable-on'
gem "rspec"
gem "rspec-rails"
#gem 'cancan'
#gem 'newrelic_rpm'
#gem 'ancestry'
#gem 'aws-s3'
#gem 'paperclip'

group :development do
  gem "ruby-debug"
  gem "capistrano"
#  gem "ruby-debug19"
#  gem "looksee"
#  gem "wirble"
#  gem "hirb"
#  gem "map_by_method"
#  gem "what_methods"
#  gem "awesome_print"
#  gem "railroady"
#  gem 'heroku'
#  gem 'taps'
#  gem 'heroku_san'
#  gem 'interactive_editor'
end


group :test, :development do
#  gem "factory_girl_rails"
#  gem "factory_girl"
#  gem "capybara"
#  gem "database_cleaner"
#  gem "spork"
#  gem "launchy"
#  gem 'ci_reporter'
#  gem "hpricot"
#  gem "ruby_parser"
#  gem 'fuubar'
#  gem 'ZenTest'
#  gem 'autotest-growl'
#  gem 'autotest-fsevent'
end

group :production do
# enable for memcached support:
# gem 'dalli'
end
