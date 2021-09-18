# Learning - September 2021 - Website Accessibility

## Foundational Concepts

Related fields but not exactly accessibility:

- Web Performance - making the app small and fast so it can be used with slower internet connections.
- Internationalization - making the app translated to other languages for users around the world.
- UI Design - making the app easy to use and understand.

Types of Accessibility Considerations:

- Keyboard only users
- Head wand
- Mouth stick
- Single switch
- Screen reader

Accessibility Standards:

- Web Content Accessibility Guidelines ([WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/)) 2.0 ([Three levels of conformance](https://www.w3.org/WAI/WCAG21/Understanding/conformance#levels)):

  - A (lowest)
  - AA (medium) - recommended for minimum compliance
  - AAA (highest)

- [WebAIM](https://webaim.org/) - useful [checklist](https://webaim.org/standards/wcag/checklist) for web accessibility recommendations:

  - Perceivable
  - Operable
  - Understandable
  - Robust

## Screen Readers

Software that can read the content of an app out load to a user.

Features include:

- Read all content
- display list of links
- display a list of headings

There are many screen readers available. Below are some of the most popular ones:

- [JAWS](https://www.freedomscientific.com/products/software/jaws/)
- [NVDA](https://www.nvaccess.org/)
- [VoiceOver](https://www.apple.com/accessibility/mac/voiceover/)
- [ZoomText](https://www.zoomtext.com/)

Some screen readers are system specific, ex. Voiceover for Mac.

Chrome screen reader - built into the browser:

NVDA is most popular for Windows users.

\* Note on alternative text - when a screen reader encounters and image and doesn't have an alt text, it will read aloud the image filename.

\* In situations where image content is unknown, an empty alt tag will be skipped over by screen readers.
