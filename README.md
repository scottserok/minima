# minima fork

This project is a fork of [jekyll/minima](https://github.com/jekyll/minima).

*Minima is a one-size-fits-all Jekyll theme for writers*. It's Jekyll's default (and first) theme. It's what you get when you run `jekyll new`.

Changes in this fork include

  - Removed `jekyll-feed` dependency
  - Added `jekyll-coffeescript` dependency

## Installation

Add this line to your Jekyll site's Gemfile:

```ruby
gem "minima", git: "git@github.com:scottserok/minima.git"
```

And then execute:

    $ bundle

## Usage

Have the following line in your config file:

```yaml
theme: minima
```

### Customizing assets

Add a style.scss and index.coffee file to your project in order to customize
styles and add your own scripts.
```
root
├── assets
│   ├── css
│   │   └── style.scss
│   └── js
│       └── index.coffee
```

Be certain to import the minima skin of your choice and add custom styles.
```
---
---
@import "minima-classic";
.text-center { text-align: center; }
```


## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
