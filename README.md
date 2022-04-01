<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Generator Support

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Detect native [`generator function`][generator-function] support.



<section class="usage">

## Usage

```javascript
import hasGeneratorSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-generator-support@esm/index.mjs';
```

#### hasGeneratorSupport()

Detects if a runtime environment supports ES2015 [`generator functions`][generator-function], i.e. `function*()`.

```javascript
var bool = hasGeneratorSupport();
// returns <boolean>
```

</section>

<!-- /.usage -->

<section class="notes">

## Notes

-   The implementation uses code evaluation, which may be problematic in browser contexts enforcing a strict [content security policy][mdn-csp] (CSP).

</section>

<!-- /.notes -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import hasGeneratorSupport from 'https://cdn.jsdelivr.net/gh/stdlib-js/assert-has-generator-support@esm/index.mjs';

var bool = hasGeneratorSupport();
if ( bool ) {
    console.log( 'Environment has native generator function support.' );
} else {
    console.log( 'Environment lacks native generator function support.' );
}

</script>
</body>
</html>
```

</section>

<!-- /.examples -->



<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2022. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/assert-has-generator-support.svg
[npm-url]: https://npmjs.org/package/@stdlib/assert-has-generator-support

[test-image]: https://github.com/stdlib-js/assert-has-generator-support/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/assert-has-generator-support/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/assert-has-generator-support/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/assert-has-generator-support?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/assert-has-generator-support.svg
[dependencies-url]: https://david-dm.org/stdlib-js/assert-has-generator-support/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/assert-has-generator-support/tree/deno
[umd-url]: https://github.com/stdlib-js/assert-has-generator-support/tree/umd
[esm-url]: https://github.com/stdlib-js/assert-has-generator-support/tree/esm

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/assert-has-generator-support/main/LICENSE

[generator-function]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*

[mdn-csp]: https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP

</section>

<!-- /.links -->
