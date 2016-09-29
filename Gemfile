source "https://rubygems.org"

ruby '2.3.1'

gem "jekyll", '3.2.1' 
gem "minima"
gem "font-awesome-sass"

gem "park-page-generator-theme-dark", "~> 1.0.0", :git => 'https://github.com/tlrasor/park-page-generator-theme-dark.git'

group :jekyll_plugins do
  gem "jekyll-mentions"
  gem "jekyll-redirect-from"
  gem "jekyll-paginate"
  gem "jekyll-gist"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

group :test,:development do
  gem 'rake'
  gem 'logging'
  gem "html-proofer"
end