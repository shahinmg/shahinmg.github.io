source 'https://rubygems.org'

# GitHub Pages builds this site with the github-pages gem, which pins Jekyll and
# the whole supported plugin set (jekyll-feed, jekyll-gist, jekyll-paginate,
# jekyll-sitemap, jekyll-redirect-from, jemoji). Depending on it alone keeps a
# local `bundle exec jekyll serve` byte-for-byte consistent with what GitHub
# publishes -- listing jekyll or the plugins separately here fights those pins.
gem 'github-pages', group: :jekyll_plugins

# Not bundled with github-pages, and `jekyll serve` needs it on Ruby 3.x.
gem 'webrick', '~> 1.8'

# Upstream pin to avoid a resolution conflict pulled in transitively.
# If bundler ever complains about this line, it is safe to drop.
gem 'connection_pool', '2.5.0'
