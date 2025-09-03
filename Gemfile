source 'https://rubygems.org'

# Use github-pages gem for GitHub Pages compatibility
gem "github-pages", group: :jekyll_plugins

# Core plugins that directly affect site building
group :jekyll_plugins do
    gem 'jekyll-archives'  # Fixed: was jekyll-archives-v2
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-get-json'
    gem 'jekyll-imagemagick'
    gem 'jekyll-jupyter-notebook'
    gem 'jekyll-link-attributes'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-regex-replace'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-tabs'
    # Removed jekyll-terser git dependency - not compatible with GitHub Pages
    gem 'jekyll-toc'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'classifier-reborn'
end

# Development only gems (won't be installed on GitHub Pages)
group :development do
  gem "jekyll-admin"
end

# Additional gems for functionality
gem 'unicode_utils', '~> 1.4'
gem 'webrick', '~> 1.7'

# Gems for development or external data fetching
group :other_plugins do
    gem 'css_parser'
    gem 'feedjira'
    gem 'httparty'
    gem 'observer'
    gem 'ostruct'
end

# Platform-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
