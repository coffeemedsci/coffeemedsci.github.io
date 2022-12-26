# README

[CoffeeSciMed site](https://coffeemedsci.com)


# To view locally
## Necessary dependencies
- Gcc and Make
- RubyGems
- Ruby

Run 
```
bundle init
gem install jekyll-theme-minimal
```

Add these lines in the Gemfile
```
gem 'nokogiri'
gem 'rack', '~> 2.2.4'
gem 'rspec'
gem 'jekyll', '~> 4.0'
gem "jekyll-theme-minimal", "~> 0.2"
```
Then run
```
bundle install
bundle exec jekyll serve
```

add '--livereload' for the site to update as changes are applied