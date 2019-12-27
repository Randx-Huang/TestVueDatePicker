<template>
  <div class="hello">
    <div id="app">
      <vue-ctk-date-time-picker
        :dark="true"
        v-model="selectedDate"
        range
        id="RangeDatePicker"
        format="YYYY/MM/DD"
        formatted="ll"
        :noHeader="true"
        :onlyDate="true"
        :noShortcuts="true"
        :overlay="true"
        :noLabel="true"
      ></vue-ctk-date-time-picker>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      selectedDate: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
