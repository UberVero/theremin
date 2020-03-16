---
title: Home
sections:
- type: heroblock
  template: heroblock
  section_id: hero
  component: hero_block.html
  content: This section can contain a subtitle or tagline. The recommended length
    is one to three sentences, but can be changed as you prefer.
  title: ''
  actions:
  - label: Test action
    url: ''
- type: contentblock
  template: contentblock
  title: About
  section_id: about
  actions:
  - label: Subscribe to my newsletter
    url: https://veronica.substack.com/
  - label: Contact Me
    url: "/contact"
  component: content_block.html
  content: "My name is Veronica Picciafuoco and I'm based in \U0001F332Palo Alto\U0001F332.
    I’ve been working in tech for about 9 years. My focus area for the past few years
    has been **B2B product marketing** for online marketplaces (advertising, analytics,
    legal tech)."
  image: ''
- type: postsblock
  template: postsblock
  title: Recent Posts
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
