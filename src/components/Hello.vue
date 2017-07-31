<template>

  <div id="example-1">

    <main>
    <v-layout  row wrap>
      <v-flex xs12>
        <v-card  dark class="primary">
          <v-card-text id="heading" class="headline">Rockies Locator</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
    </main>
    <v-footer id="footing" :absolute="true">
      <v-card-text>
      <p class="title mb-0 text-xs-center">Copyright Ninjames101 2017</p>
      </v-card-text>
    </v-footer>

  </div>

</template>





<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Rockies landing',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#example-1 {
   text-align: center;
 }
#heading {
  color: #fff;
  background-color: #24135e;
}
#footing {
  background-color: #24135e;
  color: #fff;
}

</style>
