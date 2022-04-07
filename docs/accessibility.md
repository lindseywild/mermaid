# Accessibility

Making Mermaid.js charts fully accessible is still a work in progress. Feel free to [contribute](https://github.com/mermaid-js/mermaid/blob/develop/CONTRIBUTING.md!)

## Title and Description

Each chart supports a `title` and `accDescription` that will add a `<title>` and `<description>` element to the rendered SVG. Unless otherwise specified, these will not be visible. Adding these will help screen reader users know what the chart or graph is about.

- `title` should be the title of the chart
- `description` should be a description of what is depicted in the chart

### Examples

`title`: Should I buy a dog?
<br>
`description`: A flow chart depicting the decision process of buying a dog.

`title`: Percentage of animals
<br>
`description`: A pie chart showing that there are 500 total animals; 200 cats and 100 dogs.
