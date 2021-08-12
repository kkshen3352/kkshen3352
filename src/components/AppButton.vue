https://vueschool.io/lessons/using-slots


  Adding v-on="$listeners" is not be needed in v3
  In fact $listeners was removed, as documented here:
  https://v3.vuejs.org/guide/migration/listeners-removed.html


<template>

  
  <button v-on="$listeners"> 
    <slot></slot>
  </button>
 

  <button>
    <slot></slot>
  </button>

</template>

<script>
export default {}
</script>
