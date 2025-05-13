---
type: PageLayout
title: Home
colors: colors-a
sections:
  - elementId: ''
    colors: colors-e
    backgroundSize: full
    title: I am a Senior HR Specialist/ Talent Acquisition manager
    subtitle: >-
      With over three years of experience in technical recruitment, I have
      successfully sourced, assessed, and placed top-tier talent across a range
      of in-demand roles — including software engineers, data scientists, cloud
      architects, and cybersecurity analysts. My approach blends deep industry
      understanding with a people-first mindset, allowing me to match the right
      talent with the right opportunities at the right time.What sets me apart
      is my diverse professional background:

      A five-year career in accounting and tax advisory, giving me a sharp eye
      for detail and a strong foundation in financial compliance and analytics.


      Four years as a freelance digital marketer, specializing in SEO, content
      strategy, and online branding, which honed my ability to position
      opportunities and candidates in compelling, high-impact ways.

      At CodingMountain, I leverage this unique mix of IT, finance, and
      marketing acumen to build tailored sourcing strategies, engage niche
      talent, and deliver hiring outcomes that align with business growth.More
      than just filling roles, I’m passionate about building careers — creating
      connections that are meaningful, lasting, and growth-oriented.
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: center
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/420111651_7544901958888239_8344759250389245153_n.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - colors: colors-e
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        textAlign: left
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
socialImage: '/images/ChatGPT Image Apr 24, 2025, 01_24_39 PM.png'
---
