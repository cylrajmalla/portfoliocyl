---
type: PageLayout
title: Home
colors: colors-a
sections:
  - elementId: ''
    colors: colors-e
    backgroundSize: full
    title: I am a Talent Acquisition manager/ Senior Human resources Specialist
    subtitle: >-
      With over five years of experience in technical recruitment, I have
      successfully sourced, assessed, and placed top-tier talent across a range
      of in-demand roles including software engineers, data scientists, cloud
      architects, and cybersecurity analysts. My approach blends deep industry
      understanding with a people-first mindset, allowing me to match the right
      talent with the right opportunities at the right time. What sets me apart
      is my diverse professional background: A five-year career in accounting
      and tax advisory, giving me a sharp eye for detail and a strong foundation
      in financial compliance and analytics. Four years as a freelance digital
      marketer, specializing in SEO, content strategy, and online branding,
      which honed my ability to position opportunities and candidates in
      compelling, high-impact ways. At CodingMountain, I leverage this unique
      mix of IT, Recruitment, and Brand Marketing acumen to build tailored
      sourcing strategies, engage niche talent, and deliver hiring outcomes that
      align with business growth. More than just filling roles, I’m passionate
      about building careers  creating connections that are meaningful, lasting,
      and growth-oriented.
    styles:
      self:
        height: auto
        width: full
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
        flexDirection: col
        textAlign: center
        borderRadius: none
        borderWidth: 0
        borderStyle: dashed
        borderColor: border-(--theme-dark)
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/420111651_7544901958888239_8344759250389245153_n.jpg
      altText: altText of the image
      caption: Sahil Raj Malla
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
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: false
          placeholder: Your name
          width: 1/2
          isRequired: true
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: false
          placeholder: Type your message here
          width: full
          isRequired: false
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
          isRequired: false
      submitLabel: Send Message
      elementId: 'https://forms.gle/zv8WzVyKj8pcycVx6'
      styles:
        self:
          textAlign: left
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
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
addTitleSuffix: true
---
