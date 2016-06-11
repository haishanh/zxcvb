---
title: Display a hero/banner
date: 2016-03-09
updated: 2016-06-11
toc: false
hero:
  image: http://7fva40.com1.z0.glb.clouddn.com/octocat.jpg
  height: 500px
---

Add the following config in the front matter of your post to get a stunning edge to edge banner picture(hero).

```
---
title: Test post
date: 2016-02-23
updated: 2016-02-29
hero:
  image: http://7fva40.com1.z0.glb.clouddn.com/octocat.jpg
  height: 500px
---
```

This will add inline style to the `<header>` element, rule mapping as below:

```
 * image    -> background-image    (this value can't be ommited)
 * size     -> background-size     (default to "cover")
 * position -> background-position (default to "center")
 * height   -> height              (default to "450px")
```

What you see, in the banner of this post, is my drawing of *Octocat* using app *53 paper* :)

{% admonition note %}

This config can also be applied in your site configuration file `_config.yml` to have a site level hero.

Hero config in your post front matter will overwrite what you added in your `_config.yml`.

{% endadmonition %}