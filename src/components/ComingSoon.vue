<template>
  <div class="hello">
    <h2>Coming Soon!</h2>
    <h3 @click="test">Visit old site</h3>
  </div>
</template>

<script>
export default {
  name: 'ComingSoon',
  methods: {
    test: function () {
      location.href = 'https://legopitstop.weebly.com'
    }
  }
}
</script>

<style scoped>
h2  {
  font-size: 4em;
  text-align: center;
}

h3 {
  display: inline;
  color: #f80;
  cursor: pointer;
  text-decoration: underline;
}

.hello {
  background-color: #181818;
  padding: 1em;
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  border-radius: 1em;
}
</style>
