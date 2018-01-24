<template>
  <div id="app">
    <CatFacts v-bind:facts="catfacts" />
  </div>
</template>

<script>
import CatFacts from './components/CatFacts';

export default {
  name: 'App',
  components: {
    CatFacts,
  },
  data() {
    return {
      catfacts: [
        'The ancient Egyptians were the first to tame the cat (in about 3000 BC), and used them to control pests.',
        'Cats share 95.6% of their DNA with tigers.',
        'Cats are asleep for 70% of their lives.',
        'Cat kidneys are super efficient, they can rehydrate by drinking seawater.',
        'Kittens who are taken along on short, trouble-free car trips to town tend to make good passengers when they get older.',
        'They get used to the sounds and motions of traveling and make less connection between the car and the visits to the vet.',
        'Cats can jump approximately seven times their height',
        'A group of kittens is called a kindle, and a group of cats is called a clowder',
        'A cat has 230 bones — even more than a human!',
        'Cats greet one another by touching noses - boop!',
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
