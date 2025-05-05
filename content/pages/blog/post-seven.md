---
type: PostLayout
title: funny yet truthful take on the 5 Habits of Highly Productive Web Developers⌨️
colors: colors-a
date: '2024-06-10'
author: content/data/team/doris-soto.json
excerpt: More context that may or may not be helpful
featuredImage:
  type: ImageBlock
  url: /images/featured-Image1.jpg
  altText: Post thumbnail image
backgroundImage:
  type: BackgroundImage
  url: /images/gallery-3.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 20
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
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
media:
  type: ImageBlock
  url: /images/image_fx (1).jpg
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
---

**🤓 1. "I’ll Fix It Later" (Spoiler: Never Do)**

*   Write messy code with a **"temporary" hack** that becomes permanent.

*   Leave `TODO:` comments like a time capsule for future you.

*   **Actual Productivity Hack:** Use Prettier so your code *looks* clean, even if it’s chaos.

### **☕ 2. Coffee > Sleep**

*   Debug at 2 AM because "the code was *just* working!"

*   Measure productivity in **cups of coffee** instead of hours.

*   **Actual Productivity Hack:** Hydrate (with water… sometimes).

### **🦸 3. "I Don’t Need Docs" (Immediately Googles It)**

*   Spend 4 hours debugging instead of reading the docs for 5 minutes.

*   **Stack Overflow > College Degree.**

*   **Actual Productivity Hack:** Bookmark the docs (and pretend you’ll read them).

### **🐒 4. "It Works on My Machine!"**

*   Blame **"weird dependencies"** when it breaks in production.

*   Secretly hope the client doesn’t test on Internet Explorer.

*   **Actual Productivity Hack:** Use Docker so everyone suffers equally.

### **🚀 5. "I’m Just Checking One Thing" (3 Hours Later…)**

*   Open DevTools for "a quick fix" and fall into a **black hole of CSS tweaks**.

*   Accidentally refactor the entire project at 3 AM.

*   **Actual Productivity Hack:** Set a timer (and ignore it).



### **🎤 Bonus Habit: "I’ll Start Tomorrow’s Work Early" (Opens Netflix)**

*   "Researching design inspiration" = scrolling memes.

*   **Actual Productivity Hack:** Block social media (…after *one* more meme).




