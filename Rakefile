namespace :greeting
desc "Says hello with users name"
task :greet do
  puts "Hello, what is your name?"
  name = gets.chomp
  puts "Hello" + name + ", how are you?"
end
namespace :time
desc "Give us the time"
task :time do
  puts Time.new
end

desc "prints your favorite food"
task :print_favorite_food do
  puts "Your favorite food is [food]"
end

desc "tasks that is first"
task :first do
  puts "First!"
end
desc "tasks that is second"
task :second => :first do
  puts "Second!"
end

desc "waking up"
task :wakeup do
  puts "first you get up out of bed and take a shower"
end
namespace :morning_routine
desc "getting dressed"
task :get_dressed => :wakeup do
  puts "then you put on a pair of chubbies and you're ready for the day!"
end