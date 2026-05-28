source "https://rubygems.org"

gem "github-pages", "~> 231", group: :jekyll_plugins
gem "minima", "~> 2.5"
gem "jekyll-feed", "~> 0.12"
gem "jekyll-seo-tag", "~> 2.8"
gem "csv"
gem "faraday-retry"

# Windows and JRuby do not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Lock `http_parser.rb` and `ffi` so default versions are used
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
gem "ffi", "~> 1.15.0", :platforms => [:mingw, :x64_mingw, :mswin]
