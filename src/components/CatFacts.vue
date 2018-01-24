<template>
  <div>
    <h1>Random Cat Facts</h1>
    <p>
      {{ facts }}
    </p>
    <button>Randomize!</button>
  </div>
</template>

<script type="text/javascript">

export default {
  props: ['facts']
};

</script>

<style>
</style>
