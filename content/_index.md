---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: 
      cta_alt:
        label: Ask a question
        url: 
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Sungyoung Moon</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
    
       

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
  - block: experience
    content:
        - title: Test Engineer
          company: SGS North America
          company_url: 'https://www.sgs.com/en-us'
          company_logo: sgs
          location: San Diego, CA
          date_start: '2024-06-01'
          date_end: '202-06-01'
          description: |2-
              * Conduct Radio Frequency Over-the-Air (OTA) antenna testing for major clients including Google and Samsung on mobile products (CDMA, GSM, LTE, Wi-Fi, 5G), ensuring compliance with client and SGS                       quality system requirements.
              * Perform debugging, test engineering, and system management for wireless clients using tools like EMQUEST, CRTx, and EMC32.
              * Maintain industry standard test platforms, troubleshoot issues, and ensure compliance with accreditation.
              * Collaborate with customers and test equipment manufacturers to resolve testing issues and deliver high quality service.   

    
              
        - title: Web Developer
          company: Alpha Gamma Sigma Honor Society, Santa Monica College
          company_url: ''
          company_logo: ags
          location: Santa Monica, CA
          date_start: '2019-01-01'
          date_end: '2021-01-01'
          description: |2-
    
              * Developed a student database to manage student information and track their progress, including volunteering records, attendance, and membership fees.
              * Created and maintained the official website, serving as a central online hub for organization information, updates, and resources.
              * Established and managed an e-commerce platform for selling organization-related merchandise.
              * Implemented an event calendar system to schedule and organize various chapter events and volunteer activities.
              * Designed and maintained a digital library for newsletters, providing an easily accessible resource for members and stakeholders to review past content and updates.

        - title: Administrative Support Specialist, Sergeant
          company: Republic of Korea Army
          company_url: ''
          company_logo: army
          location: 
          date_start: '2014-12-01'
          date_end: '2016-09-30'
          description: Managed administrative tasks and maintained records using military security databases and software, ensuring security and data integrity.
        - title: Technical Consultant, Self-employed
          company: Kmong Inc.
          company_url: ''
          company_logo: kmong
          location: 
          date_start: '2013-01-01'
          date_end: '2014-12-31'
          description: Advised startups on web development and maintenance to drive business success through Kmong Inc.
        - title: Gaming / Anime Community Website, Founder
          company: 
          company_url: ''
          company_logo: myweb
          location: 
          date_start: '2010-10-01'
          date_end: '2014-12-31'
          description: Founded and managed a gaming/anime community website during high school, which reached 100K+ users and 40M+ visits in three years. Led operational decision-making and organized anime events at expos.
    design:
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
        - name: Programming
          tag: Programming
        - name: Other
          tag: Demo
    
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

   


   
---
