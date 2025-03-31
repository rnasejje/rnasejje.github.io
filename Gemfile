# frozen_string_literal: true

source 'https://rubygems.org'

gem 'github-pages'
gem 'jekyll-feed'
gem 'jekyll-sitemap'
gem 'jekyll-redirect-from'
gem 'jemoji'

# Include 'webrick' gem for Ruby versions >= 3.0
gem 'webrick', '~> 1.8'

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'wdm', '>= 0.1.1', '< 0.3' # Allows version 0.2.0 to be installed
  gem 'tzinfo', '>= 1', '< 3' # Timezone library
  gem 'tzinfo-data' # Timezone data required on Windows
end

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-octicons'
  gem 'faraday-retry'
end
gem "jekyll-livereload", "~> 0.2.2"
