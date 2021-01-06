# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/TrentonRochelle/TrentonRochelle.github.io" }

gem "jekyll"
# gem "rails"
gem "jekyll-theme-clean-blog"
gem "webrick", "~> 1.7"

group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.6"
    gem "jekyll-paginate", "~> 1.1.0"
    gem "jekyll-sitemap"
  end
  
  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
  
  # Performance-booster for watching directories on Windows
  gem "wdm", "~> 0.1.0" if Gem.win_platform?
  