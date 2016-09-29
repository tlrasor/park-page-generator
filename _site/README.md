## park-page-generator README

[![Build Status](https://travis-ci.org/tlrasor/park-page-generator.svg?branch=master)](https://travis-ci.org/tlrasor/park-page-generator)

### Introduction

park-page-generator is a simple template for [domain park pages](https://en.wikipedia.org/wiki/Domain_parking) based on the [Jekyll static site generator](http://jekyllrb.org).

### Requirements

Ruby 2.3.1 (tested)
bundler
jekyll

### Install

The install uses bundler to manage required gems. It should go something like this 
(assuming you already ruby and bundler installed):

```Bash
bundle install
bundle exec jekyll build
```

### Configuration

There are a few options in _config.yml which need to be set for the generator:

| Property        | Use         |
| ------------- |:-------------:|
| title     | Title of the site and main text on page |
| email      | Used to generate a contact link |
| description | Used for generating the site head tags for SEO |
| baseurl | The subpath of the site (probably not needed, leave as "") |
| url | The domain name of the site |
| facebook_username | Creates a button to your facebook page |
| twitter_username | Creates a button to your twitter page |
| google_analytics | Add your GA code here for analytics |

### Running in development

Jekyll can use an embedded WEBrick server for development purposes. Simply,

```Bash
bundle exec jekyll serve
```

### Deployment

I use [Surge CDN](http://surge.sh) to host my pages. 
The generator will create a CNAME file for surge and all that is necessary to use Surge is to follow their [getting started page](https://surge.sh/help/getting-started-with-surge) and [configure your DNS](https://surge.sh/help/adding-a-custom-domain).

### Contribute

Pull requests are welcome. Email any comments or questions to tlrasor at gmail dot com.

### License

[MIT](https://opensource.org/licenses/MIT)
