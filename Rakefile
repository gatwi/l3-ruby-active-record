require_relative './config/environment'
require 'sinatra/activerecord/rake'

# CREATE TASK WITHOUT DESCRIPTION
task :hello_world do
    puts "Hello World" 
end


# CREATE TASK WITH DESCRIPTION
desc "Find .01% of 14k"
task :complex_math do
    output = (0.01/100) * 14000
    puts output
end

# ORGANIZE TASKS IN NAMESPACES
namespace :math_concepts do
    desc 'Find addition'
    task :add do
        puts "Addition"
    end
    desc 'Find multiplication'
    task :mult do
        puts "Multiplication"
    end
    desc 'Find division'
    task :div do
        puts "Division"
    end
end