# Tooltip

Tooltip component is based on [hint.css](https://github.com/chinchang/hint.css) for Vue Bulma.

Fork of [vue-bulma/tooltip](https://github.com/vue-bulma/tooltip)

## Installation

```
$ npm install --save https://github.com/Almendio/vue-bulma-tooltip
```


## Examples

```vue
<template>
  <tooltip label="This is title" placement="top-right">
    <button class="button is-primary has-text-centered">
      <span>top-right</span>
    </button>
  </tooltip>
</template>

<script>
import Tooltip from 'vue-bulma-tooltip'

export default {
  components: {
    Tooltip
  }
}
</script>
```
