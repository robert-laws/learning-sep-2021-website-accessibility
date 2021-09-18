# Focus Management

## Overview

As a user navigates through a webpage with the keyboard, the focus ring provides the necessary clue as tot eh currently active item.atrule

Keyboard shortcuts can be provided by websites to help keyboard-only users and power users. Websites like Twitter and Facebook have several keyboard shortcuts that are available to all users.

## Skip Links

Keyboard only users can navigate past navigational links by pressing the tab key. This is done with an anchor tag in the body of the website and is visually hidden, but when a screen reader encounters it, the user can use it to navigate past the navigation.

## Tab Navigation

A keyboard only user can use **tab** to navigate to the next elements and **shift + tab** to navigate to the previous elements.

Tab-able elements include:

- anchors
- button
- input
- select
- textarea
- iframe

Sometimes elements that are not tab-able, but need to be tab-able can use the `tabindex` attribute.

Tabindex values:

- negative value means that the element should be focusable, but should not be reachable via sequential keyboard navigation.
- 0 means that the element should be tab-able and reachable via sequential keyboard navigation, but the order is defined by the browser.
- positive value means that the element should be focusable and reachable via sequential keyboard navigation, but the sequence should follow the numbering of the tabindex value.

## Active Element

The currently active element can be captured with the `document.activeElement` property. The item can be re-focused using the `element.focus()` method.

## Tab Trapping

In situations where there are elements like a modal dialog is used, it's important to trap the tab key to keep users within the appropriate context and not back to the main web page.
