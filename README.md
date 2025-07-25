<!--

@license Apache-2.0

Copyright (c) 2025 The Stdlib Authors.

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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Vector

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Vector constructors and associated utilities.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->

<section class="installation">

## Installation

```bash
npm install @stdlib/ndarray-vector
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@stdlib/ndarray-vector' );
```

#### ns

Namespace containing ndarray vector constructors and associated utilities.

```javascript
var o = ns;
// returns {...}
```

The namespace exports the following:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`BooleanVector()`][@stdlib/ndarray/vector/bool]</span><span class="delimiter">: </span><span class="description">create a boolean vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Complex128Vector()`][@stdlib/ndarray/vector/complex128]</span><span class="delimiter">: </span><span class="description">create a double-precision complex floating-point vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Complex64Vector()`][@stdlib/ndarray/vector/complex64]</span><span class="delimiter">: </span><span class="description">create a single-precision complex floating-point vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`vector()`][@stdlib/ndarray/vector/ctor]</span><span class="delimiter">: </span><span class="description">create a vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Float32Vector()`][@stdlib/ndarray/vector/float32]</span><span class="delimiter">: </span><span class="description">create a single-precision floating-point vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Float64Vector()`][@stdlib/ndarray/vector/float64]</span><span class="delimiter">: </span><span class="description">create a double-precision floating-point vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Int16Vector()`][@stdlib/ndarray/vector/int16]</span><span class="delimiter">: </span><span class="description">create a signed 16-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Int32Vector()`][@stdlib/ndarray/vector/int32]</span><span class="delimiter">: </span><span class="description">create a signed 32-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Int8Vector()`][@stdlib/ndarray/vector/int8]</span><span class="delimiter">: </span><span class="description">create a signed 8-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Uint16Vector()`][@stdlib/ndarray/vector/uint16]</span><span class="delimiter">: </span><span class="description">create an unsigned 16-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Uint32Vector()`][@stdlib/ndarray/vector/uint32]</span><span class="delimiter">: </span><span class="description">create an unsigned 32-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Uint8Vector()`][@stdlib/ndarray/vector/uint8]</span><span class="delimiter">: </span><span class="description">create an unsigned 8-bit integer vector (i.e., a one-dimensional ndarray).</span>
-   <span class="signature">[`Uint8ClampedVector()`][@stdlib/ndarray/vector/uint8c]</span><span class="delimiter">: </span><span class="description">create a clamped unsigned 8-bit integer vector (i.e., a one-dimensional ndarray).</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var ns = require( '@stdlib/ndarray-vector' );

console.log( objectKeys( ns ) );
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

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/ndarray-vector.svg
[npm-url]: https://npmjs.org/package/@stdlib/ndarray-vector

[test-image]: https://github.com/stdlib-js/ndarray-vector/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/ndarray-vector/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/ndarray-vector/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/ndarray-vector?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/ndarray-vector.svg
[dependencies-url]: https://david-dm.org/stdlib-js/ndarray-vector/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/ndarray-vector/tree/deno
[deno-readme]: https://github.com/stdlib-js/ndarray-vector/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/ndarray-vector/tree/umd
[umd-readme]: https://github.com/stdlib-js/ndarray-vector/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/ndarray-vector/tree/esm
[esm-readme]: https://github.com/stdlib-js/ndarray-vector/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/ndarray-vector/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/ndarray-vector/main/LICENSE

<!-- <toc-links> -->

[@stdlib/ndarray/vector/bool]: https://github.com/stdlib-js/ndarray-vector-bool

[@stdlib/ndarray/vector/complex128]: https://github.com/stdlib-js/ndarray-vector-complex128

[@stdlib/ndarray/vector/complex64]: https://github.com/stdlib-js/ndarray-vector-complex64

[@stdlib/ndarray/vector/ctor]: https://github.com/stdlib-js/ndarray-vector-ctor

[@stdlib/ndarray/vector/float32]: https://github.com/stdlib-js/ndarray-vector-float32

[@stdlib/ndarray/vector/float64]: https://github.com/stdlib-js/ndarray-vector-float64

[@stdlib/ndarray/vector/int16]: https://github.com/stdlib-js/ndarray-vector-int16

[@stdlib/ndarray/vector/int32]: https://github.com/stdlib-js/ndarray-vector-int32

[@stdlib/ndarray/vector/int8]: https://github.com/stdlib-js/ndarray-vector-int8

[@stdlib/ndarray/vector/uint16]: https://github.com/stdlib-js/ndarray-vector-uint16

[@stdlib/ndarray/vector/uint32]: https://github.com/stdlib-js/ndarray-vector-uint32

[@stdlib/ndarray/vector/uint8]: https://github.com/stdlib-js/ndarray-vector-uint8

[@stdlib/ndarray/vector/uint8c]: https://github.com/stdlib-js/ndarray-vector-uint8c

<!-- </toc-links> -->

</section>

<!-- /.links -->
