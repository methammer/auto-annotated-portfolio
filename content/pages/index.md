---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      I’m a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: >-
      This is my info—I’m sharing it all this with ya’ll to impress you with all
      the hard work I’ve done in the past few years. Once you’re impressed, you
      can continue to scroll down to see more details and credentials about me.
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
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: FeaturedItemsSection
    title: Value propositions
    items:
      - type: FeaturedItem
        title: I'm Fast
        subtitle: ''
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: 50$
            altText: 50$
            url: /
            showIcon: true
            icon: cart
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: I'm Smart
        subtitle: ''
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: I'm Focused
        subtitle: ''
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        featuredImage:
          type: ImageBlock
          url: >-
            https://assets.stackbit.com/components/images/default/default-image.png
          altText: Item image
          caption: Caption of the image
          elementId: ''
        actions:
          - type: Button
            label: ''
            altText: ''
            url: /
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 2
    spacingX: 16
    spacingY: 16
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: ContactSection
    title: Contact Me
    text: I'm look forward to hearing from you.
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
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: false
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextFormControl
          name: Adresse
          label: Adresse
          hideLabel: false
          placeholder: Votre adresse...
          width: full
          isRequired: false
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    media:
      type: ImageBlock
      url: /images/contact.jpg
      altText: Contact form image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
