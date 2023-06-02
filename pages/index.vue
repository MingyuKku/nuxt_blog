<template>
  <Tutorial/>
</template>

<script>
import { test } from '../content/hello';

export default {
  name: 'IndexPage',
  mounted() {
    test();
  }
}



</script>

