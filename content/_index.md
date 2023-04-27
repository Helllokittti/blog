---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Programming
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Sport
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Drawing
          description: 10%
          icon: camera-retro
          icon_pack: fas
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ассистент
          company: Университет дружбы народов
          company_url: ''
          company_logo: org-gc
          location: Москва
          date_start: '2023-02-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Прогаммист
          company: ГазПром
          company_url: ''
          company_logo: org-x
          location: Москва
          date_start: '2020-01-01'
          date_end: '2021-12-31'
          description: Ассистирование в отделе айти.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://stepik.org
          date_end: ''
          date_start: '2022-01-25'
          description: ''
          organization: Stepik
          organization_url: https://www.coursera.org
          title: Сертификат об успешном освоении Python
          url: ''
        
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
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
        publication_type: "

Басманова Дарья Кирилловна 😻
Басманова Дарья Кирилловна
Студентка
РУДН Университет Дружбы Народов

Всем привет! Меня зовут Даша. Учусь на факультете Физико-математических и естественных наук. Направление Бизнес-информатика. Я студентка 1 курса. Председатель Комиссии по Качеству образования. Честная, добрая и заботливая. Люблю рисовать и занимаюсь спортом. Работаю баристой. Буду рада видеть вас на своем сайте.
Skills
Programming

90%
Sport

100%
Drawing

10%
Experience
 
 
 
 
 
Университет дружбы народов
Ассистент
Университет дружбы народов
February 2023 – Present Москва

Responsibilities include:

    Analysing
    Modelling
    Deploying

 
 
 
 
 
ГазПром
Прогаммист
ГазПром
January 2020 – December 2021 Москва
Ассистирование в отделе айти.
Accomplish­ments
Сертификат об успешном освоении Python"
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: db1406@yandex.ru
      phone: 89854649244
      
      address:
        
        city: Moscow
        region: 
        postcode: ''
        country: Russia
        country_code: RF
      
     
      contact_links:
        - icon: 
          icon_pack: 
          name: GitHub
          link: 'https://github.com/Helllokittti'
        - icon: 
          icon_pack: 
          name: academia
          link: 'https://independent.academia.edu/DariaBasmanova'
        - icon: 
          icon_pack: fab
          name: Elibrary
          link: 'https://elibrary.ru/project_user_office.asp'
        - icon: 
          icon_pack: 
          name: ORCID
          link: 'https://orcid.org/my-orcid?orcid=0009-0003-3042-7726&justRegistered=true'
        - icon: 
          icon_pack: 
          name: ELSEVIER
          link: 'https://account.elsevier.com/account'
         
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
