# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

#begin
#  require File.expand_path('../config/applicatidion', __FILE__)
#  rescue Bundler::PathError, Bundler::GitError => e
#    # Fall back on doing an unlocked resolve at runtime.
#    if (!system("bundle install"))
#        puts $?
#  end
#end
require File.expand_path('../config/application', __FILE__)

require 'rake'

OpenGov::Application.load_tasks