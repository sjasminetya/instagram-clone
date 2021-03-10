<template>
  <v-app>
    <v-container fluid>
      <v-row>
        <v-col lg="3" class="profile-side">
          <SideProfile />
        </v-col>
        <v-col lg="9" style="border: 1px solid red">
          <Header />
          <hr>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import Header from './components/Header'
import SideProfile from './components/SideProfile'
export default {
  name: 'App',
  components: {
    SideProfile,
    Header
  }
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
  background: #e9edf2;
}
</style>