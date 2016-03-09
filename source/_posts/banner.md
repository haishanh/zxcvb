---
title: Display a banner
date: 2016-03-09
updated: 2016-03-09
toc: false
banner:
  image: http://7fva40.com1.z0.glb.clouddn.com/octocat.jpg
  height: 700px
---

Add the following config in the front matter of your post to get a stunning edge to edge banner picture.

```
---
title: Test post
date: 2016-02-23
updated: 2016-02-29
banner:
  image: http://7fva40.com1.z0.glb.clouddn.com/carlog-404-sprite.jpg
  size: cover
  position: center
  height: 450px
---
```


This will add inline style to the `<header>` element, rule mapping as below:

```
 * image    -> background-image    (this value can't be ommited)
 * size     -> background-size     (default to "cover")
 * position -> background-position (default to "center")
 * height   -> height              (default to "450px")
```