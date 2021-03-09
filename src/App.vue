<template>
  <v-app>
    <v-container fluid>
      <v-row>
        <v-col lg="3" style="border: 1px solid red" class="profile-side">
          <SideProfile />
        </v-col>
        <v-col lg="9"></v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
import SideProfile from './components/SideProfile'
export default {
  name: 'App',
  components: {
    SideProfile
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
  background: #fffdfe;
}
</style>