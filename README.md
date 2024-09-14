# Overflow Property Demo

This HTML file demonstrates the use of the CSS `overflow` property in different states: `visible`, `hidden`, `scroll`, and `auto`. The `overflow` property controls how content is displayed when it exceeds the size of its container.

## Description

The file includes four different `div` elements with the following `overflow` behaviors:

1. **Overflow: visible** (default) - Content is not clipped and renders outside the element's box.
2. **Overflow: hidden** - Content that overflows the element's box is clipped.
3. **Overflow: scroll** - Content that overflows is scrollable.
4. **Overflow: auto** - Adds scrollbars only when content overflows the box.

Each element has the following properties:
- Background color: Custom for each element.
- Width: 200px.
- Height: 65px.
- Border: 1px solid black.
- Overflow: Controls the content overflow behavior (`visible`, `hidden`, `scroll`, or `auto`).

## File Structure

- `index.html`: Main HTML file containing the overflow demo.
- `style`: CSS styles are defined within the `<style>` tag inside the `<head>` of the HTML.

## How to Run

1. Save the HTML content in a file, e.g., `index.html`.
2. Open the file in a browser to see the overflow behavior.

## Example
# OUTPUT
https://mohamedyusuf007.github.io/overflow/


```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .hi1 { ... } /* Example class for overflow: visible */
    .hi2 { ... } /* Example class for overflow: hidden */
    .hi3 { ... } /* Example class for overflow: scroll */
    .hi4 { ... } /* Example class for overflow: auto */
  </style>
</head>
<body>
  <h2>Overflow: visible</h2>
  <div class="hi1">Content that may overflow.</div>

  <h2>Overflow: hidden</h2>
  <div class="hi2">Content that may overflow.</div>

  <h2>Overflow: scroll</h2>
  <div class="hi3">Content that may overflow.</div>

  <h2>Overflow: auto</h2>
  <div class="hi4">Content that may overflow.</div>
</body>
</html>
