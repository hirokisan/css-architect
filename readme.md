# CSS-ARCHITECT

## ARCHITECTURE
```
link:css css/home/home.css

export home.css from...
	@include css/common/main.css
		@include css/common/reset.css
		@include css/common/utility.css /* e.g, body, h1, p, p10 */
		@include css/common/component.css /* e.g, btn, nav */
  @include css/home/component.css /* e.g, component for current project, move component to css/common/component.css if its useful*/
	@include css/home/cosmetic.css /* Modifier, Wrap, Mixes */

compile public/ from assets/ with task runner such as Gulp.js, Webpack
```
