# frozen_string_literal: true

source "https://rubygems.org"
ruby RUBY_VERSION

gemspec

group :development do
  gem "guard-rspec", require: false
  gem "pry", require: false
end

group :test do
  gem "rspec", "~> 3", require: false
  gem "rubocop", "0.45.0", require: false
  gem "coveralls", require: false
end

group :development, :test do
  gem "rake"
end
