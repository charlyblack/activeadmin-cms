source "http://rubygems.org"

# Declare your gem's dependencies in activeadmin-cms.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end


gem "activeadmin"
gem "haml"

# jquery-rails is used by the dummy application
gem "jquery-rails"

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
gem 'ruby-debug19', :require => 'ruby-debug'

gem 'carrierwave'
gem 'fog'
gem 'mini_magick' 

gem 'acts_as_markup', :git => 'git@github.com:adamphillips/acts_as_markup.git'

gem 'delayed_job_active_record'
gem 'carrierwave_backgrounder'
gem 'daemons'

group :development do
  gem 'factory_girl_rails'
  gem 'generator_spec', :path => '/Users/aphillips/Projects/Development/OpenSource/gems/generator_spec'
end
