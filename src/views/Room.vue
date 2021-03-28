<template>
  <div class="room">
    <div id="participants-div">
        <div id="left">
            <p>6 viewers</p>
            <img alt="" src="../assets/room-participants.png" />
        </div>
        <div id="right">
            <p>Avengers 复联粉丝团</p>
            <img alt="" src="../assets/room-handcontrols.png" />
        </div>
    </div>
    <div id="video-div">
        <img alt="" src="../assets/room-video.png" />
        <div id="chat-div">
            <div id="chat">
                <img alt="" src="../assets/room-chat.png" />
            </div>
            <div id="message">
                <p>Message Avengers 复联粉丝团</p>
                <img alt="" src="../assets/room-icon-share.png" />
            </div>
        </div>
    </div>
  </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@600&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');

    #participants-div {
        width: 100%;
        height: 5%;
        background-color: #161a1a;
        display: flex;
        flex-direction: "row";
        justify-content: "space-between";
        padding-top: 20px;
        padding-bottom: 20px;
    }
    #participants-div #left{
        width: 138%;
        height: 5%;
        display: flex;
        flex-direction: "row";
        justify-content: "space-between";
    }
    #participants-div #right{
        width: 100%;
        height: 5%;
        gap: 15%;
        display: flex;
        flex-direction: "row";
        justify-content: "space-between";
    }
    #participants-div p {
        font-family: 'Poppins', sans-serif;
        font-size: 22;
        color: #FFFFFF;
        opacity: 42%;
        margin-top: auto;
        margin-bottom: auto;
    }
    #participants-div * {
        margin-left: 20px;
    }
    #video-div {
        width: 100%;
        height: 80%;
        background-color: #161a1a;
        display: flex;
        flex-direction: "row";
        justify-content: "space-between";
    }
    #video-div img {
        padding-left: 20px;
        padding-bottom: 21px;
        width: 72%;
    }
    #video-div #chat-div{
        margin-left: 20px;
        width: 25%;
        height: 100%;
    }
    #chat-div #chat {
        width: 100%;
        height: 65vh;
        border-radius: 6px;
    }
    #chat-div #chat img {
        width: 106%;
        margin-left: -20px;
    }
    #chat-div #message {
        display: flex;
        flex-direction: "row";
        justify-content: "space-between";
        gap: 25%;
        width: 100%;
        height: 8vh;
        border-radius: 6px;
        background-color: #3A3A3D;
        margin-top: 15px;
        padding-top: 18px;
        padding-left: 20px;
    }
    #chat-div #message p {
        font-family: 'Lato', sans-serif;
        font-size: 22;
        color: #FFFFFF;
        opacity: 20%;
    }
    #chat-div #message img {
        width: 40px;
        height: 43px;
        opacity: 40%;
    }
</style>