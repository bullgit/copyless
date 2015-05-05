# copy.less.CSS!

Prevent all the evil people from the internets of copying your content! Copy.less is written in Sass and uses `@extend` to prevent all your elements or specific elements from being copied.


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
