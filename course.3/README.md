## Course 3

Let us cover the next major part on our journey of understanding CSS. We will continue to look at some properties of
interests, how they can be used in collection with other properties, and finally look into display types and flex
properties.

### Further Properties

* `border` - style the borders of the tag, following the values of width, style, and color
  * `border: 15px solid red;` - this defines a red solid 15px border surrounding the tag
  * `border: 10px dotted;` - this defines a dotted border of size 10px
  * `border: double;` - this defines a double-lined border
  * by default, the border style is of `medium none inherited-color`
* `font-weight` - determines the thickness of the text, defined by either `normal`, `bold`, `bolder`, `lighter` or
    `[1-9]00`
* `text-indent` - specify the indentation present on the first line of a text block (paragraph)
* `text-transform` - control the capitalization of text through this property, `none`, `capitalize`, `uppercase`, and
    `lowercase`
* `transform` - while the functions for this property require further discussion, its existance should be noted
* `visibility` - visibility will cause an element to not be rendered onto the page, but it will still take space
* `width` and `height` - we can "hardcode" the dimensions of tags, the default is set to `auto`
* `min-width` and `max-width` - this sets the minimum size that must be true to apply this style
* `min-height` and `max-height` - similarly to above, except it sets a maximum size value for this style
* `overflow-x` and `overflow-y` - at times, a block-level tag may either clip or hide overflow content. This property
    can be set with the values `visible`, `hidden`, and `scroll`
* `text-overflow` - in some similar style, sometimes overflowing text should not be rendered, or, rather, show that
    the text body continues afterwards and should be represented with ellipsis. This property can be set with the values
    `clip` or `ellipsis`, and usually follows the properties `white-space: nowrap; overflow: hidden;`
* `z-index` - thinking of stacked sheets, a higher value signifies the sheet being higher in the stack. **NOTE** that
    this works for flex items and tags in the `absolute`, `relative`, `fixed`, or `sticky` position
* `display` - this property alters the way the selected tag is rendered, relative to its surrounding tags
  * `inline` - render the element as inline, any height and width properties are ignored
  * `block` - render the element as a block
  * `flex` - renders the element in a flexible way
    * `align-content` - align its flex children along 
    * `align-items` - consider this as the filling caused by its children, considering its flex direction
    * `align-self` - this overrides the effect of its parent `align-items`
    * `justify-content` - aligns all of the flexible container's items
    * `flex-direction` - set the direction of rendering for its children, by `row` or `column` direction
