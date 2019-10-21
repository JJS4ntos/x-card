# nx-card

<a href="https://www.npmjs.com/package/nx-card"><img src="https://img.shields.io/npm/v/nx-card.svg"/>  <img src="https://img.shields.io/npm/dm/nx-card.svg"/>  <img src="https://img.shields.io/badge/vue-2.x-brightgreen.svg" alt="vue2"></a>

!['screenshot'](https://github.com/nazar-xda/nx-card/raw/master/card.png)

Simple and beautiful card made for vue.js.

[Live Demo](http://nx-card.surge.sh)

## Table of contents

- [Installation](#installation)
- [Usage](#usage)

# Installation

```
npm install --save nx-card
```

## Default import

Install all the components:

```javascript
import Vue from 'vue'
import NxCard from 'nx-card'

Vue.use(NxCard)
```

## Distribution import

Install all the components:

```javascript
import 'nx-card/dist/nx-card.css'
import NxCard from 'nx-card/dist/nx-card.common'

Vue.use(NxCard)
```

## Browser

```html
<link rel="stylesheet" href="nx-card/dist/nx-card.css"/>
<script src="vue.js"></script>
<script src="nx-card/dist/nx-card.browser.js"></script>
```

The plugin should be auto-installed. If not, you can install it manually with the instructions below.

Install all the components:

```javascript
Vue.use(NxCard)
```

# Usage

In the template, use the `nx-card` directive:

```vue
<nx-card url="https://vuejs.org">
  <template slot="title">Lorem ipsum dolor sit.</template>
  <template slot="description">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam voluptate exercitationem odit neque optio quos soluta illum earum nulla molestiae.</template>
  <template slot="image">
    <img src="http://nx-card.surge.sh/logo.png">
  </template>
</nx-card>
         
```