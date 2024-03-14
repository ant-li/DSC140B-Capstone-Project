source "https://rubygems.org"

# If you want to use GitHub Pages, uncomment the line below. 
# GitHub Pages already includes a set of Jekyll and plugin versions that are guaranteed to work together.
# This makes managing dependencies easier.
gem "github-pages", group: :jekyll_plugins

# This will include any plugins specific to your project that GitHub Pages supports.
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby compatibility gems.
# These are not necessary unless you are working on Windows or JRuby.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
  gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
end
gem 'webrick'
