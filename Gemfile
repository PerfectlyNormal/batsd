source "https://rubygems.org"

gem 'eventmachine', '~> 1.2.0'
gem 'redis', "~> 3.0.2"
if RUBY_PLATFORM == 'java'
  gem 'json-jruby'
else
  gem 'json'
end

group :development, :test do
  gem 'yard'
  gem 'mocha'
  gem 'rake'
end
