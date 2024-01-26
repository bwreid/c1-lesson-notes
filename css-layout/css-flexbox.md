# CSS Flexbox

By the end of this lesson, you will be able to:

- Understand the principles of the Flexbox layout.
- Create flexible and responsive web layouts using Flexbox.
- Utilize Flexbox properties for alignment and space distribution.

## Context

As you've seen, layout really matters in terms of presenting a cohesive design. One powerful tool in your toolbox is _flex box_, which allows for multiple elements to be aligned together within a containing element. We can see an example of flexbox on the [Dribbble](https://dribbble.com/) website. On both the main page and the jobs page, flex is used to easily create a layout.

It's important to note that we don't _need_ flexbox. We could attain a similar layout with what we've already learned. However, flexbox is a powerful tool that will make designing webpages _easier_, therefore it's a great idea for us to master it.

## Guiding questions

### Getting Started

#### Overview: Definition & Components

- What is the difference between "flex container" properties and "flex item" properties?

  > Flex container properties affect the containing element or _all_ of the items within them. Flex item properties can affect a _specific_ flex item.

- This relationship is also sometimes referred to as a "parent-child" relationship. Take a read through [this page](https://forum.freecodecamp.org/t/parent-element-and-child-element/453992) then answer the following question: what is a parent-child relationship in coding?

  > Most broadly, a parent-child relationship refers to whenever an entity (e.g., an HTML element, a data structure) has multiple other entities _underneath or within it_ (e.g., other HTML elements, data). In the example of HTML, it is possible for one element to contain multiple other HTML elements. In this case, the containing element is the parent and all of the elements directly within it are children. Parents can be children and children can become parents.

### Flex Container Properties

#### Display: Flex

- Based on just this example, what could you do to achieve a similar result _without_ using flexbox?

  > It would be possible to float each element to the left, followed by a "clearfix" hack. You could also set the `display` value as `inline-block`.

- For the majority if this lesson, I am going to hand it over to you all to do the research on specific properties for containers and items. Let's first do a couple together.

  1. Flex direction.
  2. Flex grow.

- For your assigned container or item property below, go to the appropriate page on Codio and work to understand the property. Write up two or three sentences _on your own_ that help you understand what the property does and how the values may affect the overall layout. Next, respond to the appropriate thread in Slack with your own explanation of how the property works.

  This process, of taking what you've learned and putting it into your own words, is an important part of learning. So, if someone else writes an explanation you think is great, you should still write your own! We'll discuss all of the properties together with a different example in a few minutes.

  Based on your last name, review the following lesson:

  - A to B: Flex Wrap
  - C to D: Justify Content
  - E to H: Align Items
  - I to L: Align Content
  - M to N: Gap
  - O to S: Flex Shrink
  - T to U: Flex Basis
  - V to Z: Flex Shorthand

  [Codepen: Flexbox Playground](https://codepen.io/enxaneta/full/adLPwv/) may be of use.

## Resources

- [Flexbox Froggy](https://flexboxfroggy.com/)
- [CSS Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Codepen: Flexbox Playground](https://codepen.io/enxaneta/full/adLPwv/)
