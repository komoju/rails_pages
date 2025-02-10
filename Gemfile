source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Specify your gem's dependencies in rails_pages.gemspec.
gemspec

group :development do
  gem 'sqlite3', '~> 1'
end

group :test do
  gem 'concurrent-ruby', '1.3.4'
  gem 'rails', '~> 6'
  gem 'rspec-rails'
  gem 'rails-controller-testing'
  gem 'fakefs', require: 'fakefs/safe'
  gem 'sprockets-rails'
  gem 'psych', '< 6'
end

group :development, :test do
  gem 'pry-byebug'
  gem 'webpacker', '~> 5.4.4'
end

# To use a debugger
# gem 'byebug', group: [:development, :test]
