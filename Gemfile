source "https://rubygems.org"

# Happy Jekylling!
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-seo-tag", "~> 2.7"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-menus", "~> 0.6.1"
end

install_if -> { Gem.win_platform? } do
  gem "wdm", "~> 0.1.1"
  gem "tzinfo", "~> 2.0.4"
  gem "tzinfo-data"
end
