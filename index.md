---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: A developer developing things.
  title: Welcome
  actions: []
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Contact Me
    url: "/contact"
  component: content_block.html
  content: My name is Victor Corvalan, I'm a videogame and mobile front-end developer
    from Asunción, Paraguay.
  image: ''
- type: postsblock
  template: postsblock
  title: Latest projects
  section_id: recent-posts
  actions:
  - label: View Blog
    url: blog/index.html
  component: posts_block.html
  num_posts_displayed: 4
layout: home
menu:
  main:
    weight: 1

---
