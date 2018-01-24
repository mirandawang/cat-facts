<template>
  <div>
    <h1>Random Cat Facts</h1>
    <p>
      {{ this.fact }}
    </p>
    <button v-on:click="showFact">Randomize!</button>
  </div>
</template>

<script type="text/javascript">

export default {
  props: ['facts'],
  data() {
    return {
      fact: this.facts[0],
    };
  },
  methods: {
    showFact() {
      const factNumber = Math.floor(Math.random() * this.facts.length);
      this.fact = this.facts[factNumber];
    },
  },
};

</script>

<style>
</style>
