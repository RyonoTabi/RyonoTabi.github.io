# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll-theme-chirpy", "~> 7.0", ">= 7.0.1"

group :test do
  gem "html-proofer", "~> 5.0"
end

# Some dependencies will be not in default gems since Ruby 3.4.0
# Gemfile
if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new('3.3')
  gem "csv", "~> 3.3"
  gem "base64", "~> 0.2.0"
  gem "bigdecimal", "~> 3.1.5"
end