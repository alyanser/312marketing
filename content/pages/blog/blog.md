---
title: Blog
slug: /blog
numOfPostsPerPage: 12
enableSearch: false

sections:

  - title:
      text: Blogs
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
      - content/pages/blog/lahore/lahore.md
      - content/pages/blog/islamabad/islamabad.md

    showThumbnail: true
    showDate: false
    showAuthor: false
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
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
