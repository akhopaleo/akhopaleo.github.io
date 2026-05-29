# frozen_string_literal: true

source "https://rubygems.org"

# Force the exact stable versions that prevent the May update crash
gem "jekyll", "4.3.4"
gem "jekyll-sass-converter", "3.0.0"
gem "jekyll-theme-chirpy", "~> 7.5"

# Definite fixes for Ruby 3.4 standard library removal crashes
gem "csv"
gem "base64"
gem "bigdecimal"

group :test do
  gem "html-proofer", "~> 4.4"
end

# Windows configuration support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]