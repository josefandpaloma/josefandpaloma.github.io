source "https://rubygems.org"


gem 'jekyll', "3.0.5"
gem 'jekyll-paginate'
gem 'jekyll-multiple-languages'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']