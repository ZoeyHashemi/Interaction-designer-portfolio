source "https://rubygems.org"

# Use Jekyll to build the site
gem "jekyll", "~> 4.3"

# Plugins for Jekyll
group :jekyll_plugins do
  gem "jekyll-feed"                 # Generates Atom feed
  gem "jekyll-archives"
  gem "jekyll-seo-tag"              # Adds SEO meta tags
  # gem "jekyll-sitemap"              # Creates a sitemap.xml
  # gem "jekyll-assets"             # Uncomment if using asset management
  # gem "jekyll-minifier"             # Minifies HTML
  # gem "rexml", "~> 3.2.5"           # Required for Ruby 3.x
  # gem "minima", "~> 2.5"
  gem "jekyll-paginate"
end

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo"
  gem "tzinfo-data"
end

# Required for Jekyll 4.x development
gem "webrick"                       # Needed for Ruby 3.x
