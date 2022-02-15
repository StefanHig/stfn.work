---
layout: page
title: about this site
permalink: /about_this_site/
---

This static site was built using Atom and Jekyll. The font is [Nunito](https://fonts.google.com/specimen/Nunito?category=Sans+Serif){:target="_blank"}. The core theme, called "no-style-please," was developed by Riccardo Graziosi (see [GitHub](https://github.com/riggraz/no-style-please){:target="_blank"} or [RubyGems](https://rubygems.org/gems/no-style-please){:target="_blank"} page). It's a minimal-CSS Jekyll theme, although I have customised it, especially the photography pages, in Sassy CSS. I also added social media [icons](https://evil-icons.io/) so you can reach me more easily. Otherwise, I wrote most of the actual content in Markdown (customizing HTML here and there), and the metadata in YAML.

Though the domain is hosted elsewhere, I've stored the site's directory and files at my [GitHub](https://github.com/StefanHig){:target="_blank"} so anybody else can take a look to see what I've done.

***

OK, let's talk about *the photography page*. You might've noticed it loads oddly, or slowly, for you. That's because I wanted to use a masonry layout, which means your images lay themselves out in a grid, but in the same way a stone mason works: i.e., unevenly, filling in open spaces organically. Setting up that styling within this template has been a task. That's because in order to *do* masonry in CSS, you have to [hack](https://css-tricks.com/piecing-together-approaches-for-a-css-masonry-layout/){:target="_blank"} how containers [display masonry](https://www.smashingmagazine.com/native-css-masonry-layout-css-grid/){:target="_blank"}. There's now ways to actually do masonry in your grid template in CSS, but they're [not evenly supported](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Masonry_Layout){:target="_blank"} across browsers and devices (if you're using a browser like Safari you might notice weird stuff happening to the photography grid). And I didn't want to use JavaScript, because this site is trying to use as little as possible.

Anyway, this is my first time building a website, so it's not perfect. If you run into issues, let me know. Feedback is always welcome!

<br>

&copy; Stefan Higgins, 2022
