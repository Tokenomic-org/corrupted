source "https://rubygems.org"

# Use GitHub Pages gem
gem "github-pages", group: :jekyll_plugins

# Remove direct Jekyll and Minima gem dependencies to avoid conflicts
# gem "jekyll", "~> 3.8.7"
# gem "minima", "~> 2.5"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-paginate-v2"
  gem "jekyll-tagging"
  gem "jekyll-archives"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Required for XML parsing
gem "rexml", "~> 3.2", ">= 3.2.4"

# Add Faraday retry middleware
gem "faraday-retry"

