---
# Leave the homepage title empty to use the site title
title: 'Bio'
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Un umanista contemporaneo
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: stefano
#  - block: skills
#    content:
#      title: Skills
#      text: ''
#      # Choose a user to display skills from (a folder name within `content/authors/#`)
#      username: stefano
#    design:
#      columns: '1'
#  - block: experience
#    content:
#      title: Experience
#      # Date format for experience
#      #   Refer to https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Experiences.
#      #   Add/remove as many `experience` items below as you like.
#      #   Required fields are `title`, `company`, and `date_start`.
#      #   Leave `date_end` empty if it's your current employer.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - title: CEO
#          company: GenCoin
#          company_url: ''
#          company_logo: org-gc
#          location: California
#          date_start: '2021-01-01'
#          date_end: ''
#          description: |2-
#              Responsibilities include:
#
#              * Analysing
#              * Modelling
#              * Deploying
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor #physics.
#    design:
#      columns: '2'
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          icon: coursera
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use #cases.
#          icon: edx
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/#uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          icon: datacamp
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
  - block: collection
    id: posts
    content:
      title: Dal blog
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./#publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
---
