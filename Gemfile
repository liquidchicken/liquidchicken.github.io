source 'https://rubygems.org'

require 'json'
require 'open-uri'

versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']

gem 'jekyll'

group :jekyll_plugins do
  gem 'jekyll-mentions'
  gem 'jemoji'
  gem 'jekyll-redirect-from'
  gem 'jekyll-sitemap'
  gem 'redcarpet'
  gem 'pygments.rb'
end
