# helmit

A spiffy, minimal theme based on information- and text-first, sans-serif designs. Created for a site featuring blog posts and project posts for a single developer or artist. Based off Broccolini's [Swiss theme](https://github.com/broccolini/swiss) with some design cues from academic, digital, and philosophy publishing layouts.

![](https://user-images.githubusercontent.com/20846414/53905663-114a0580-4017-11e9-9e3f-74f8550b2b74.png)

![](https://user-images.githubusercontent.com/20846414/53905680-2161e500-4017-11e9-9795-49c2d20c07df.png)

## Installation

Clone this repo.

## Usage

Make some changes to make the site more you while you're adding content:

- Start by configuring the site! Go to `_config.yml` and fill in as necessary.
- Edit the content in `layouts/homepage.html` for the blurbs on the front page.
- Revise the copyright notice in `_includes/footer.html` to take ownership! Maybe use a [Creative Commons](https://creativecommons.org/) if you're feeling generous.
- Put your content into the site! Remember to put a datestamp at the start of the filename for stuff in `_posts`. The sample content can give an example of how it works.
- Change the site's style -- `_sass/variables.scss` lets you mingle with the colors and fonts.
- The site is configured to be used as a personal site that features *blog posts* and *project posts* in two separate sections. If you have additional categories to add, then make another page in the root directory with `yourcategoryname.html` as the filename; you can just copy and paste content from `blog.html` and replace the word 'blog' with your category's name. Done.

## Contributing

Bug reports and pull requests are welcome [on GitHub](https://github.com/matildepark/helmit-jekyll-theme).

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
