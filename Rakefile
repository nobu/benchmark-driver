require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |t|
  t.ruby_opts = %w[-w]
  t.rspec_opts = %w[--profile]
end

task default: :spec

# task :test_ruby do
#   Dir.glob(File.expand_path('./examples/*.rb', __dir__)).sort.each do |file|
#     Bundler.with_clean_env do
#       sh ['time', 'bundle', 'exec', 'ruby', file].shelljoin
#     end
#     puts
#   end
# end
