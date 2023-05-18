# Vue 3 Component Library

A simple Vue 3 Component Library with TypeScript and Vite.

## Quickstart

Build library

```shell
vite build
```

Use this component library in other Vue 3 project.

```shell
npm install vue3-component-library-ts

# OR

npm install /path/to/vue3-component-library-ts
```

```vue
<template>
  <div>
    <Heading :text="'Hello world'" />
  </div>
</template>

<script lang="ts">
import { Heading} from 'vue3-component-library-ts'; // Update the import path with the correct location and name of the component

export default {
  components: {
    Heading,
  },
};
</script>
```