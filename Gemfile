source 'https://rubygems.org'

gemspec

gem 'rake', '~> 10.4.2'
gem 'rake-compiler', '~> 0.9.5'

group :test do
  gem 'eventmachine' unless RUBY_PLATFORM =~ /mswin|mingw/
  gem 'rspec', '~> 3.2'
end

group :benchmarks do
  gem 'activerecord', '>= 3.0'
  gem 'benchmark-ips'
  gem 'do_mysql'
  gem 'faker'
  gem 'mysql'
  gem 'sequel'
end

group :development do
  gem 'pry'
  gem 'rake-compiler-dock', '~> 0.4.2'
end

platforms :rbx do
  gem 'rubysl-bigdecimal'
  gem 'rubysl-drb'
  gem 'rubysl-rake'
end
