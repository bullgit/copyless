# copy.less.CSS!

Prevent all the evil people from the internets of copying your content! Copy.less is written in Sass and uses `@extend` to prevent all your elements or specific elements from being copied.

See the [Demo on CodePen](http://codepen.io/kevingimbel/full/a31f922d753de0f129ccfabe500d6ec9/)!

### Usage

```scss
@import "copy.less";

.no-copy {
  @extend %no-copy;
}
```

```html
<div class="no-copy">
Can't touch this!
</div>
```
