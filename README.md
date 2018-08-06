# Kasper 🤡 (formerly Casper)
[![Build Status](https://travis-ci.org/sh0rez/Kasper.svg?branch=master)](https://travis-ci.org/sh0rez/Kasper)
![tag](https://img.shields.io/github/tag/sh0rez/Kasper.svg)
![license](https://img.shields.io/github/license/sh0rez/Kasper.svg)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsh0rez%2FKasper.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsh0rez%2FKasper?ref=badge_shield)

Theme for the Ghost blogging platform, forked from the official Casper theme, modified for use on my private blog and oriented towards the DSGVO / GDPR.
### Most relevant added / improved features:
* 🖍️ Syntax Highlighting using [`prism.js`](https://prismjs.com/index.html)
* 📝 Comments using [DISQUS](https://disqus.com/)
* ⏱️ Page Speed Improvements
	* Asynchronous loading of most resources
	* Minified JS / CSS
* ⚖️ DSGVO / GDPR Compliance
	* 👮 [`Shariff`](https://github.com/heiseonline/shariff) by heise-online to provide privacy-friendly  social-share buttons
	* 🍪 [Cookie Consent](https://silktide.com/tools/cookie-consent/download/) by silktide
	* Links to Privacy Policy (`/pricacy)` and Legal Notice (`/legal`) in Footer
<hr>

### Excerpt from the original readme, kept for informative purposes:
> # Development 
> 
> Casper styles are compiled using Gulp/PostCSS to polyfill future CSS
> spec. You'll need Node and Gulp installed globally. After that, from
> the theme's root directory:
> 
> ```bash $ yarn install $ yarn dev ```
> 
> Now you can edit `/assets/css/` files, which will be compiled to
> `/assets/built/` automatically.
> 
> The `zip` Gulp task packages the theme files into
> `dist/<theme-name>.zip`, which you can then upload to your site.
> 
> ```bash $ yarn zip ```
> 
> # PostCSS Features Used
> 
> - Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major
> versions of every browser.
> - Variables - Simple pure CSS variables
> - [Color Function](https://github.com/postcss/postcss-color-function)
> 
> 
> # SVG Icons
> 
> Casper uses inline SVG icons, included via Handlebars partials. You
> can find all icons inside `/partials/icons`. To use an icon just
> include the name of the relevant file, eg. To include the SVG icon in
> `/partials/icons/rss.hbs` - use `{{> "icons/rss"}}`.
> 
> You can add your own SVG icons in the same manner.


# Copyright & License
**Kasper Theme**: Copyright (c) 2018 shorez - Released under the [`GPLv2`](LICENSE)  
formerly **Original Casper Theme**: Copyright  (c) 2013-2018 Ghost Foundation - Released under the [`MIT license`](https://github.com/TryGhost/Casper/blob/master/LICENSE).


[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fsh0rez%2FKasper.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fsh0rez%2FKasper?ref=badge_large)