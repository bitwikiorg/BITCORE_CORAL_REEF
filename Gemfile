source "https://rubygems.org"

gem "jekyll", "~> 3.9.0"

# GitHub Pages plugins
group :jekyll_plugins do
  gem "github-pages"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jekyll-redirect-from"
  gem "jemoji"
end

# Required for Ruby 3.0.0+
gem "webrick", "~> 1.7"
gem "csv", "~> 3.2"

# Windows and JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]
