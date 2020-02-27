<template>
  <div class="evaluation">
    <h3>Moon Value Evaluation</h3>
    <p>Just paste the result of your moon probing in the box underneath and the value of each moon will be caculated based on the market value of each ore</p>
    <md-field>
      <label>Moon Survey Results</label>
      <md-textarea v-model="surveyResults"></md-textarea>
    </md-field>
  </div>
</template>

<script>
export default {
  name: "Evaluation",
  data: () => {
    return {
      surveyResults: ""
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
