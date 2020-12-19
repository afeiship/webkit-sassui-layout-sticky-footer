# wsui-layout-sticky-footer
> Sticky footer use absolute solution.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-layout-sticky-footer
```

## usage
```scss
@import '~@jswork/wsui-layout-sticky-footer';

.global-sticky-footer{
  @include wsui-layout-sticky-footer(100px, 10px);
}
```

```html
<section class="global-sticky-footer">
  <div class="is-body"> Body </div>
  <!-- ... -->
  <!--  .is-footer  -->
  <footer class="is-footer">
    <p> My Footer </p>
  </footer>
</section>
```

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-layout-sticky-footer/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-layout-sticky-footer
[version-url]: https://npmjs.org/package/@jswork/wsui-layout-sticky-footer

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-layout-sticky-footer
[license-url]: https://github.com/afeiship/wsui-layout-sticky-footer/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-layout-sticky-footer
[size-url]: https://github.com/afeiship/wsui-layout-sticky-footer/blob/master/dist/wsui-layout-sticky-footer.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-layout-sticky-footer
[download-url]: https://www.npmjs.com/package/@jswork/wsui-layout-sticky-footer

