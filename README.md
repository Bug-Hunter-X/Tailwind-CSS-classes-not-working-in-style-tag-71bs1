# Tailwind CSS Classes Not Working in Style Tag

This repository demonstrates a bug where Tailwind CSS classes are not applied correctly when defined within a `<style>` tag.  The expected behavior is that the classes `.bg-red-500` and `.text-xl` should apply their respective styles.  However, in the provided example, these classes fail to style the elements.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe that the text is not red or extra-large.

## Solution

The issue is resolved by importing Tailwind's stylesheet correctly. This example utilizes the CDN version, but the issue persists with local installations if the Tailwind directives aren't correctly placed within your CSS.