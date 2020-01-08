# Installation

```
npm install whatwg-fetch --save
```

As an alternative to using npm, you can obtain `fetch.umd.js` from the
[Releases][] section. The UMD distribution is compatible with AMD and CommonJS
module loaders, as well as loading directly into a page via `<script>` tag.

You will also need a Promise polyfill for [older browsers](http://caniuse.com/#feat=promises).
We recommend [taylorhakes/promise-polyfill](https://github.com/taylorhakes/promise-polyfill)
for its small size and Promises/A+ compatibility.

## Usage

For a more comprehensive API reference that this polyfill supports, refer to
https://github.github.io/fetch/.
