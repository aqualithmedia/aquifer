---
blocks:
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: 'pt-48 pb-48 pr-10 pl-10 sm:pt-64 sm:pb-28 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: 'w-2/3 min-h-0 text-right sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-wrap  '
      labelStyles: 'text-white mg-headline-small '
      headlineStyles: 'text-white mg-headline-large '
      subheadStyles: 'text-white mg-copy-large '
      textStyles: 'text-white mg-copy '
    background:
      fillStyles: bg-accent1 opacity-100
      wrapFillStyles: ' opacity-100'
      src: /uploads/stock/touching-the-wall.jpg
      style: bg-repeat
      position: bg-top
      ornaments:
        - src: /uploads/brand/aqualith-logo-tran-500.png
          alignment: left
          width: '400'
          height: '400'
          xOffset: ''
          yOffset: '175'
    label: STORY
    headline: Setting the water table
    subhead: ''
    body: ''
    buttons:
      - label: Explore
        link: '#'
        icon: ''
        buttonStyle: primary
        fathomId: ''
    _template: feature
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: pt-20 pb-20 pr-0 pl-0
      featureImage: '  mx-auto'
      featureContent: w-3/5 min-h-0 text-center
      buttonsLayout: 'flex-row  '
      labelStyles: text-black mg-hidden undefined
      headlineStyles: 'text-primary mg-headline-large '
      subheadStyles: text-primary undefined undefined
      textStyles: text-accent2 undefined undefined
    background:
      style: bg-cover
      position: bg-center
    headline: Telling stories through compelling design.
    subhead: Including yours.
    body: |
      Now open for contract and freelance.
    buttons:
      - label: Let's chat
        link: /contact
        icon: arrow-right-solid
        buttonStyle: primary
    _template: feature
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: pt-0 pb-0 pr-0 pl-0
      featureContent: w-full min-h-0 text-center
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-hidden undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white undefined undefined
    cardStyle:
      fillStyles: bg-black opacity-100
      grid: >-
        grid-cols-3 justify-start gap-0.5 sm:grid-cols-1 sm:justify-start
        sm:gap-0.5
      alignment: flex-col items-start  text-left
      image: wpx-48 hpx-48 object-left object-fill
      imagePadding: 'pt-20 pb-0 pr-0 pl-10 sm:pt-10 sm:pb-0 sm:pr-0 sm:pl-5'
      contentPadding: 'pt-5 pb-12 pr-11 pl-11 sm:pt-5 sm:pb-2.5 sm:pr-5 sm:pl-5'
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-small undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonType: primary
      buttonIcon: arrow-right-solid
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: bg-black opacity-100
      wrapFillStyles: bg-black opacity-100
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: Features
    subhead: ''
    body: ''
    items:
      - image:
          src: /uploads/bring-forward.svg
        headline: Consultancy
        subhead: Leave that centralization behind.
        body: >
          Future-proofed value in the form of design solutions that ensure your
          project truly stands out.
        link: '#'
        buttonLabel: Deploy your stuff
      - image:
          src: /uploads/brush.svg
        headline: Products
        subhead: Imprinting imagination.
        body: >
          Publishing tabletop roleplaying game products designed to drop right
          into your favorite systems.
        link: '#'
        buttonLabel: Roll for initiative
      - image:
          src: /uploads/image-polaroid.svg
        headline: Media
        subhead: Sights and sounds.
        body: >
          Documenting nerdery and creative forms of engagement through podcasts,
          blogs, and the social web.
        link: '#'
        buttonLabel: Value for value
    navigationLabel: features
    _template: cards
  - style:
      fullWidth: false
      minHeight: min-h-0
      padding: pt-20 pb-20 pr-10 pl-10
      labelStyles: 'text-white undefined '
      headlineStyles: text-primary undefined undefined
      subheadStyles: text-primary undefined mb-4
      textStyles: text-accent2 mg-copy undefined
    background:
      fillStyles: from-accent4 to-black bg-gradient-to-r opacity-100
      wrapFillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
    navigationLabel: Timeline
    _template: eventTimeline
  - style:
      alignment: >-
        flex-col-reverse items-center gap-6 sm:flex-col-reverse sm:items-center
        sm:gap-12
      padding: 'pt-20 pb-20 pr-14 pl-14 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureContent: 'w-2/3 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
    cardStyle:
      fillStyles: ' opacity-100'
      grid: >-
        grid-cols-4 justify-start gap-12 sm:grid-cols-2 sm:justify-start
        sm:gap-4
      alignment: flex-col items-start  text-left
      image: wpx-48 hpx-48 object-center object-fill
      imagePadding: pt-0 pb-0 pr-0 pl-0
      contentPadding: pt-5 pb-0 pr-0 pl-0
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-medium undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: 'Built on a foundation of fast, production-grade tooling'
    subhead: ''
    body: ''
    items:
      - image:
          src: /uploads/react.svg
        headline: React
        subhead: ''
        body: >
          A free and open-source front-end JavaScript library for building user
          interfaces based on components.
      - image:
          src: /uploads/next-js.svg
          alt: Next JS
        headline: Next JS
        subhead: ''
        body: >
          Create full-stack Web applications by extending the latest React
          features and JavaScript tooling.
      - image:
          src: /uploads/tailwind.svg
          alt: Tailwind
        headline: Tailwind
        subhead: ''
        body: >
          A utility-first CSS framework that can be used to build any design,
          directly in your markup.
      - image:
          src: /uploads/tina.svg
        headline: Tina CMS
        body: |
          Tina is an open-source, headless CMS for Markdown, MDX, and JSON.
    navigationLabel: tooling
    _template: cards
  - style:
      alignment: >-
        flex-col-reverse items-center gap-6 sm:flex-col-reverse sm:items-center
        sm:gap-12
      padding: 'pt-20 pb-20 pr-14 pl-14 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureContent: 'w-2/3 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white undefined undefined
    cardStyle:
      fillStyles: ' opacity-100'
      grid: >-
        grid-cols-4 justify-start gap-12 sm:grid-cols-2 sm:justify-start
        sm:gap-6
      alignment: flex-col items-start  text-left
      image: wpx-36 hpx-36 object-center object-fill
      imagePadding: pt-0 pb-0 pr-0 pl-0
      contentPadding: pt-5 pb-0 pr-0 pl-0
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-medium undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: Components
    subhead: (keep until done with above)
    body: ''
    items:
      - image:
          src: /uploads/star.svg
        headline: Feature
        subhead: ''
        body: >
          Copy next to an image, or above an image. Or below it - you get the
          point. The core component of all websites.
      - image:
          src: /uploads/bring-forward.svg
        headline: Cards
        subhead: ''
        body: >
          A grid of cards. Each one with an image and text - a whole family of
          baby features. Incredibly customizable.
      - image:
          src: /uploads/distribute-spacing-vertical.svg
        headline: Accordion
        body: >
          A list of collapsible headline/text sets. Use them for FAQs,
          directions or list your bands favorite foods.
      - image:
          src: /uploads/video.svg
        headline: Embed
        body: >
          An open ended component for your own HTML with Tailwind styles. Forms,
          videos or anything else you can imagine.
      - image:
          src: /uploads/calendar.svg
        headline: Schedule
        body: >
          A full featured event calendar generated from event posts. Location
          details, time slots, categories and more.
      - image:
          src: /uploads/timeline.svg
        headline: Timeline
        subhead: ''
        body: >
          This is a simplified way of sharing event posts. An easy to read
          overview of the day or month's schedule.
    navigationLabel: components
    _template: cards
  - style:
      alignment: 'flex-row-reverse items-center gap-12 sm:flex-col sm:items-center sm:'
      padding: 'pt-32 pb-32 pr-14 pl-14 sm:pt-0 sm:pb-10 sm:pr-5 sm:pl-5'
      featureImage: '  mr-auto   sm:mx-auto'
      featureContent: 'w-3/5 min-h-0 text-left sm:w-full sm:min-h-0 sm:text-left'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    image:
      src: /uploads/collections.mp4
    headline: Collections
    subhead: ''
    body: >
      Go beyond pages and add data as events or posts. Events can be displayed
      in a feature rich schedule component, timeline or as cards. Create any
      other data collection you like to manage team members, products or
      anything else you can imagine. The data structure of these collections is
      completely up to you.
    navigationLabel: collections
    _template: feature
  - style:
      alignment: 'flex-row-reverse items-center  sm:flex-col sm:items-center sm:'
      padding: 'pt-32 pb-32 pr-14 pl-14 sm:pt-10 sm:pb-14 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: w-full min-h-0 text-left
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    headline: Get Started
    subhead: ''
    body: |
      1. Clone the project repo and upload it to your choice of static host
      2. Create a **[Free Tina CMS account](https://tina.io/ "Tina CMS")**
      3. Start stacking up components to create your pages
    buttons:
      - label: Documentation
        link: 'https://github.com/MicrogenSite/microgen'
        buttonStyle: primary
    navigationLabel: ''
    _template: feature
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: 'pt-20 pb-20 pr-5 pl-5 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: 'w-3/4 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large mb-10
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    headline: Credits
    subhead: ''
    body: >
      ![](/uploads/bustout-protocol-partners.svg)


      Microgen was built by **[Bust Out](https://bustout.com "Bust Out")** for
      **[Protocol Labs](https://protocol.ai "Protocol Labs")** and designed to
      run on **[IPFS](https://ipfs.tech/ "IPFS")**. It’s based on the excellent
      and open source **[Tina CMS](https://tina.io "Tina CMS")**.
    _template: feature
backgroundColor: white
meta:
  title: Microgen
  description: ''
background:
  fillStyles: bg-black opacity-100
  src: ''
  style: bg-cover
  position: bg-left
---






















