---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Postdoctoral Fellow
          company: Memorial University of Newfoundland
          company_url: https://www.mun.ca
          company_logo: ''
          location: St. John's, NL, Canada
          date_start: '2023-04-01'
          date_end: ''
          description: ''
        - title: Per Course Instructor
          company: Memorial University of Newfoundland
          company_url: https://www.mun.ca
          company_logo: ''
          location: St. John's, NL, Canada
          date_start: '2023-08-28'
          date_end: '2023-12-15'
          description: ''
        - title: Research and Teaching Assistant
          company: Memorial University of Newfoundland
          company_url: https://www.mun.ca
          company_logo: ''
          location: St. John's, NL, Canada
          date_start: '2018-09-24'
          date_end: '2023-03-23'
          description: ''
        - title: Assistant Professor
          company: Chittagong University of Engineering & Technology
          company_url: https://www.cuet.ac.bd
          company_logo: ''
          location: Chattogram, Bangladesh
          date_start: '2017-12-03'
          date_end: '2018-09-17'
          description: ''
        - title: Research and Teaching Assistant
          company: Memorial University of Newfoundland
          company_url: https://www.mun.ca
          company_logo: ''
          location: St. John's, NL, Canada
          date_start: '2016-01-15'
          date_end: '2018-01-03'
          description: ''
        - title: Assistant Professor
          company: Chittagong University of Engineering & Technology
          company_url: https://www.cuet.ac.bd
          company_logo: ''
          location: Chattogram, Bangladesh
          date_start: '2015-07-02'
          date_end: '2016-01-10'
          description: ''
        - title: Lecturer
          company: Chittagong University of Engineering & Technology
          company_url: https://www.cuet.ac.bd
          company_logo: ''
          location: Chattogram, Bangladesh
          date_start: '2011-10-12'
          date_end: '2015-07-01'
          description: ''
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: 'Courses Taught'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2023-12-15'
          date_start: '2023-08-28'
          description: |
            + Math 3132 (Numerical Analysis I): Fall 2023
          icon: 
          organization: Per Course Instructor, Mathematics and Statistics
          organization_url: 
          title: Memorial University of Newfoundland
          url: https://www.mun.ca
        - certificate_url: 
          date_end: '2022-12-15'
          date_start: '2018-09-24'
          description: |
            + Math 3132-002 (Numerical Analysis I Laboratory): Fall 2022 
            + Math Help Centre: Fall 2018 – Spring 2022
            + Math 2051 (Linear Algebra II): Winter 2022
            + Math 2050 (Linear Algebra I): Winter 2021
            + Math Bridging Program: Spring 2020
            + Math 2090 (Mathematics of Finance): Winter 2020 
            + Math 2050 (Linear Algebra I): Fall 2019 
            + Math 1001 (Calculus II): Winter 2019
          icon: 
          organization: Teaching Assistant, Mathematics and Statistics
          organization_url: 
          title: 'Memorial University of Newfoundland'
          url: https://www.mun.ca
        - certificate_url: 
          date_end: '2017-12-15'
          date_start: '2016-05-01'
          description: |
            + ENGI 3911 (Chemistry & Physics of Engineering Materials): Fall 2017 
            + ENGI 4961 (Fluid Mechanics I): Spring 2017 
            + ENGI 8690/9114 (Advanced Reservoir Engineering): Winter 2017 
            + ENGI 4961 (Fluid Mechanics I): Spring 2016
          icon: 
          organization: Teaching Assistant, Process Engineering
          organization_url: 
          title: 'Memorial University of Newfoundland'
          url: https://www.mun.ca
        - certificate_url: 
          date_end: '2018-09-17'
          date_start: '2011-10-12'
          description: |
            + PME 111 (Reservoir Rock and Fluid Properties): Batch- 2013 
            + PME 112 (Reservoir Rock and Fluid Properties Laboratory): Batch- 2013 
            + PME 151 (Geology for Mining & Petroleum Engineers): Batch- 2011, 2013 
            + PME 152 (Geology Laboratory): Batch- 2011, 2013 
            + PME 153 (Introduction to Petroleum and Mining Engineering): Batch- 2012 
            + PME 261 (Rock Mechanics): Batch- 2010, 2011, 2012, 2013 
            + PME 262 (Rock Mechanics Laboratory): Batch- 2010, 2011, 2012, 2013  
            + PME 311 (Reservoir Engineering): Batch- 2011, 2012 
            + PME 313 (Well Logging and Formation Evaluation): Batch- 2011
            + PME 314 (Well Logging Laboratory): Batch- 2011
            + PME 315 (Drilling Engineering): Batch- 2012
            + PME 321 (Petroleum Production Engineering): Batch- 2014
            + PME 323 (Natural Gas Engineering): Batch- 2010 
            + PME 324 (Natural Gas Engineering Laboratory): Batch- 2010
            + PME 334 (Drilling Fluids Laboratory): Batch- 2012
            + PME 352 (Computational Laboratory): Batch- 2010, 2011 
            + PME 415 (Reservoir Modeling & Simulation): Batch- 2011
            + PME 416 (Reservoir Modeling & Simulation Laboratory): Batch- 2011
          icon: 
          organization: Faculty Member, Petroleum and Mining Engineering
          organization_url: 
          title: 'Chittagong University of Engineering & Technology'
          url: https://www.cuet.ac.bd
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
     # text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: tzaman@mun.ca
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: ''
        city: St. John's
        region: NL
        postcode: ''
        country: Canada
        country_code: ''
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '47.5741'
        longitude: '-52.7354' 
     # contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
