---
title: Home
slug: /
sections:
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
      - content/pages/blog/case-study-3.md
      - content/pages/blog/case-study-3.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: false
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-5
          - pl-0
          - pb-10
          - pr-0
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up

    actions:
      - label: More blogs
        url: /blog
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
        showIcon: true

  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
    type: DividerSection

  - type: GenericSection
    title:
      text: 312 Marketing
      color: text-primary
      type: TitleBlock
    subtitle: A Real Estate Company
    text: >
      If you are willing to buy or sell any type of property whether it be residential or commercial, then you have come to the right place. We will guide you in making the right monetary decisions depending on your budget and priorities. Our <b>[agents](/#agents)</b> have vast amount of expertise in property management. You can expect utter professionalism, trust and fast response timing while communicating with them. Get a free consultation right now by contacting any of our agents!

    media:
      url: /images/logo.jpg
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16

  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
    type: DividerSection

  - type: FeaturedItemsSection
    title:
      text: Why Choose Us
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Our Services

    items:
      - type: FeaturedItem
        title: Real Estate Consultancy
        text: >-
          We provide our local and overseas customers help in making correct investment decisions and support in acquisition and disposal of properties. Our team provides end to end services such as transfers, registry and any legal requirements involved in transaction to our clients.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Sales and Marketing
        text: >-
          We provide promotions, marketing and sales services of all kind of projects based all across Pakistan to our clients using our significant presence on social media platforms such as Youtube, Facebook, Instagram, Twitter and Linkedin.

        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Property Management
        text: >-
          We provide complete management of properties of our clients. The management includes collection of rentals, installments, upkeep, management of tenants, repair and maintenance of properties.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem

      - title: Construction Services
        text: >-
          We have experienced construction specialists and architects which deliver our customers most cost effective solutions for residential and commercial buildings.
        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    elementId: ''
    variant: two-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center

  - title:
    image:
      url: /images/bossman.png
      type: ImageBlock
      elementId: bossman
    type: FeaturedItem
    justifyContent: center

  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
    type: DividerSection

  - tilte:
    text: >
      <a name="agents">
    type: FeaturedItem

  - title:
      text: Meet the Agents
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock

    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection

  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
    type: DividerSection

  - subtitle: Projects We Deal
    images:
      - url: /images/companies/bahria-karachi.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/bahria-edu.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/bahria-town.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/park-avenue.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/bahria-orchard.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/al-noor-orchard.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/dha-lahore.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/etihad-town.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/new-lahore-city.png
        type: ImageBlock
        elementId: budiness

      - url: /images/companies/park-view-city.png
        type: ImageBlock
        elementId: budiness
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
      subtitle:
        textAlign: center
    type: ImageGallerySection

  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
    type: DividerSection

  - title:
    text: <a name="aboutus">
    type: FeaturedItem

  - title:
      text: About Us
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    text: |-
      312 Marketing Company is a premier real estate firm dedicated to offering comprehensive solutions for those looking to buy or sell properties. Our team, comprised of experienced professionals with deep industry knowledge, is committed to assisting clients in making informed investment decisions that align with their budget. We focus on delivering exceptional value, rapid response times, and professional service at all stages of the process. Recognizing the complexities involved in real estate transactions, we provide expert advice and guidance, underpinned by detailed market analysis and our team's extensive experience.
     
       Our investment advice is grounded in a deep understanding of the real estate market, enabling us to offer clients the best possible guidance. Our commitment to excellence is evident in our large and satisfied client base, whose success stories are a testament to the value we deliver. 312 Marketing Company serves as a comprehensive resource for all your real estate needs, and we are dedicated to turning your aspirations into reality. If you're considering buying or selling a property, reach out to us for a complimentary consultation. Let us assist you in making the right investment choices and take the first step towards achieving your real estate goals.

    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection

  - title:
    text: <a name="contactus">
    type: FeaturedItem

  - title:
      text: Contact Us
      color: text-primary
      type: TitleBlock
    text: |-
      Please fill the given form and click on the submit button to reach out to us. We will try to reach back to you as soon as possible.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: phone
          label: Phone
          hideLabel: true
          placeholder: Your phone number (optional)
          isRequired: false
          width: full
          type: TextFormControl
        - name: subject
          label: Subject
          hideLabel: true
          placeholder: Subject of email
          isRequired: true
          width: full
          type: TextFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    colors: bg-light-fg-dark
    type: GenericSection


  - title:
    text: <iframe id="location" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d54508.42654907027!2d74.13979589856318!3d31.365141806992753!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3918ff9a30fa362d%3A0x528615a7981ce611!2sBahria%20Town%2C%20Lahore%2C%20Punjab%2C%20Pakistan!5e0!3m2!1sen!2s!4v1724313791063!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    type: FeaturedItem

seo:
  metaTitle: Home
  metaDescription: This is the homepage.
  socialImage: /images/logo.jpg
  type: Seo
type: PageLayout
---
