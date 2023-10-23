# Task-2-Video-Conferencing-Website
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Video Conferencing Website</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='style.css'>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300&family=Permanent+Marker&display=swap" rel="stylesheet">
</head>
<body>

    <main>

     


        <!-- <div id="users-list"></div> -->

        <h1 id="site-title">Aditya Video Conferencing Website</h1>
        <div id="join-wrapper">
            <input id="username" type="text" placeholder="Enter your name..." />
            <button id="join-btn">Join Stream</button>
        </div>
        <div id="user-streams" ></div>
        


        <!-- Wrapper for join button -->
        <div id="footer">
            <div class="icon-wrapper">
                <img class="control-icon" id="camera-btn" src="./assets/video.svg" />
                <p>Camera</p>
            </div>

            <div class="icon-wrapper">
                <img class="control-icon" id="mic-btn" src="./assets/microphone.svg" />
                <p>Mic</p>
            </div>

            <div class="icon-wrapper">
                <img class="control-icon" id="leave-btn" src="./assets/leave.svg" />
                <p>Leave</p>
            </div>
            
           
            
            
        </div>

    </main>

    <script src='script.js'></script>
</body>
</html>
