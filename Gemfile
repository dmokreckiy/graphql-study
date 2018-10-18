source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 5.2.1'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'webpacker'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

gem 'graphql'
gem 'oj'
gem 'multi_json'
gem 'mini_racer'
gem 'jwt'

group :development, :test do
  gem 'byebug'
  gem 'faker', require: false
  gem 'factory_bot_rails'
  gem 'rspec-rails'
  gem 'rubocop', '~> 0.58.2', require: false # linter and style checker
  gem 'pry' # replacement for irb
  gem 'awesome_print' # for more visual data in console
  gem 'spring-commands-rspec'
  gem 'rubocop-rspec' # separate rubocop rules for tests
  gem 'shoulda-matchers', '4.0.0.rc1'
  gem 'rails-controller-testing' # If you are using Rails 5.x
  gem 'pry-rails' # useful rails info inside pry console
  gem 'pry-byebug' # debugging in pry
end

group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  # gem 'thin', require: false
  # gem 'activerecord-colored_log_subscriber' # backport from Rails 5
  # gem 'benchmark-ips'
  gem 'better_errors'
  gem 'binding_of_caller'
  # gem 'bullet', require: false
  # gem 'ruby-prof'
  # gem 'diffy'
  gem 'pry-doc'
  # gem 'rack-mini-profiler', require: false
  # gem 'memory_profiler' # For memory profiling in rack-mini-profiler
  # flamegraph stack
  # gem 'flamegraph', require: false # For flame graphs in rack-mini-profiler
  # gem 'stackprof', require: false # For flame graphs in rack-mini-profiler
  # flamegraph stack end
  # gem 'pry-rescue'
  gem 'pry-stack_explorer'
  gem 'rcodetools', require: false
  # gem 'bumbler', require: false
  # gem 'perftools.rb', git: 'git://github.com/tmm1/perftools.rb.git'
  # gem 'ruby-prof'
  # gem 'annotate', git: 'https://github.com/ctran/annotate_models.git', require: false
  # gem 'scout_apm'
  gem 'dotenv-rails'
  gem 'bundler-audit', require: false
end
