<template>
  <v-app>
    <v-toolbar class="white">
      <v-toolbar-title v-text="title"></v-toolbar-title>
    </v-toolbar>
    <v-content>

      <section>
        <v-layout column class="my-5">
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap>
                <v-flex xs12 md6>
									<v-card>
                    <v-responsive min-height="350" transition :contain=true>
										  <v-img class="white--text" src="../../static/images/2dfd3c34fef146579660cab4600ebd10.webp"></v-img>
                    </v-responsive>
										<v-card-title>
                      <v-flex>
                        <div class="avatar-section py-3">
                          <v-avatar slot="activator" size="36px" ma-2>
                            <img :src=returnAvatar() alt="Avatar">
                          </v-avatar>
                          <div>
                            <v-flex py-0 class="caption">John Leider</v-flex>
                            <v-flex py-0 d-inline-flex class="caption">
                              <span class="pdr-10">4 days ago</span>
                              <li></li>
                              <span>1 min</span>
                            </v-flex>
                          </div>
                          <v-spacer></v-spacer>
                          <v-icon small>fas fa-ellipsis-v</v-icon>
                        </div>
                        <div class="title-section">
                          <div>
                            <div class="title mb-0 py-3">Outdoor cooking hacks</div>
                            <div class="subheading">Create a blog post subtitle that summarizes your post in a few short, punchy sentences and entices your audience to continue reading. Welcome to your...</div>
                          </div>
                        </div>
                      </v-flex>
										</v-card-title>
                    <v-flex px-4><v-divider></v-divider></v-flex>
                    <v-flex pa-4>
                      <div class="card-footer">
                        <div class="caption">0 views</div>
                        <div class="caption ml-3">Write a comment</div>
                        <v-spacer></v-spacer>
                        <v-icon small color="red">far fa-heart</v-icon>
                      </div>
                    </v-flex>
									</v-card>
                </v-flex>
                <v-flex xs12 md6>
									<v-card>
                    <v-responsive min-height="300" transition max-height="600">
										  <v-img class="white--text" src="../../static/images/b9129a16fc024475a5f969c9bc538a63.webp"></v-img>
                    </v-responsive>
										<v-card-title>
                      <div class="avatar-section py-3">
                        <v-avatar slot="activator" size="36px" ma-2>
                          <img :src=returnAvatar() alt="Avatar">
                        </v-avatar>
                        <div>
                          <v-flex py-0 class="caption">John Leider</v-flex>
                          <v-flex py-0 d-inline-flex class="caption">
                            <span class="pdr-10">4 days ago</span>
                            <li></li>
                            <span>1 min</span>
                          </v-flex>
                        </div>
                        <v-spacer></v-spacer>
                        <v-icon small>fas fa-ellipsis-v</v-icon>
                      </div>
                      <div class="title-section">
                        <div>
                          <div class="title mb-0 py-3">Picture perfect campsites</div>
                          <div class="subheading">Create a blog post subtitle that summarizes your post in a few short, punchy sentences and entices your audience to continue reading. Welcome to your blog post. Use this space to connect with your </div>
                        </div>
                      </div>
										</v-card-title>
									</v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section>
        <v-parallax src="assets/section.jpg" height="380">
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-3 text-xs-center">Web development has never been easier</div>
            <em>Kick-start your application today</em>
            <v-btn class="blue lighten-2 mt-5" dark large href="/pre-made-themes">
              Get Started
            </v-btn>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Company info</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                  Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.
                  Nullam in aliquet odio. Aliquam eu est vitae tellus bibendum tincidunt. Suspendisse potenti.
                </v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>
                  Cras facilisis mi vitae nunc lobortis pharetra. Nulla volutpat tincidunt ornare.
                </v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>777-867-5309</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Chicago, US</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>john@vuetifyjs.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>

      <v-footer class="blue darken-2">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">
              Made with
              <v-icon class="red--text">favorite</v-icon>
              by <a class="white--text" href="https://vuetifyjs.com" target="_blank">Vuetify</a>
              and <a class="white--text" href="https://github.com/vwxyzjn">Costa Huang</a>
            </div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </v-app>
</template>

<style>
html {
  background-color: #9FA8DA;
}
.card-footer {
  display: flex;
}

.card-footer .caption {
  font-weight: 300;
}
.pd-5 {
  padding: 5px;
}

.pdr-5 {
  padding-right: 5px;
}
.pdr-10 {
  padding-right: 10px;
}

.avatar-section {
  display: flex;
  width: 100%
}

.title-section {
  width: 100%;
}

.title-section .title{
  font-weight: 300;
}

.title-section .subheading {
  font-weight: 300;
}
</style>


<script>
var faker = require('faker');
export default {
  name: 'blog',

  data() {
    return {
      title: 'Your Logo'
    }
  },

  computed: {
  },

  watch: {},

  mounted() {
    console.log('Faker ->', faker.name.findName())
  },

  methods: {
    returnAvatar() {
      return faker.image.avatar()
    }
  }
}
</script>
