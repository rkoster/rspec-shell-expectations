require 'bundler/gem_tasks'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new(:spec) do |t|
  t.verbose = false
end

require 'rubocop/rake_task'
RuboCop::RakeTask.new

task default: [:rubocop, :spec]