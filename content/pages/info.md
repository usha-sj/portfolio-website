---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >-
      ## Hello World! I'm Usha. 
      
      I'm pursuing a double major in Computer Science and Economics at the University of Toronto, driven by a passion for blending data, design, AI, and finance to create intelligent solutions with beautiful interfaces. 
      
      Most of all, I love trying new things and continuously learning!

      I’m eager to explore opportunities where I can apply my skills in data science, machine learning, UX/UI design, and finance to solve real-world problems. Let’s connect and create something impactful!
    media:
      type: ImageBlock
      url: /images/about.png
      altText: A photo of me!
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  # - type: DividerSection
  #   styles:
  #     self:
  #       width: wide
  #       padding:
  #         - pt-8
  #         - pb-8
  #         - pl-4
  #         - pr-4
  #       justifyContent: center
  #       borderWidth: 1
  #       borderStyle: solid
  # - type: MediaGallerySection
  #   colors: colors-f
  #   subtitle: 'I worked with these folks:'
  #   images:
  #     - type: ImageBlock
  #       url: /images/logo1.svg
  #       altText: Logo one
  #       caption: Logo one
  #     - type: ImageBlock
  #       url: /images/logo2.svg
  #       altText: Logo two
  #       caption: Logo two
  #     - type: ImageBlock
  #       url: /images/logo3.svg
  #       altText: Logo three
  #       caption: Logo three
  #     - type: ImageBlock
  #       url: /images/logo4.svg
  #       altText: Logo four
  #       caption: Logo four
  #     - type: ImageBlock
  #       url: /images/logo5.svg
  #       altText: Logo five
  #       caption: Logo five
  #   spacing: 3
  #   columns: 5
  #   aspectRatio: auto
  #   showCaption: false
  #   enableHover: false
  #   styles:
  #     self:
  #       width: wide
  #       height: auto
  #       padding:
  #         - pt-8
  #         - pb-8
  #         - pl-4
  #         - pr-4
  #       justifyContent: center
  #       borderRadius: none
  #       borderWidth: 0
  #       borderStyle: none
  #       borderColor: border-dark
  #     title:
  #       textAlign: left
  #     subtitle:
  #       textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/usha-sj'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/ushasj/'
        styles:
          self:
            textAlign: left
      # - type: FeaturedItem
      #   actions:
      #     - type: Link
      #       label: Instagram
      #       url: 'https://www.instagram.com/'
      #   styles:
      #     self:
      #       textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: Python (NumPy, Pandas, Matplotlib, Beautiful Soup)
      - type: Label
        label: Java
      - type: Label
        label: C
      - type: Label
        label: JavaScript (React, Next.js, Web3.js, )
      - type: Label
        label: HTML/CSS
      - type: Label
        label: AWS
      - type: Label
        label: SQL
      - type: Label
        label: R
      - type: Label
        label: Microsoft Excel
      - type: Label
        label: Figma
      - type: Label
        label: Git
      - type: Label
        label: Jira

  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [ushashasj@gmail.com](mailto:ushashasj@gmail.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * Research Assistant (Software Development) @ Munk School of Global Affairs and Public Policy.

          **07/2023 - 12/2023**

          * Software Development Engineering Intern @ Kumandra by KOOMPI

          **06/2023 - 08/2023**

          * Research Assistant (Data Analytics) @ Institute of the Study of University Pedagogy

          **2021 - 2022**

          * Digital Marketing Officer @ KOOMPI

          **2020 - 2021**

          * Business & Partnerships Intern @ smallworld venture
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Extracurriculars:'
        text: |-
          **Current**

          * Co-President @ Google Student Developers Club (GDSC) UTM

          **Current**

          * VP Finance @ UTM Robotics

          **2023 - 2024**

          * Finance Lead @ Google Student Developers Club (GDSC) UTM

          **2023 - 2024**

          * VP Marketing @ UTM Robotics

          **2023 - 2024**

          * VP Finance @ UNICEF UTM
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2022 - 2026**

          * BSc in Computer Science and Economics with a Mathematics Minor @ the University of Toronto (Mississauga)

          **2019 - 2022**

          * International Baccalaureate Diploma Programme (40/45) @ Alcanta International College
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  # - type: DividerSection
  #   styles:
  #     self:
  #       width: wide
  #       padding:
  #         - pt-12
  #         - pb-12
  #         - pl-4
  #         - pr-4
  #       justifyContent: center
  #       borderWidth: 1
  #       borderStyle: solid
  # - type: ContactSection
  #   backgroundSize: full
  #   title: "Let’s talk... \U0001F4AC"
  #   colors: colors-f
  #   form:
  #     type: FormBlock
  #     elementId: sign-up-form
  #     fields:
  #       - name: firstName
  #         label: First Name
  #         hideLabel: true
  #         placeholder: First Name
  #         isRequired: true
  #         width: 1/2
  #         type: TextFormControl
  #       - name: lastName
  #         label: Last Name
  #         hideLabel: true
  #         placeholder: Last Name
  #         isRequired: false
  #         width: 1/2
  #         type: TextFormControl
  #       - name: email
  #         label: Email
  #         hideLabel: true
  #         placeholder: Email
  #         isRequired: true
  #         width: full
  #         type: EmailFormControl
  #       - name: message
  #         label: Message
  #         hideLabel: true
  #         placeholder: Tell me about your project
  #         isRequired: true
  #         width: full
  #         type: TextareaFormControl
  #       - name: updatesConsent
  #         label: Sign me up to recieve my words
  #         isRequired: false
  #         width: full
  #         type: CheckboxFormControl
  #     submitLabel: "Submit \U0001F680"
  #     styles:
  #       submitLabel:
  #         textAlign: center
  #   styles:
  #     self:
  #       height: auto
  #       width: narrow
  #       margin:
  #         - mt-0
  #         - mb-0
  #         - ml-4
  #         - mr-4
  #       padding:
  #         - pt-12
  #         - pb-12
  #         - pr-4
  #         - pl-4
  #       alignItems: center
  #       justifyContent: center
  #       flexDirection: row
  #     title:
  #       textAlign: left
  #     text:
  #       textAlign: left
---
