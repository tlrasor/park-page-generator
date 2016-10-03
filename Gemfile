source "https://rubygems.org"

ruby '2.3.1'

gem "jekyll", '3.2.1' 

group :jekyll_themes do
  gem "park-page-generator-theme-dark", "1.0.1", 
    :git => 'https://github.com/tlrasor/park-page-generator-theme-dark.git',
    :tag =>'1.0.1'
end 

group :test,:development do
  gem 'rake'
  gem 'logging'
  gem "html-proofer"
end