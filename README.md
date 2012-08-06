vim-css-syntax
===============

Vim's built-in `syntax/css.vim` has some bugs and some of these bugs cannot be fixed with `after/syntax/css.vim`. This patched syntax file fixes all bugs I know:

  * `braile`, `embosed`, and `ty` are typo
  * `clip()` function is deprecated
  * `page`, `size`, `marks`, and `inside` are not valid properties
  * `landscape`, `portrait`, `crop`, and `cross` are not valid values
  * `text` and `progress` values are missing
  * `text-row-gorup` is typo
  * `pre-wrap` and `pre-line` values are missing
  * `speak-numerals` is typo
  * `speak-header` is `cssAuralProp`, not `cssTableProp`
  * `pitch` property is missing
  * `low`, `high`, `x-low`, and `x-high` values are missing
  * `object` element is missing
  * `sans-serif` cannot be highlighted when `set iskeyword+=-`
  * `background-repeat` property is missing
  * `contained` argument is missing in one of the `cssTextProp`
  * `text-indent` property is not `cssTextAttr`, is `cssTextProp`
  * `inline-block` value is missing
  * `run-in`, `inline-table`, and `list-item` are not `cssRenderProp`, are `cssRenderAttr`

Patches welcome!
