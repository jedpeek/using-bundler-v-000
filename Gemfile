require 'bundler/setup'
Bundler.require(:default, :development)

group :default do
source "https://rubygems.org"
  gem "rspec"
  gem "hashie"
  gem "sinatra", '1.4.4'
  gem "octokit", '~> 2.0'
  gem "awesome_print", :git => 'https://github\.com:awesome\-print\/awesome_print\.git'
end

gem "pry", :group => "development"

require_relative '../config/environment'
require_relative '../bin/run.rb'
