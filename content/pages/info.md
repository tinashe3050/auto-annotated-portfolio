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
    text: "As a stay-at-home dad web builder, you have unique advantages to offer small business owners and personal brands. Here's how to position yourself effectively:\n\n## Website & Positioning Essentials\n\n1.  **Specialized Homepage Messaging**:\n\n    *   \"Affordable Websites for Busy Small Business Owners - Built by a Dad Who Understands Budgets & Schedules\"\n\n    *   Highlight your availability during business hours when competitors may be unavailable\n\n2.  **Service Packages**:\n\n    *   Starter package (basic 5-page site) -\_500−500−800\n\n    *   E-commerce ready package -\_1,200−1,200−1,800\n\n    *   Monthly maintenance retainer option\n\n3.  **Unique Value Propositions**:\n\n    *   \"Dad-tested business solutions\" (play on your family experience)\n\n    *   \"Websites built during naptime - savings passed to you\"\n\n    *   \"No corporate overhead means lower prices for you\"\n\n\n\n\n\n"
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
        textAlign: left
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: >-
      PacketStream: Sells your unused bandwidth to businesses for tasks like web
      scraping, paying you based on data usage.Honeygain: Shares your idle
      internet bandwidth with companies for market research, earning you passive
      income.Repocket/Peer2Profit/PawnsApp: Similar platforms that monetize your
      unused bandwidth or IP address, paying you in cash or crypto.
    images:
      - type: ImageBlock
        url: /images/Snapshot_250501163057.png
        altText: honeygain
        caption: Logo one
      - type: ImageBlock
        url: /images/Snapshot_250501163717.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/Snapshot_250501164147.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/Snapshot_250501164902.png
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/Snapshot_250501165754.png
        altText: Logo five
        caption: Logo five
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
    title: SIDE HUSTLES
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    subtitle: >-
      You can find me here: and if you would like to try these side hustles all
      links are under linktree
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Whatsapp
            url: 'https://wa.me/message/QHRWGT3LKGMXG1'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: x
            url: 'https://x.com/BhUnUHTMlemons'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: www.linkedin.com/in/bhunu-htmlemons-904776363
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: CodePen
            url: 'https://codepen.io/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Telegram
            url: 'https://discord.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      bhunuhtmlemons\@gmail.com
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
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
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
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
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
