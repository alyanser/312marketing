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
      - content/pages/blog/commercial/commercial.md

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

  - title:
    text: <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"> <a href="https://wa.me/923214444140" class="right-float" target="_blank"> <i class="fa fa-whatsapp my-float"></i> </a>
    type: FeaturedItem

  - title:
    text: <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css"> <a href="/#contactus" class="left-float"> <i class="fa fa-solid fa-envelope my-float"></i> </a>
    type: FeaturedItem


seo:
  metaTitle: Home
  metaDescription: This is the homepage.
  socialImage: /images/logo.jpg
  type: Seo
type: PageLayout

---
