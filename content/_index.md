---
# Leave the homepage title empty to use the site title
title: Kevin Grieco
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        👋 Hi, there! I'm **Kevin G**, a man on a mission.
        {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: apartment 1.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
      css_class: d-flex fullscreen align-items-center
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
   - block: about.education
    id: about
    content:
      title: Education
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin


---

