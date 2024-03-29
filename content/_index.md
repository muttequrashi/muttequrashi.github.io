---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Wowchemy demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://wowchemy.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Wowchemy - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

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
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
    id: exper
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
     
      items:
        - title: Robotics & Control Engineer Thesis Intern
          company: ImViA
          company_url: 'https://imvia.u-bourgogne.fr/'
          company_logo: 
          location: Le Creusot, France
          date_start: '2023-01-01'
          date_end: '2023-06-30'
          description: |2-
            • Developed robust non‑linear control for quadcopters and wheeled robots, enabling precise tracking, disturbance resilience, and computer vision integration for real‑time autonomy.
            • Tested on AR Drone 2.0, DJI Tello Drone, and TurtleBot3.
      
       # - title: Robotics and Computer Vision Engineer
        # company_url: ''
         # company_logo: ''
          #location: 'Remote'
          #date_start: '2021-07-01'
          #date_end: '2023-08-31'
          #description: |2-
           # • Developed and deployed computer vision systems using OpenCV, Python, and other tools to solve real‑world problems in various industries.
        
        - title: Robotics & Control Engineer Intern
          company: Z‑PARADISE SAS
          company_url: ''
          company_logo: ''
          location: Staffelfelden, France
          date_start: '2022-06-01'
          date_end: '2022-09-30'
          description: |2-
            • Pool Quality Sensor: Designed PCB and programmed the swimming pool filtration management system using various components (ESP32, sensors, & solar power) and implemented Z‑wave protocol.

        - title: Robotic Software Engineer
          company: Sky High Escape Rooms
          company_url: ''
          company_logo: ''
          location: Remote
          date_start: '2020-08-01'
          date_end: '2020-10-31'
          description: |2-
            • Node‑RED escape room program for Raspberry Pi with multiple user inputs, camera feeds, and HDMI/audio output, designed with a specific sequencing algorithm.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.kaggle.com/learn/certification/mutteurrehman/python
          date_end: ''
          date_start: '2023-02-25'
          description: ''
          organization: Kaggle
          organization_url: https://www.kaggle.com
          title: Python
          url: ''


        - certificate_url: https://app.theconstructsim.com/accomplishments/verify/RIA4DE0911ABB7D/
          date_end: ''
          date_start: '2022-12-24'
          description: 
          organization: The Construct
          organization_url: https://www.theconstructsim.com
          title: Code Foundation for ROS
          url: https://app.theconstructsim.com/learning-paths/code-foundation-for-ros/


        - certificate_url: https://courses.edx.org/certificates/a586a82803f444ffa6fed29dc4239415
          date_end: ''
          date_start: '2021-04-01'
          description: ''
          organization: edx
          organization_url: https://www.edx.org
          title: 'Technology Entrepreneurship: Lab to Market'
          url: ''


        - certificate_url: https://www.linkedin.com/learning/certificates/0909b94f3357aeac061b6703b26de8b308a8007fbbf90ad4bf5439607189508a
          date_end: ''
          date_start: '2022-10-01'
          description: ''
          organization: LinkedIn
          organization_url: https://www.linkedin.com
          title: 'Machine Learning with Python: Foundations'
          url: ''

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
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: experience
    id: achievements 
    content:
      title: Achievements
      date_format: Jan 2006
      items:
        - title: Vice Chancellor’s Recognition Award
          company: Air University
          company_url: 'https://www.au.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2019-03-01'
          date_end: ''
          description: Vice Chancellor’s Recognition Award among 1500 students.
        
        - title: 1st Position at Robo‑rumble Competition
          company: SOFTEC 2019 – Fast University (NUCES)
          company_url: 'https://www.nu.edu.pk/'
          company_logo:
          location: Lahore, PK
          date_start: '2019-01-01'
          date_end: ''
          description: Achieved 1st Position at Robo‑rumble Competition.
        
        - title: 1st Position at Robowars Competition
          company: AirTech’19 – Air University
          company_url: 'https://www.au.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2019-12-01'
          date_end: ''
          description: Achieved 1st Position at Robowars Competition.
        
        - title: Winners at Airtech 2018
          company: Air University
          company_url: 'https://www.au.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2018-12-01'
          date_end: ''
          description: Achieved 1st Position at Robo wars competition.
        
        - title: Runners up at NERC 2018
          company: EME Islamabad
          company_url: 'https://ceme.nust.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2018-11-01'
          date_end: ''
          description: 2nd position at Robo wars competition organized.
        
        - title: Winner at Olympiad Hitec 2017
          company: Hitec University
          company_url: 'https://www.hitecuni.edu.pk/'
          company_logo:
          location: Taxila, PK
          date_start: '2017-05-01'
          date_end: ''
          description: 1st position in Sumo Robowar competition.
        


        - title: Winners at IYC 2017
          company: IST Islamabad
          company_url: 'https://www.ist.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2017-02-01'
          date_end: ''
          description: 1st position at Aero modeling competition.
        
        - title: Runners up at IYC 2017
          company: IST Islamabad
          company_url: 'https://www.ist.edu.pk/'
          company_logo:
          location: Islamabad, PK
          date_start: '2017-02-01'
          date_end: ''
          description: 2nd position at Air Crash Inquiries competition.
    design:
      columns: '2'
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-       
        <div style="text-align:right; background-color: transparent; padding:10px;">
        <img src="uploads/ban_new.gif" alt="GIF" >
        </div>


    design:
      columns: '1'
      
  
  - block: contact
    id: contact
    content:
      title: Contact
    
      # Contact (add or remove contact options as necessary)
      email: muttequreshi@gmail.com
      phone: +33 07 83 85 3998
      appointment_url: 'https://calendly.com/muttequreshi'
      address:
        city: Le Creusot
        postcode: '71200'
        country: France
        country_code: FR
    design:
      columns: '2'


---

