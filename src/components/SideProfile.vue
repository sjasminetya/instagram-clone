<template>
  <v-app style="background: #e9edf2;">
    <div class="d-flex">
        <v-icon large color="black" class="icon">mdi-instagram</v-icon>
        <h1 class="instagram">Instagram</h1>
    </div>
    <v-avatar size="100" class="img-profile">
        <img src="../assets/profile.jpg" alt="" />
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
            <v-icon large class="active">home</v-icon>
            <h4 class="active">Feed</h4>
        </div>
        <div class="d-flex">
            <v-icon large>explore</v-icon>
            <h4>Explore</h4>
        </div>
        <div class="d-flex">
            <v-icon large>tag</v-icon>
            <h4>Trending Tags</h4>
        </div>
        <div class="d-flex">
            <v-icon large>check_circle_outline</v-icon>
            <h4>Top Post</h4>
        </div>
        <div class="d-flex">
            <v-icon large>perm_identity</v-icon>
            <h4>People</h4>
        </div>
        <div class="d-flex">
            <v-icon large>notifications_none</v-icon>
            <h4>Notification</h4>
        </div>
        <div class="d-flex">
            <v-icon large>near_me</v-icon>
            <h4>Direct</h4>
        </div>
        <div class="d-flex">
            <v-icon large>donut_small</v-icon>
            <h4>Stats</h4>
        </div>
        <div class="d-flex">
            <v-icon large>settings</v-icon>
            <h4>Settings</h4>
        </div>
    </div>
  </v-app>
</template>

<script>
export default {
  name: "SideProfile",
};
</script>

<style scoped>
.icon {
  margin-left: 20px;
}

.instagram {
  padding-left: 20px;
  font-family: 'Redressed', cursive;
}

.img-profile {
  border: 1px solid #ff003c;
  margin: 80px auto 20px auto;
  display: block;
}

.img-profile img {
  max-width: 100%;
  height: 100%;
  object-fit: cover;
  padding: 5px;
}

.detail-profile {
  text-align: center;
}

.social .social-title,
.social .social-sum {
  display: flex;
  margin: 40px 0px 20px 0px;
  justify-content: center;
}

.social h5 {
  padding-right: 30px;
}

.social .social-sum {
  margin: 0;
}

.social p {
  padding-right: 50px;
}

.category {
  margin: 60px 0px 0px 20px;
  padding-bottom: 20px;
  color: rgba(0,0,0,.5);
}

.category .active {
  color: #ff003c;
}

.category h4 {
  padding: 20px;
}
</style>
