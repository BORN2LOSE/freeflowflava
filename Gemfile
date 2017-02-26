source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails',              '~> 5.0.1'
gem 'puma',               '~> 3.4.0'
gem 'bootstrap-sass'
gem 'bcrypt'
gem 'sass-rails',         '~> 5.0'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'uglifier',           '3.0.0'
gem 'coffee-rails',       '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks',         '~> 5'
gem 'jbuilder',           '~> 2.5'

group :development, :test do
  gem 'sqlite3', '1.3.12'
  gem 'byebug',  '9.0.0', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen',      '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'rails-controller-testing', '0.1.1'
  gem 'minitest-reporters',       '1.1.9'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
end

group :production do
  gem 'pg'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
