require 'bundler/setup'
Bundler.require(:default, :development)
group :default do
source "https://rubygems.org"
  gem "rspec"
  gem "sinatra"
  gem "octokit" -> 2.0
  gem "awesome_print"
end

group :development do
  gem "pry"
end

require_relative '../config/environment'
