---
title: Authors
date: 2016-06-11
toc: false
author:
  - haishanh
  - octocat
  - no_name
---

See authors of this page below? At the end of the post just before the site footer.

To have this, define your authors list in your site `_config.yml` like this:

```text
authors:
  haishanh:
    name: Haishan
    link: http://hanhaishan.com
    avatar: https://avatars0.githubusercontent.com/u/1166872?v=3
  octocat:
    name: The Octocat
    avatar: https://avatars0.githubusercontent.com/u/583231?v=3
```

Then add this in the front matter of your post:

```text
author:
  - haishanh
  - octocat
  - no_name
```

Authors that are listed in your front matter but not defined in your site config will have a default avatar.