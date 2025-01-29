source "https://rubygems.org"

# Jekyll and its dependencies
gem "jekyll", "~> 4.3.3"

# Default theme
gem "minima", "~> 2.5"

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-tagging"  # Gem for tagging in blog posts
end

# Windows and JRuby dependencies
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Uncomment if you want to use GitHub Pages
# gem "github-pages", group: :jekyll_plugins
