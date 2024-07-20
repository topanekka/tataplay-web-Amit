
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TATAPLAY >> MTBTV</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <link rel="stylesheet" href="style.css">
  <link rel="shortcut icon" href="../image/Logo.png" type="image/x-icon">
  <style>
 body {
      font-family: 'Poppins', sans-serif;
      background-color: #111010;
      color: #F8F8F8;
      margin: 0;
      padding: 0;
    }
    .channel{
      margin-left:0px;
      font-size:0.8rem;
      padding:5px;
      
    }
    #channelName{
      font-size:0.8rem;
      color:#036264;
    }

    #logo{
      height:60px;
      margin:5px 0px 3px 5px;
    }
    #lan{
      font-size:.7rem;
    }
    #genre{
      font-size:.7rem;
      color:#52489f;
    }
    .player-container{
      display:block;
      padding:10px 5px;
    }
    /* telegram btn */
    .telegram-button{
    position: relative;
    display: inline-block;
    height: 30px;
    box-sizing: border-box;
    cursor: pointer;
    background-color: #0088cc;
    border-radius: 3px;
    padding: 3px 6px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 1rem;
    color: #FFF;
    text-decoration: none;
}

.telegram-button:hover{
    background-color: #007dbb;
}

.telegram-button:active{
    background-color: #026698;
}

.telegram-button i{
    display: inline-block;
    height: 1rem;
    width: 1.4rem;
    vertical-align: middle;
    margin-right: 2px;
    
    background: url('https://telegram.org/img/oauth/tg_button_small.png') no-repeat;
    background-size: contain;
}

.telegram-button span{
    display: inline-block;
    vertical-align: top;
}
    /* Player Container */
    #player{
      max-width: 900px;
      text-align: center;
      background-color: #000000d2;
      box-shadow: 0 4px 8px rgba(38, 92, 54, 0.6);
      border-radius: 8px;
      animation:0.5s ease-in-out;
      position: relative;
    }
     @media (min-width: 700px){
      .player-container{
      display:flex;
    }
    #channelName{
      font-size:0.8rem;
      color:#036264;
    }

    #logo{
      height:60px;
      margin:5px 0px 3px 5px;
    }
    #lan{
      font-size:.7rem;
    }
    #genre{
      font-size:.7rem;
      color:#52489f;
    }
      #player{
      max-width: 70%;
      margin-left:10px;
      text-align: center;
      background-color: #000000;
      box-shadow: 0 4px 8px rgba(38, 92, 54, 0.3);
      border-radius: 10px;
      animation:0.5s ease-in-out;
      position: relative;

     }
}
.jwplayer.jw-skin-myskin .jw-display-icon-container {
  border-style: solid;
  border-width: medium;
  border-radius: 50%;
  padding: 1em;
}

  </style>
  <!-- JW Player CDN -->
  <script src="https://content.jwplatform.com/libraries/SAHhwvZq.js"></script>
</head>
<body>

              <div class="player-container">
                    <div id="player"></div>
                <div class="channel">
                  <span><img id="logo" src="" alt="Logo :Loading..."></span>
                   <p id="channelName">Channel :Loading... </p>
                   <p id="lan">Language :Loading...</p>
                   <p id="genre">Category :Loading...</p>
                 <div>
                   <a class="telegram-button" href="https://t.me/allinonereborn" target="_blank">
                      <i></i>
                     <span>@MTBTV Join</span>
                    </a>
                    <a class="telegram-button" href="#">
                     <span>Thanks to toxicify</span>
                    </a>
                 </div>
                </div>
              </div>


              <script>
                const urlParams = new URLSearchParams(window.location.search);
                const channelId = urlParams.get("id");
                const streamUrl =  "https://mtbtv.rf.gd/tata/link_keys/manifest.php?id=" + channelId; 
                const licenseUrl = "https://mtbtv.rf.gd/tata/link_keys/getkeys.php?id=" + channelId;
                fetchLicenseData(licenseUrl)
                  .then((data) => {
                    document.getElementById('channelName').innerHTML="Channel : "+data.channel_name;
                    document.getElementById('channelName').style.color = "#d7dbd7";
                    document.getElementById('logo').src =data.logo;
                    document.getElementById('lan').innerHTML ="Language : "+data.channel_language;
                    document.getElementById('lan').style.color = "#036264";
                    document.getElementById('genre').innerHTML ="Category : "+data.genre;
                    document.getElementById('genre').style.color = "#52489f";

                    const playerConfig = {
                      file: streamUrl,
                      type: "dash",
                      autostart: true,
                      stretching: "",
                      mute: false,
                      logo:{
                        fil:data.logo,
                      },
                      skin: {
                        name: "netflix",
                      },
                      captions: {
                        color: "#FFF",
                        fontSize: 14,
                        backgroundOpacity: 0,
                        edgeStyle: "raised",
                      },
                      primary: "html5",                          
                      drm: {
                        clearkey: {
                          keyId: data.keyId,
                          key: data.key,
                        },
                      },
                    };
          
                    if (typeof data === "string" && data === "error 1") {
                      showNotice("Error fetching license data: " + data);
                    } else {
                      const playerInstance = jwplayer("player");
                      playerInstance.setup(playerConfig);
                    }
                  })
                  .catch((error) => {
                    console.error("Error fetching license data:", error);
                    showNotice("There is an error . please inform us in telegram.(error 2)");
                  });
          
                function fetchLicenseData(url) {
                  return fetch(url)
                    .then((response) => response.json())
                    .catch((error) => {
                      console.error("Error:", error);
                      throw error;
                    });
                }
          
                function showNotice(message) {
                  const noticeElement = document.createElement("div");
                  const noticeContent = document.createElement("div");
                  noticeContent.classList.add("notice");
                  noticeContent.textContent = message;
                  noticeElement.appendChild(noticeContent);
                  document.body.appendChild(noticeElement);
                }
          
                window.addEventListener("error", (event) => {
                  const noticeContainer = document.querySelector(".notice");
                  if (noticeContainer) {
                    noticeContainer.textContent =
                      "There is an error.(" + event.message + ")";
                  }
                });
              </script>
              
<script src="https://content.jwplatform.com/libraries/KB5zFt7A.js"></script>
  <script disable-devtool-auto src='https://cdn.jsdelivr.net/npm/disable-devtool@latest'></script>
 </body>
</html>

