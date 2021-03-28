<template>
  <div id="nav">
    <v-app-bar color="#0e1212" dark>
      <router-link to="/">
        <img src="../src/assets/vidyclub2.png" width="180px" />
      </router-link>
      <v-spacer> </v-spacer>
      <v-btn text rounded router-link to="/about"> Discovery </v-btn>
      <router-link to="/create">
        <img src="../src/assets/create.png" width="100px" />
      </router-link>
      <v-col style="padding-top: 30px" md="2" width="0px">
        <v-text-field
          outlined
          rounded
          dense
          solo
          single-line
          label="Search"
          prepend-inner-icon="mdi-magnify"
        ></v-text-field>
      </v-col>
      <router-link to="/profile">
        <img src="../src/assets/clara.png" width="50px" />
      </router-link>
      <v-btn text rounded router-link to="/profile"> Clara Xu </v-btn>
    </v-app-bar>
    <div style="padding-top: 15px"></div>
    <div id="home">
      <router-view />
    </div>
    <img id="footer" src="../src/assets/footer.png"/>
  </div>
</template>

<style lang="scss">
  #nav {
    padding: 10px;
    text-align: right;
    background-color: #0e1212;
  }
  #footer {
      width: 110%;
  }
</style>
