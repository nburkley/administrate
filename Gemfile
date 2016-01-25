source 'https://rubygems.org'

ruby "2.2.3"

gemspec

gem 'rails', '>= 5.0.0.beta1', '< 5.1'
gem "delayed_job_active_record"
gem "high_voltage"
gem "markdown-rails"
gem "pg"
gem "redcarpet"
gem "unicorn"

group :development do
  gem "web-console", ">= 2.1.3"
end

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "faker"
  gem "i18n-tasks"
  gem "pry-rails"

  gem "rspec-core", github: "rspec/rspec-core"
  gem "rspec-rails", github: "rspec/rspec-rails"
  gem "rspec-mocks", github: "rspec/rspec-mocks"
  gem "rspec-support", github: "rspec/rspec-support"
  gem "rspec-expectations", github: "rspec/rspec-expectations"
end

group :test do
  gem "ammeter"
  gem "database_cleaner"
  gem "formulaic"
  # gem "fuubar"
  gem "launchy"
  gem "rails-controller-testing"
  gem "capybara", github: "jnicklas/capybara"
  gem "percy-capybara"
  gem "poltergeist"
  gem "shoulda-matchers", "~> 2.8.0", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end
