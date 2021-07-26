# query-dollar

Ultra-light, ESM-only wrapper for `document.querySelector` and
`document.querySelectorAll`.

## Install

```sh
npm i query-dollar
```

## Set-up (bundler)

```js
import {$, $$} from 'query-dollar';
```

## Set-up (direct import)

```js
import {$, $$} from './node_modules/query-dollar/dollar.js';
```

## Usage

Returns a DOM element of array of DOM elements:

```js
// Returns, e.g., <div id="aSingleElement">
$('#aSingleElement');

// Returns, e.g., [
//   <span class="givesAnArrayOfElements">,
//   <span class="givesAnArrayOfElements">
// ]
$$('.givesAnArrayOfElements');
```
