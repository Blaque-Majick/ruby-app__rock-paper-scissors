require 'rake/testtask'

task :default => :tet
Rake::TestTask.new(:test) do |t|
  t.libs = %w(lib tests)
  t.pattern = 'tests/**/*_test.rb'
end

task :default => :test