source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{ repo_name }/#{ repo_name }" unless repo_name.include?('/')
  "https://github.com/#{ repo_name }.git"
end

gem 'rake'

group :development, :test do
  gem 'roo'
  gem 'atlas',    ref: '44ebbd6', github: 'quintel/atlas'
end

group :test do
  gem 'rspec'
  gem 'rubel',    ref: 'e36554a', github: 'quintel/rubel'
  gem 'refinery', ref: '72eacf8', github: 'quintel/refinery'
end
