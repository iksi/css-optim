# CSSO

CSS optimization inspired by Jens Oliver Meiert’s book <https://github.com/j9t/css-optimization-basics/>.

## Declaration sorting

Sort declarations alphabetically.

## Selector sorting

The following order is based on <https://html.spec.whatwg.org/multipage/#toc-semantics> (with the exception of the main element).

### Universal
- *

### Document
- html

### Document metadata
- head
- title
- base
- link
- meta
- style

### Sections
- body
- main
- article
- section
- nav
- aside
- h1
- h2
- h3
- h4
- h5
- h6
- hgroup
- header
- footer
- address

### Grouping content
- p
- hr
- pre
- blockquote
- ol
- ul
- menu
- li
- dl
- dt
- dd
- figure
- figcaption
- div

### Text-level semantics
- a
- em
- strong
- small
- s
- cite
- q
- dfn
- abbr
- ruby
- rt
- rp
- data
- time
- code
- var
- samp
- kbd
- sub
- sup
- i
- b
- u
- mark
- bdi
- bdo
- span
- br
- wbr

### Edits
- ins
- del

### Embedded content
- picture
- source
- img
- iframe
- embed
- object
- param
- video
- audio
- track
- map
- area
- math
- svg

### Tabular data
- table
- caption
- colgroup
- col
- tbody
- thead
- tfoot
- tr
- td
- th

### Forms
- form
- label
- input
- button
- select
- datalist
- optgroup
- option
- textarea
- output
- progress
- meter
- fieldset
- legend

### Interactive elements
- details
- summary
- dialog

### Scripting
- script
- noscript
- template
- slot
- canvas

### Attributes
- .class
- \#id

## ID and class naming

- keep use of IDs and classes to a _minimum_
- if needed, use _functional_ ID and class names
- otherwise use _generic_ ID and class names
- use names that are _as short as possible but as long as necessary_

## Shorthands

Use shorthands when possible. An overview of CSS shorthands:

- animation
- background
- border
- border-bottom
- border-color
- border-left
- border-radius
- border-right
- border-style
- border-top
- border-width
- column-rule
- columns
- flex
- flex-flow
- font
- grid
- grid-area
- grid-column
- grid-row
- grid-template
- list-style
- margin
- offset
- outline
- overflow
- padding
- place-content
- place-items
- place-self
- text-decoration
- transition
