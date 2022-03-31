# Reading Notes: Basics of HTML, CSS & JS

## Chapter 2: Text (pp.40-61)

- HTML tags are used to describe how the webpage is laid out.

- Semantic tags tell us what the content is doing. The browser doesn't nessecarily care but it helps us put things into categories that assist us in adding css and js later on.

## Chapter 10: Introducing CSS (pp.226-245)

- Block
  - Displays things on a new line, similar to the `<br>` tag. Some HTML elements have block layout by default.`h1, p, div`
- Inline
  - Elements flow within the text and do not start on a new line. Examples are `img, span`

- CSS applies things in a downward fashion, hence the "Cascading" part.
- Selectors
  - `*` applies to everything
  - type selectors apply to the html tag. `h1, {}`
  - `.class` applies to an entire class. You can specify this in your opening html tags. `<h1 class="a name">`
    - you can apply a class selector to only a class *within* an html tag. `p.class`
  - id selector is typically used for a one time element instead of applying to an entire class. `#id`
  - if you have overlapping styles, the latter will take priority.
    - you can override this with `!important`
  - box model




## Chapter 2: Basic JavaScript Instructions (pp.53-84)

- Statements are each individual instruction. Ended with a `;`
- JS is case sensitive.
- Curly braces are used to group code blocks.
- Comments can be added with `//`, multiline comments are `/*start     end */`
- Variables are defined with `let` and `const`. Variables store objects.
- There are many data types but the primary ones are: numberic, string, and boolean
- camelCasing
- Arrays are formed with `[content, content, content]`. They can be multidemensional.
  - Array constructors are used by `Array(content,content, content)`

## Chapter 4: Decisions and Loops (pp.145-162)

- Switch Statements
  - Presents users with a different statement depending on which level the user is on.
  - break is used to get out of the switch statement.




