# General CSS
* when you use _rem_ with font-size, the computed value will be calculated in relation to the root font-size, e.g. 1.5rem = 1.5 * 16px = 24px
* percentages with font-size refer to parent's font size
* percantages with lengths of elements refer to parent's **width**
* _em_ units use parent or current element as a reference and _rem_ use the root element font-size
* _em_ for fonts use the **parent's** font-size as a reference, whereas the _em_ for lengths use the **current element's** computed font-size
* line-height is relative to font-size
* props related to text **are inherited**
* when all child elements are floating, then the parent looses the height


# SASS
* what are mixins? kinda variables to make larger portions of css code reusable. They can also take arguments.
* placeholders work in opposite direction that mixins do
