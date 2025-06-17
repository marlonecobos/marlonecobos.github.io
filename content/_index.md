---
title: 'MEC'
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - name: Statistics
      icon: "chart-line"
      icon_pack: fas
    - name: R
      icon: "r-project"
      icon_pack: fab
    - name: GIS
      icon: q
      icon_pack: fas
    - name: Python
      icon: python
      icon_pack: fab
    - name: Linux
      icon: linux
      icon_pack: fab
    - name: AI
      icon: brain
      icon_pack: fas
    title: Skills
- block: collection
  content:
    count: 3
    filters:
      author: ''
      category: ''
      exclude_featured: no
      exclude_future: no
      exclude_past: no
      folders: 
        - post
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    subtitle: ''
    text: ''
    title: Recent Posts
  design:
    columns: '2'
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: Disease Biogeography
      tag: Biogeography
    - name: Methods and Tools
      tag: Methods and tools
    default_button_index: 0
    filters:
      folders: project
    title: Projects
  design:
    columns: '1'
    flip_alt_rows: no
    view: showcase
  id: projects
- block: collection
  content:
    count: 5
    filters:
      exclude_featured: yes
      folders: 
        - publication
    text: ''
    subtitle: "[All publications](./publication/all_pubs)"
    title: Featured Publications
  design:
    columns: '2'
    view: citation
  id: featured
- block: collection
  content:
    count: 4
    filters:
      author: ''
      category: ''
      exclude_featured: no
      exclude_future: no
      exclude_past: no
      folders: 
        - software
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    subtitle: "[My GitHub](https://github.com/marlonecobos)"
    text: ''
    title: Software
  design:
    columns: '2'
    view: compact
  id: software
- block: collection
  content:
    count: 2
    filters:
      author: ''
      category: ''
      exclude_featured: no
      exclude_future: no
      exclude_past: no
      folders: 
        - mentoring
      publication_type: ''
      tag: ''
    offset: 0
    order: desc
    subtitle: ''
    text: ''
    title: Mentoring <br> and <br> Engagement<br>
  design:
    columns: '2'
    view: compact
  id: mentoring
- block: contact
  content:
    address:
      city: Lawrence
      country: United States
      country_code: US
      postcode: '66045'
      region: KS
      street: <a href="https://goo.gl/maps/2nW9ccAYqfEo9uk6A" target="_blank">1345
        Jayhawk Blvd</a>
    autolink: yes
    contact_links:
    - icon: linkedin
      icon_pack: fab
      link: https://www.linkedin.com/in/marlon-e-cobos-009203b4/
      name: 'Marlon E. Cobos'
    - icon: github
      icon_pack: fab
      link: https://github.com/marlonecobos
      name: marlonecobos
    directions: Dyche Hall, 7th floor
    email: marloncobos@ku.edu
    form:
      formspree:
        id: null
      netlify:
        captcha: no
      provider: netlify
    office_hours: 09:00 to 17:00 (09:00 am to 05:00 pm)
    phone: "(1)785-864-3926"
    subtitle: null
    text: A shortcut to start communications.
    title: Contact
  design:
    columns: '2'
  id: contact
date: "2023-08-24"
output:
  html_document:
    df_print: paged
type: landing
---
