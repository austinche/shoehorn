require 'bundler'  
require 'rake'
require 'rake/testtask'

Bundler::GemHelper.install_tasks

Rake::TestTask.new(:test) do |test|
  test.libs << 'lib' << 'test'
  test.pattern = 'test/**/*_test.rb'
end