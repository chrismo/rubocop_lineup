# frozen_string_literal: true

require "bundler/gem_tasks"
require "rspec/core/rake_task"

RSpec::Core::RakeTask.new(:spec)

task default: [:spec, "rubocop:auto_correct"]

require "rubocop/rake_task"

RuboCop::RakeTask.new
