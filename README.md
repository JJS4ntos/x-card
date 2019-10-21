# x-card

Simple and beautiful card made for vue.js created from nx-card.

## Table of contents

- [Installation](#installation)
- [Usage](#usage)

# Installation

```
npm install --save x-card
```

## Default import

Install all the components:

```javascript
import Vue from 'vue'
import xCard from 'x-card'

Vue.use(xCard)
```

## Distribution import

Install all the components:

```javascript
import 'x-card/dist/x-card.css'
import xCard from 'x-card/dist/x-card.common'

Vue.use(xCard)
```

## Browser

```html
<link rel="stylesheet" href="x-card/dist/x-card.css"/>
<script src="vue.js"></script>
<script src="x-card/dist/x-card.browser.js"></script>
```

The plugin should be auto-installed. If not, you can install it manually with the instructions below.

Install all the components:

```javascript
Vue.use(xCard)
```

# Usage

In the template, use the `x-card` directive:

```vue
<x-card url="https://vuejs.org">
  <template slot="title">Lorem ipsum dolor sit.</template>
  <template slot="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam voluptate exercitationem odit neque optio quos soluta illum earum nulla molestiae.</template>
  <template slot="image">
    <img src="image-url">
  </template>
</x-card>

```
