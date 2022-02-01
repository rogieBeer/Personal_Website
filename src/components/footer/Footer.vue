<template>
    <div>
        <div v-if="$vuetify.breakpoint.xsOnly">
            <v-footer
                dark
                padless
                tile
            >
                <v-card
                    fluid
                    tile
                    flat
                    centre
                    class="text-center flex-fill"
                >
                <v-card-text>
                        <v-btn
                            v-for="icon in icons"
                            :key="icon"
                            class="mx-4 brown--text text--lighten-5"
                            icon
                        >
                        <v-icon size="24px">
                            {{ icon }}
                        </v-icon>
                        </v-btn>
                </v-card-text>

                <v-card-text class="pt-0 brown--text text--lighten-3">
                    Thanks for stopping by, this portfolio is currently under construction.
                </v-card-text>

                <v-divider></v-divider>

                <v-card-text class="brown--text text--lighten-5">
                    {{ new Date().getFullYear() }} — <strong>@rogiebeer</strong>
                </v-card-text>
                </v-card>
            </v-footer>
        </div>
        <div v-else>
            <v-footer
                dark
                padless
                tile
                app
            >
                <v-card
                    fluid
                    tile
                    flat
                    centre
                    class="text-center flex-fill"
                >
                <v-card-text>
                        <v-btn
                            icon
                            class="mx-4 brown--text text--lighten-5"
                            href="http://www.instagram.com/rogiebeer"
                        >
                            <v-icon size="24px">
                                mdi-instagram
                            </v-icon>
                        </v-btn>
                        <v-btn
                            icon
                            class="mx-4 brown--text text--lighten-5"
                            href="https://github.com/rogieBeer"
                        >
                            <v-icon size="24px">
                                mdi-github
                            </v-icon>
                        </v-btn>
                        <v-btn
                            icon
                            class="mx-4 brown--text text--lighten-5"
                            href="http://www.instagram.com/rogiebeer"
                        >
                            <v-icon size="24px">
                                mdi-email
                            </v-icon>
                        </v-btn>
                </v-card-text>

                <v-card-text class="pt-0 brown--text text--lighten-3">
                    Thanks for stopping by, this portfolio is currently under construction.
                </v-card-text>

                <v-divider></v-divider>

                <v-card-text class="brown--text text--lighten-5">
                    {{ new Date().getFullYear() }} — <strong>@rogiebeer</strong>
                </v-card-text>
                </v-card>
            </v-footer>
        </div>
    </div>
  
</template>

<script>
  export default {
    data: () => ({
      icons: [
        'mdi-github',
        'mdi-instagram',
        'mdi-email'
      ],
      links: [
          "https://github.com/rogieBeer",
          "http://www.instagram.com/rogiebeer",
          "http://www.instagram.com/rogiebeer"
      ]
    }),
  }
</script>
