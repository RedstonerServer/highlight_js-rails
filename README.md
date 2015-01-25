# Highlight.js for rails 4

Rails pipeline wraper for highlight.js http://softwaremaniacs.org/soft/highlight/en/

**This is a fork updated to higlightjs 8.4**

## Install

In you Gemfile:

```Ruby
gem 'highlight_js-rails', :git => 'git://github.com/RedstonerServer/highlight_js-rails.git'
```

Then `bundle install`

## Usage

application.js

```javascript
//= require highlight_js/highlight
//= require highlight_js/languages/ruby

hljs.initHighlightingOnLoad();
```

application.css

```css
*= require highlight_js/github
```