# frozen_string_literal: true

source "https://rubygems.org"
gemspec

gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"
gem "rss" if RUBY_VERSION >= "3.0.0"

install_if -> { Gem.win_platform? } do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data"
end
