vim-css-syntax
===============

Vim's built-in `syntax/css.vim` has some bugs and some of these bugs cannot be fixed with `after/syntax/css.vim`. This patched syntax file fixes all bugs I know:

  * `object` element is missing
  * `sans-serif` cannot be highlighted when `set iskeyword+=-`
  * `background-repeat` property is missing
  * `contained` argument is missing in one of the `cssTextProp`
  * `text-indent` property is not `cssTextAttr`, is `cssTextProp`
  * `inline-block` value is missing
  * `run-in`, `inline-table`, and `list-item` are not `cssRenderProp`, are `cssRenderAttr`

Patches welcome!
