# How to Apply CSS Styles to HTML with Cascade and Specificity

Styles can be applied to elements on a webpage three ways: inline on a specific element, using the `<style>` tag within the HTML, and loading an external stylesheet into the document. Styles are applied as the browser traverses the CSS cascade (in order, given equal specificity), which can be overridden by more specific selectors (like class selectors). The example in `index.html` demonstrates this in action, as well as how the `!important` rule overrides both the cascade and specificity.
