Planit Rails
================

PlanitJS is a tool built on jQuery to help you interact with markers/hotspots
on an image or blank container. This gem adds the script and stylesheet to your
asset pipeline.

Refer to [PlanitJS](https://github.com/planitjs/planit) for PlanitJS's usage.

Installation
----------------

Add this line to your application's Gemfile:

```ruby
gem 'planit-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install planit-rails

## Usage

Load the scripts, and don't forget jQuery:

**application.js**

```js
//= require jquery
//= require planit
```

You can also add the stylesheet as well:

**application.scss**

```scss
@import "planit";
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/planit-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
