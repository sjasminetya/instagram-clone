<template>
  <v-app>
    <v-container fluid>
      <v-row>
        <v-col lg="3" style="border: 1px solid red" class="profile-side">
          <div class="d-flex">
            <v-icon large color="black" class="icon">mdi-instagram</v-icon>
            <h1 class="instagram">Instagram</h1>
          </div>
          <v-avatar size="100" class="img-profile">
            <img src="./assets/profile.jpg" alt="">
          </v-avatar>
          <div class="detail-profile">
            <h3>Emma Watson</h3>
            <p>New York, NY</p>
          </div>
          <div class="social">
            <div class="social-title">
              <h5>Post</h5>
              <h5>Followers</h5>
              <h5>Following</h5>
            </div>
            <div class="social-sum">
              <p>116</p>
              <p>48m</p>
              <p>48m</p>
            </div>
          </div>
          <div class="category">
            <div class="d-flex">
              <v-icon large color="black">home</v-icon>
              <h4>Feed</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">explore</v-icon>
              <h4>Explore</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">tag</v-icon>
              <h4>Trending Tags</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">check_circle_outline</v-icon>
              <h4>Top Post</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">perm_identity</v-icon>
              <h4>People</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">notifications_none</v-icon>
              <h4>Notification</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">near_me</v-icon>
              <h4>Direct</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">donut_small</v-icon>
              <h4>Stats</h4>
            </div>
            <div class="d-flex">
              <v-icon large color="black">settings</v-icon>
              <h4>Settings</h4>
            </div>
          </div>
        </v-col>
        <v-col lg="9"></v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  name: 'App'
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Redressed&family=Rubik:wght@400;500&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Rubik', sans-serif;
}

.profile-side {
  min-height: 100vh;
  background: #fffdfe;
}

.profile-side .icon {
  margin-left: 20px;
}

.profile-side .instagram {
  padding-left: 20px;
  font-family: 'Redressed', cursive;
}

.profile-side .img-profile {
  border: 1px solid red;
  margin: 80px auto 20px auto;
  display: block;
}

.profile-side .img-profile img {
  max-width: 100%;
  height: 100%;
  object-fit: cover;
  padding: 5px;
}

.profile-side .detail-profile {
  text-align: center;
}

.profile-side .social .social-title,
.profile-side .social .social-sum {
  display: flex;
  margin: 40px 0px 20px 0px;
  justify-content: center;
}

.profile-side .social h5 {
  padding-right: 30px;
}

.profile-side .social .social-sum {
  margin: 0;
}

.profile-side .social p {
  padding-right: 50px;
}

.profile-side .category {
  margin: 60px 0px 0px 20px;
  padding-bottom: 20px;
}

.profile-side .category h4 {
  padding: 20px;
}
</style>