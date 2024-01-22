# CSS Box Model

By the end of this lesson, you will be able to:
- Understand the components of the CSS Box Model.
- Apply margins, borders, padding, and content dimensions in CSS.
- Use the box model to control element spacing and layout.

## Context

Layout is what makes overall web experiences understandable and excellent.
- Example: https://dribbble.com/

## Guiding questions

### Warm Up

#### Trivia Question 1

- What does "cascading" in Cascading Stylesheets refer to?

  > Cascading refers to how order and specificity are used to apply styles to the page, as if each rule "cascades" over the other.

#### Trivia Question 2

- Let's define the various terms of a CSS rule.

  > [This page](https://www.w3schools.com/css/css_syntax.asp) accurately breaks down the various terms for a CSS rule.

### Box Model Components

#### Example: Content

- Do HTML elements by default have a height and width?

  > Yes, elements will take up some amount of space depending on the type of element. For example, a `p` element will have a width equal to its containing element and a height dependent on the text within it.

#### Example: Padding

- How does padding affect the width and height of an element?

  > It will increase the width and height of an element.

#### Example: Margin

- Inspect the elements on this page. What color is the `margin` property when inspected? How do margins interact with one another.

  > Margins appear orangey in the inspector. When margins are stacked against one another vertically, they collapse into one another, with the larger margin taking over. This is called margin collapse.

### Sizing Boxes

#### Example: content-box vs border-box

- What do you think is more intuitive? `border-box` or `content-box`?

### Position

#### Example: Static

- What is the "normal flow of the document?"

  > Top to bottom.

#### Example: Absolute

- What happens to the default width of absolutely positioned elements?

  > The element's default width may change if it was a block element.
