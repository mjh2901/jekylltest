# frozen_string_literal: true

source "https://rubygems.org"

# Use the github-pages gem so GitHub Pages' build environment can
# satisfy and lock the versions it supports. Do not also pin
# `jekyll` directly when using this gem — that causes conflicts.
gem "github-pages", group: :jekyll_plugins

group :jekyll_plugins do
  # You can keep these plugin declarations here. Note: GitHub Pages
  # only supports a specific set of plugins. If you rely on a plugin
  # not supported by Pages, consider building with GitHub Actions
  # instead of the Pages native build.
  gem "jekyll-feed"
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  # removed jekyll-shell-theme because it is not supported by GitHub Pages' github-pages gem
end
