# Load DSL and set up stages
require 'capistrano/setup'
require 'capistrano/framework'

require 'capistrano/ssh_doctor'
require "airbrussh/capistrano"

require 'capistrano/shiplane'
require 'capistrano/shiplane_bootstrappers_chef'
require 'capistrano/shiplane_deployers_capistrano_docker'

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/**/*.rake').each { |r| import r }
