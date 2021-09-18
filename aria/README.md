# Aria

Accessible Rich Internet Applications ([ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)) is a W3C standard for making web content more accessible.

Web Accessibility Initiative - Accessible Rich Internet Applications ([WAI-ARIA Specification](https://www.w3.org/TR/wai-aria-1.1/))

## Labels

ARIA has great tools for labelling and describing elements:

- aria-label - a human-readable label for an element
- aria-labelledby - a reference to an element that provides a human-readable label for an element
- aria-describedby

Difference between labelledby and describedby: label is essential information about the element, while describedby is more general information about the element.

Ex. a button that redirects can use aria-describedby to explain what will happen when the button is clicked.

## Roles, States, and Properties

ARIA provides roles that can be applied to any element. Examples include:

- button
- checkbox
- tree
- banner
- aria-autocomplete
- aria-haspopup

## Live Regions

Used to alert user of an change in an element's state. When content within the element changes, aria-live will announce the update. They will interrupt the user's current activity and notify them of the change.

Options include, **assertive**, **polite**, and **off**.
