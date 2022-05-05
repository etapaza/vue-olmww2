<template>
  <div class="app-form">
    <section class="form">
      <div class="field">
        
        <p>Pangrams are sentences which use every single letter of the alphabet. ex: “A quick brown fox jumps over the lazy dog.”</p>
        <p>Please fork this project and write a function which determines if the input is a pangram or not. If the input is a pangram return "Pangram!" If it is not, 
          please return the letters of the alphabet that are missing from the sentance. The sentence may include upper or lowercase letters or special characters
          but the returned letters should all be lowercase with special characters ommitted. You may use any libraries or tools at your disposal to help complete this project.
          Please also include responsive css styles on this page (this paragraph included) and the output as well, the design is up to you (feel free to be creative on css styles!). Bonus points for using TypeScript, validation and including accessibility. </p>

          <p> Vue.js documentation can be found here: <a href="https://vuejs.org/">Vue documentation</a>
        <div v-if="isSubmitted === false">
          <div class="">
            <label class="label">Pangram</label>
            <input class="input" type="text" placeholder="Text input">
          </div>
        </div>
         <div v-if="isSubmitted === true">
         
         </div>
      </div>
  
      <button type="submit">
        <span>submit</span> 
      </button>
    </section>
  </div>
</template>

<script>
import Vue from "vue";

export default {
  name: "pangram",
  data() {
    return {
      isSubmitted: false,
      form : {
        pangram: "",
      }
    } 
  },
  methods: {
    isPangram() {

    }
  } 
};

</script>

<style scoped lang="scss">

</style>