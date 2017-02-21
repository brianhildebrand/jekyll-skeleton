# jekyll-skeleton #

[![Gem Version](https://badge.fury.io/rb/jekyll-skeleton.svg)](https://badge.fury.io/rb/jekyll-skeleton)

Super simple implementation of [Skeleton CSS](http://getskeleton.com) as a Jekyll theme.

## Why? ##

I got tired of heavy CSS frameworks (Bootstrap & Foundation) being large downloads and getting in my way of customizing my blog.
I know you can select only the components you want from each of these and throw away others, but that seemed like the opposite direction than I wanted to work from.

## Installation ##

Add this line to your Jekyll site's Gemfile:

```ruby
gem "jekyll-skeleton"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-skeleton
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-skeleton

This will give you some simple, basic layouts (nothing fancy) and the basic CSS.
It's just a skeleton, after all ;)

You can add custom CSS in `assets/style.css` in your Jekyll site and it'll automatically be included.

## Adding Related Posts ##

To list related posts at the end of a post, add the following line to your `_config.yaml`:

    include_related_posts: true

Then, the top 5 related posts will be listed.
See Jekyll's [docs](https://jekyllrb.com/docs/variables/#site-variables) for more information on what this means.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/awochna/jekyll-skeleton. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## Development

To set up your environment to develop this theme, run `bundle install`.

There is an example site in the `example/` folder using this theme that you can develop against.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

