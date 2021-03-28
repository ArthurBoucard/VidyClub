<template>
  <div class="home">
    <h3>Rooms from people you follow</h3>
    <img id="follow" src="../assets/profil_follow.png">
    <br><br><br>
    <img id="discover" src="../assets/discover.png">
    <br><br><br>
    <router-link to="/room">
      <div id="scrollable">
        <img id="continue" src="../assets/continue_watching.png">
      </div>
    </router-link>
    <br><br>
    <img id="title" src="../assets/room_netflix_title.png">
    <br><br><br><br>
    <div id="scrollable">
      <img id="netflix_room" src="../assets/netflix_room.png">
    </div>
    <br>
    <img id="title2" src="../assets/topic_title.png">
    <div id="scrollable">
      <router-link to="/topic">
        <img id="topic" src="../assets/topic.png">
      </router-link>
    </div>
  </div>
</template>

<style lang="scss">
  #home {
    text-align: left;
    h3 {
      font-size: 20px;
      color: #757878;
    }
    v-avatar {
      margin-right: 200px;
    }
  }
  #title {
    float: left;
    margin-left: 2px;
    width: 60%;
  }
  #title2 {
    margin-left: 40px;
    width: 8%;
  }
  #follow {
    margin-left: 20px;
    width: 110%;
  }
  #discover {
    margin-left: 20px;
    width: 100%;
  }
  #continue {
    margin-left: 20px;
    width: 110%;
  }
  #netflix_room {
    margin-left: 20px;
    width: 180%;
  }
  #topic {
    margin-left: 20px;
    width: 150%;
  }
  #scrollable {
    overflow: auto;
  }
</style>