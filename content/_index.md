---
title: Home
sections:
  - component: hero_block.html
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    section_id: hero
    title: 'Hi, I''m Alec Pokarier'
    type: heroblock
  - component: portfolio_block.html
    layout_style: mosaic
    num_projects_displayed: 4
    section_id: latest-projects
    subtitle: Here's some of the local issues I'm passionate about
    title: Fighting For Our Fair Share
    type: portfolioblock
    view_all_text: View All
    view_all_url: portfolio/index.html
  - component: services_block.html
    section_id: services
    serviceslist:
      - content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla tortor at, pulvinar orci.
        title: Our Fair Share
      - content: >-
          Donec lobortis velit sed suscipit lobortis. Ut non quam metus. Nullam
          a maximus mi. Quisque justo nunc, sollicitudin euismod euismod at,
          tincidunt ut tellus. Vivamus rhoncus mattis varius. 
        title: Our Community
      - content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
        title: Our Safety
      - content: >-
          Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis
          justo, sit amet condimentum lorem nibh vel quam. Duis consectetur
          lorem ipsum, non efficitur urna viverra et.
        title: Our Future
    subtitle: An optional subtitle of the section
    title: What I Value
    type: servicesblock
  - component: testimonials_block.html
    section_id: testimonials
    subtitle: Here's what others have to say about me
    testimonialslist:
      - author: John Doe
        avatar: /images/screen-shot-2019-07-30-at-8.52.23-pm.png
        content: >-
          Alec has been instrumental in gaining funding for our local mens shed.
          He was able to approach our federal member on our behalf and help
          secure an $80,000 grant.
      - author: Jane Roe
        avatar: images/jane_roe.jpg
        content: >-
          Alec has been a huge supporter of our running club for the past 12
          months. He's been instrumental in helping our membership grow.
    title: What they said...
    type: testimonialsblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: posts_block.html
    num_posts_displayed: 2
    section_id: latest-posts
    subtitle: Keep up to date with the local news
    title: News
    type: postsblock
  - component: contact_block.html
    section_id: contact
    subtitle: An optional subtitle of the section
    title: Contact Me
    type: contactblock
menu:
  main:
    name: Home
    weight: 1
layout: home
---

