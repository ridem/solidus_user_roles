source 'https://rubygems.org'

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus', github: 'solidusio/solidus', branch: branch

gem 'mysql2'
gem 'pg'

group :development, :test do
  gem 'pry'
end

gemspec
