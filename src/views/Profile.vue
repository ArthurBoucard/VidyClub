<template class="profile">
  <div id="container">
    <img id="head" alt="profile_head" src = "../assets/profile_name.png">
    <img id="setting" alt="profile_head" src = "../assets/profile_setting.png">
    
    <img id="TopRooms" alt="profile_head" src = "../assets/profile_rooms.png">

    <img id="room_info" alt="profile_head" src = "../assets/profile_info_room.png">
    <h1 id="title">Broadcasters I follow</h1>
    <h1 id="opa_title">in active rooms</h1>
    <img id="caster" alt="profile_head" src = "../assets/pro_caster.png">
    <h1 id="title">From my linked accounts</h1>
    <img id="account" alt="profile_head" src = "../assets/pro_account.png">
    <h1 id="title">Youtube rooms</h1>
    <img id="youtube" alt="profile_head" src = "../assets/pro_youtube1.png">
    <h1 id="title">Netflix rooms</h1>
    <img id="youtube" alt="profile_head" src = "../assets/pro_netflix.png">
    <h1 id="title">Disney+ rooms</h1>
    <img id="youtube" alt="profile_head" src = "../assets/pro_disney.png">

  </div>
</template>



<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap');

  #container {
    background-color:#161A1A;
  }
  #title {
    font-family: 'Poppins', sans-serif;
    float: left;
    margin-left: 30px;
    font-size: 32px;
    color: white;
    margin-bottom: 15px;
  }
  #opa_title {
    font-family: 'Poppins', sans-serif;
    opacity: 42%;
    float: left;
    margin-left: 30px;
    font-size: 32px;
    color: white;
    margin-bottom: 15px;
  }
  #head {
    float: left;
    margin-left: 30px;
    margin-top: 10px;
    width: 70%;
    margin-bottom: 30px;
  }
  #setting {
    float: right;
    margin-top: 25px;
    margin-right: 30px;
    width: 3%;
  }
  #TopRooms {
    margin-left: 20px;
    width: 110%;
  }
  #room_info {
    float: left;
    margin-left: 27px;
    width: 94%;
    margin-bottom: 50px;
  }
  #broadcast {
    width: 40%;
    float: left;
    margin-left: 27px;
    margin-bottom: 15px;
  }
  #caster {
    width: 95%;
    float: left;
    margin-left: 27px;
    margin-bottom: 50px;
  }
  #link {
    width: 30%;
    float: left;
    margin-left: 27px;
    margin-bottom: 15px;
    margin-right: 50%;
  }
  #account {
    float: left;
    margin-left: 30px;
    width: 50%;
    margin-bottom: 50px;
    margin-right: 50%;
  }
  #youtubeTi {
    float: left;
    margin-left: 30px;
    margin-bottom: 5px;
    width: 20%;
  }
  #youtube {
    margin-left: 30px;
    margin-bottom: 50px;
    width: 98%;
  }

</style>
