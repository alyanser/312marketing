---
title: Islamabad
slug: /blog/islamabad

featuredImage:
  url: /images/islamabad.jpg
  elementId: thumbnail
  styles:
    self:
      borderRadius: x-large
  type: ImageBlock

styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: center
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col

sections:

  - title:
      text: Islamabad Blogs
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    styles:
      self:
        flexDirection: col
        justifyContent: center
    type: GenericSection

  - posts:
      - content/pages/blog/lahore/bahria-orchard.md

    showThumbnail: true
    showDate: true
    showAuthor: false
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-5
          - pb-10
          - pr-5
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up

seo:
  metaTitle: Home
  metaDescription: This is the homepage.
  socialImage: /images/logo.jpg
  type: Seo
type: PageLayout
---
