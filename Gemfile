source 'https://rubygems.org'
ruby '~> 2.5.0'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

# Application
gem 'active_model_serializers', '~> 0.10.0'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'geocoder', '~> 1.4', '>= 1.4.9'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.7'
gem 'rails', '~> 5.2'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'faker', '~> 1.8', '>= 1.8.7'
  gem 'rspec-rails', '~> 3.7'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.2'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
