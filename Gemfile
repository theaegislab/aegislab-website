source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "bulma-clean-theme", "1.0.0"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# webrick is no longer bundled with Ruby by default; jekyll serve needs it
gem "webrick", "~> 1.8"
