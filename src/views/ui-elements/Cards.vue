<template>
  <v-container fluid grid-list-xl py-0>
    <v-layout row wrap>
      <v-flex xs12 md6>
        <v-card class="mb-30">
          <img src="/static/img/blog-1.jpg" alt="Card Image" class="img-responsive" />
          <v-card-title>
            <h3 class="headline text-primary">Blog post layout #1 with image</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ultrices tortor non quam feugiat pulvinar. Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Vestibulum aliquam gravida justo, ut rhoncus tellus malesuada nec. Fusce dignissim velit eget consequat congue....</p>
          </v-card-title>
          <v-card-actions>
            <v-btn class="btn-warning">Share</v-btn>
            <v-btn class="btn-primary">Explore</v-btn>
          </v-card-actions>
        </v-card>
        <div class="app-card">
          <div class="app-card-content">
            <div class="blog-thumb mb-3">
              <img src="/static/img/post-1.png" class="img-responsive" alt="blog-1" width="100%" />
            </div>
            <div class="blog-content mb-3">
              <h4>Where Can You Find Unique Myspace Layouts Nowadays</h4>
              <span class="small">11 Nov 2017 , By: Admin , 5 Comments </span>
            </div>
            <v-card-actions>
              <v-btn class="btn-success">Share</v-btn>
              <v-btn class="btn-danger">Explore</v-btn>
            </v-card-actions>
          </div>
        </div>
      </v-flex>
      <v-flex xs12 md6>
        <v-card class="mb-30">
          <v-card-media src="/static/img/blog-2.jpg" alt="Card Image" height="410">
            <v-container fill-height fluid>
              <v-layout fill-height>
                <v-flex xs12 text-xs-center flexbox white--text>
                  <span class="headline">Top 10 Australian beaches</span>
                </v-flex>
              </v-layout>
            </v-container>
          </v-card-media>
          <v-card-title primary-title>
            <h3 class="headline text-primary">Blog post layout #1 with image</h3>
            <p class="mb-0">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque ultrices tortor non quam feugiat pulvinar. Lorem ipsum dolor sit amet, consectetur
                adipiscing elit. Vestibulum aliquam gravida justo, ut rhoncus tellus malesuada nec. Fusce dignissim velit eget consequat congue....</p>
          </v-card-title>
          <v-card-actions>
            <v-btn class="btn-primary">Share</v-btn>
            <v-btn class="btn-danger">Explore</v-btn>
          </v-card-actions>
        </v-card>
        <v-card class="mb-30">
          <img src="/static/img/blog-3.jpg" alt="Card Image" class="img-responsive" />
          <v-card-title primary-title>
            <div>
              <div class="headline">Top western road trips</div>
              <span class="grey--text">1,000 miles of wonder</span>
            </div>
          </v-card-title>
          <v-card-actions>
            <v-btn color="secondary">Share</v-btn>
            <v-btn class="btn-info">Explore</v-btn>
            <v-spacer></v-spacer>
            <v-btn icon @click.native="show = !show">
              <v-icon>{{ show ? 'keyboard_arrow_down' : 'keyboard_arrow_up' }}</v-icon>
            </v-btn>
          </v-card-actions>
          <v-slide-y-transition>
            <v-card-text v-show="show">
              I'm a thing. But, like most politicians, he promised more than he could deliver. You won't have time for sleeping, soldier, not with all the bed making you'll be doing. Then we'll go with that data file! Hey, you add a one and two zeros to that or we walk! You're going to do his laundry? I've got to find a way to escape.
            </v-card-text>
          </v-slide-y-transition>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      show: false
    })
  }
</script>
