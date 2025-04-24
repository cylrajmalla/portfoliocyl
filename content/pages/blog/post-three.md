---
type: PostLayout
title: Composable - the future of web
colors: colors-b
date: '2024-01-01'
author: content/data/team/doris-soto.json
excerpt: Published
featuredImage:
  type: ImageBlock
  url: /images/featured-Image3.jpg
  altText: Post thumbnail image
backgroundImage:
  type: BackgroundImage
  url: /images/gallery-2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 10
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        textAlign: left
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: Stay up-to-date with my words ✍️
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
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
        width: wide
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---


## What is Composable Web?
Composable Web is an approach where websites/apps are built by assembling independent, reusable components (APIs, microservices, UI elements). Instead of tightly coupled code, you plug-and-play best-in-class solutions.

### Syntax highlighter in Next.js

```css
.colors-a {
  @apply bg-dark text-on-dark;
  .sb-input,
  .sb-select,
  .sb-textarea {
    @apply text-on-dark placeholder-on-dark placeholder-opacity-75;
  }
  .sb-header-links-primary .sb-component-link:before,
  .sb-component-header .sb-component-social:before {
    @apply bg-on-dark;
  }
  .sb-header-links-primary .sb-component-link:hover,
  .sb-component-header .sb-component-social:hover {
    @apply text-dark;
  }
  .sb-header-overlay {
    @apply bg-dark;
  }
}
```

Why It Matters

    Speed: Launch faster by integrating pre-built services (e.g., Stripe for payments, Auth0 for login).

    Flexibility: Swap components without rewriting entire systems (e.g., migrating CMS from WordPress to Headless Contentful).

    Scalability: Scale only what you need (e.g., just your database or frontend).

Key Pillars of Composable Web

    Headless Architectures

        Decouple frontend (React/Next.js) from backend (Node.js/APIs).

        Example: Shopify’s headless commerce + custom React storefront.

    API-First Design

        Build services as reusable APIs (REST, GraphQL, or gRPC).

        Example: Using Twilio’s API for SMS instead of in-house code.

    Microservices & Serverless

        Deploy small, single-purpose functions (AWS Lambda, Vercel Edge).

        Example: Image resizing via Cloudflare Workers.

    Jamstack (JavaScript + APIs + Markup)

        Pre-rendered pages + dynamic APIs = blazing-fast sites.

        Tools: Next.js, Netlify, Sanity.io.

    Low-Code/No-Code Integration

        Glue services together with platforms like Zapier or Retool.
