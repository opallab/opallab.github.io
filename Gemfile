source "https://rubygems.org"

# Add this line for Ruby 3.4+ compatibility
gem "csv"

# Jekyll core
gem "jekyll", "~> 4.3.0"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-archives"
  gem "jekyll-include-cache"
end

# Development dependencies
group :development do
  gem "webrick", "~> 1.7"
  gem "jekyll-admin"
  gem "jekyll-sass-converter"
end

# Add Bootstrap and other frontend dependencies
gem "bootstrap", "~> 5.3.0"
gem "popper_js", "~> 2.11.0"
gem "sassc", "~> 2.4"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Use `libldns` gem for JRuby builds since newer versions of `unf` gem do not have a
# Java counterpart.
gem "unf", "~> 0.1.4", :platforms => [:jruby]

# Use `json` gem for JRuby builds since newer versions of `unf` gem do not have a
# Java counterpart.
gem "json", "~> 2.0", :platforms => [:jruby]

# Use `psych` gem for JRuby builds since newer versions of `unf` gem do not have a
# Java counterpart.
gem "psych", "~> 3.0", :platforms => [:jruby]

