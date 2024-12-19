source "https://rubygems.org"

# Use Jekyll to manage your site
gem "jekyll-default-layout"

# Use the Just the Docs theme
gem "just-the-docs", "~> 0.10.0"

# Explicitly add csv and base64 gems to silence Ruby 3.4+ warnings
gem "csv"
gem "base64"

# If you want to use GitHub Pages, uncomment the line below
# gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for file watching on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Fix compatibility issues with JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
