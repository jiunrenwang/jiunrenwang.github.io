---
layout: post
---

some draft content

the draft content doesn't need the same naming convention as a post

just move this draft into posts once you're ready to publish

categories: blog, life, tech,

permalink: /:categories/:day/:year/:month/:title.html
for the _config.yml

below plugins create a new category called defaults

defaults:
  -
    scope:
        path: ""
        type: ""
    values:
        layout: "post"
        title: "My Title"