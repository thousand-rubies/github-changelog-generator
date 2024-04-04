# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gemspec

group :development, :test do
  gem "bundler"
  gem "overcommit", ">= 0.31"
  gem "rake"
  gem "rubocop", ">= 0.50"
  gem "rubocop-performance"
  gem "yard-junk", ">= 0.0.8"
end

group :development do
  gem "bump"
end

group :test do
  gem "codeclimate-test-reporter", "~> 1.0"
  gem "json"
  gem "rspec", "< 4"
  gem "rspec_junit_formatter"
  gem "simplecov", "~>0.10", require: false
  gem "vcr", "~> 6"
  gem "webmock"
end
