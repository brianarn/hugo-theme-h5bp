# hugo-theme-h5bp

## Description

In the event that you're not familiar with the [HTML5 Boilerplate][h5bp]
project, here's a quote from their website.

> HTML5 Boilerplate helps you build fast, robust, and adaptable web apps or
> sites. Kick-start your project with the combined knowledge and effort of 100s
> of developers, all in one little package.

This project is an attempt to provide a H5BP based theme for [Hugo][], which is
a super speedy and seemingly nifty static site generator.

The baseline is H5BP, along with some fairly minimal personal choices for
markup, nothing fancy. It's all also going to be easily overriden by users of
the theme. It won't provide a whole heck of a lot, aside from a very basic
baseline that should prove to be a friendly site for a wide variety of modern
devices.

As of this writing, H5BP 5.0.0 is the baseline in use. There has been no
customized build or anything, it's just a stock "All the things in v5.0.0".
Updates will be assessed as available, or feel free to submit a PR. :)

## Site Params

This theme supports the following additional site parameters:

### `googleAnalytics`

The `partials/google-analytics.html` partial uses this site parameter when
rendering out the `script` element to inject Google Analytics

### Post Front-matter options

The `layout/_default/single.html` template will check for the presence of
`rendertoc` in your item's front-matter, and if it exists, it will render the
`{{ .TableOfContents }}` variable into the page.

[h5bp]: https://html5boilerplate.com/
[Hugo]: http://gohugo.io/
