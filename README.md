Backport of v1.5.1 for next stack: Ruby 2.2.6 + Rails 3.2.22.5 + ActiveAdmin 1.0.0.pre5

# ActiveMaterial

An ActiveAdmin skin based on Google's Material Design.

<img src="http://i.imgur.com/kDkGzYe.png">

1. [Installation](#installation)
2. [Usage](#usage)
3. [Customization](#customization)
4. [Contributing](#contributing)

## Installation

Add this line to your application's Gemfile:

```ruby
gem "active_material", github: "garantexpress/activeadmin_material"
```

And then execute:

```shell
$ bundle
```

Or install it yourself as:

```shell
$ gem install active_material
```

## Usage

In `app/assets/stylesheets/active_admin.css.scss`, replace:

`@import "active_admin/base";`

with

`@import "active_material";`

Additionally, ActiveMaterial comes with an optional JavaScript bundle that adds a few additional features. It should be included right after the active_admin base script.

In app/assets/javascripts/active_admin.js, add:

```
//= require active_material
```

## Customization

Refer to the [Customization Guide](./docs/customization.md).

***

<a href="http://code.viget.com">
  <img src="http://code.viget.com/github-banner.png" alt="Code At Viget">
</a>

Visit [code.viget.com](http://code.viget.com) to see more projects from [Viget.](https://viget.com)
