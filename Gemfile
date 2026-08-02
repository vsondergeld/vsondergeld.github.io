source "https://rubygems.org"

# Ruby 3.4+ no longer bundles these as default gems, but Jekyll 3.9 still
# requires them without declaring the dependency itself.
gem "csv"
gem "bigdecimal"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# Using plain, modern Jekyll instead of the "github-pages" meta-gem for local
# preview. github-pages hard-pins Jekyll 3.9 / Liquid 4.0.3 to mirror GitHub's
# old legacy Pages build image, but this repo has no .github/workflows, so
# GitHub Pages builds the live site on its own infrastructure and never reads
# this Gemfile anyway. Pinning to ancient Jekyll only broke local preview on
# modern Ruby (removed String#tainted?/#untaint), so we don't need it here.
# gem "github-pages", group: :jekyll_plugins

gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'hawkins'
  gem "webrick", "~> 1.8"
end

gem 'tzinfo-data'