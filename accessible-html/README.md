# Accessible HTML

## Semantic HTML

Some elements have semantic meaning but no specific functionality.

- aside
- footer
- header

Other elements have a lot of built-in functionality

- button
- input
- textarea

Important elements in terms of accessibility:

- headings
- links
- lists
- tables
- blockquotes
- forms
- images

Example: Labels and forms

Labels are important for accessibility, and should not be substituted with other elements like `<p>` or `<span>`.

Ex. `<label for='first-name'>First Name</label>` or `<label>Last Name<input id='lastName' type='text' /></label>`

In situations where a label is needed, but cannot be added to an element, the **aria-label** attribute can be used instead.

## Communicating with Screen Readers

It's possible to add an element to the HTML, but make it visually hidden to screen readers.
