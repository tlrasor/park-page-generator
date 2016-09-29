require 'html-proofer'

desc "build website"
task :build do
  sh "bundle exec jekyll build"
end

desc "test website"
task :test => [:build] do
  HTMLProofer.check_directory("./_site", {:log_level => :debug, :disable_external => true }).run
end

task :default => :test