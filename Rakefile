# Rakefile
require 'sinatra/activerecord/rake'
require './app'

task :default => :test

desc "Run all tests"
task(:test) do
  Dir['./spec/*_spec.rb'].each { |f| load f }
end
