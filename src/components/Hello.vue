<template>
<div id="example-1">
  <main>
    <v-layout row wrap>
      <v-flex xs12>
        <v-card dark class="primary">
          <v-card-text id="heading" class="headline">Rockies Locator</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
    <div class="text-xs-center">
      <v-btn id="traffic-btn"  class="body-1" round>Is Traffic Going To Suck Today?</v-btn>
    </div>
    <v-container fluid>
      <v-layout row wrap>
        <v-flex xs12>
          <v-card id="info-card" class="mb-4">
            <v-container  fluid grid-list-lg>
              <v-layout row>
                <v-flex xs2>
                  <div id="spacer">
                  </div>
                </v-flex>
                <v-flex xs8>
                  <div>
                    <div class="headline">Yes</div>
                    <div>Here is why</div>
                  </div>
                </v-flex>
                <v-flex xs2>
                  <div id="spacer">
                  </div>
                </v-flex>
              </v-layout>
            </v-container>
          </v-card>
        </v-flex>
      </v-layout>
    </v-card>
    </v-flex>
    </v-layout>
    <v-layout row wrap>
      <v-flex xs12>
        <v-card id="info-card">
          <v-container fluid grid-list-lg>
            <v-layout row>
              <v-flex xs2>
                <div id="spacer">
                </div>
              </v-flex>
              <v-flex xs8>
                <div>
                  <div class="headline">Probably</div>
                  <div>But Not Because Of The Rockies</div>
                </div>
              </v-flex>
              <v-flex xs2>
                <div id="spacer">
                </div>
              </v-flex>
            </v-layout>
          </v-container>
        </v-card>
      </v-flex>
    </v-layout>
  </v-card>
  </v-flex>
  </v-layout>
    </v-container>
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

#heading, #footing, #traffic-btn {
  color: #fff;
  background-color: #24135E;
}

#spacer {
  height: 10%;
}
#info-card {
  color: #24135E;
  background-color: #CACDCD;
}
</style>
