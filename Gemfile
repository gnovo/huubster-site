source 'https://rubygems.org'
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end
ruby '2.3.4'
gem 'rails', '~> 5.0.5'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
group :development, :test do
  gem 'byebug', platform: :mri
end
group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'administrate'
gem 'bootstrap', '~> 4.0.0.alpha6'
gem 'bourbon'
gem 'devise'
gem 'high_voltage'
gem 'pg'
gem 'pundit'
gem 'therubyracer', :platform=>:ruby
gem 'unicorn'
gem 'unicorn-rails'
group :development do
  gem 'better_errors'
  gem 'hub', :require=>nil
  gem 'rails_layout'
end

group :production do
  gem 'rails_12factor'
end