#!/usr/bin/env rake
require "rubygems"
require "bundler/setup"

require "bundler/gem_tasks"
require "rake/testtask"

Rake::TestTask.new do |t|
  t.libs << "test"
  t.text_files = FileList['test/**/*_test.rb']
  t.verbose = true
end

task :default => :test
