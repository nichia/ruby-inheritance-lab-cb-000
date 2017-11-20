require_relative "./lib/student.rb"
require_relative "./lib/teacher.rb"
require_relative "./lib/user.rb"

require "pry"
require "rake"

puts "Welcome to Ruby Inheritance"

def reload!
  load "./lib/student.rb"
  load "./lib/teacher.rb"
  load "./lib/user.rb"
end

desc "A Console"
task :console do
  Pry.start
end
