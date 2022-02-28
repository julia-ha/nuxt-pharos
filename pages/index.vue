<template>
    <homepage-pharos-button>
    Vue button
   </homepage-pharos-button>
</template>


<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@webcomponents/scoped-custom-element-registry@0.0.3/scoped-custom-element-registry.min.js"></script>
<script>
  import { PharosAlert, PharosButton, PharosIcon } from '@ithaka/pharos';
  import registerComponents from '@ithaka/pharos/lib/utils/registerComponents';
  import "@ithaka/pharos/lib/styles/fonts.css";
  import "@ithaka/pharos/lib/styles/variables.css";

  registerComponents('homepage', [PharosAlert, PharosButton, PharosIcon]);


  export default {
    name: 'IndexPage'
  }
</script>
