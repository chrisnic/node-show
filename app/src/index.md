<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0,  minimum-scale=1.0"> 

    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="icon" href="assets/img/favicon.ico">

    <title>Slideshow</title>

    <!-- Bootstrap core CSS -->
    <link href="assets/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="assets/css/main.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->

  </head>

  <body>

    <div id="controls-menu">

        <div class="hitbox"></div>

        <ul class="controls" >            

            <li>
                <a id="play-icon" data-action="play">
                    <span class="icon-play3"></span>
                    <span class="icon-pause2"></span>
                </a>
            </li>

            <li>
                <a id="speed-button" data-action="speed"> 
                    <span class="icon-power"></span>
                </a>
            </li>

            <li>
                <a data-action="fullscreen">
                    <span class="icon-enlarge"></span>
                    <span class="icon-shrink"></span>
                </a>
            </li>

            <li>
                <a data-action="home">
                    <span class="icon-home"></span>
                </a>
            </li>

            <li>
                <a id="lock-button" data-action="locktoggle"> 
                    <span class="icon-lock"></span>
                    <span class="icon-unlocked"></span>
                </a>
            </li>
            

            <li class="unlocked-only">
                <a id="add-button"  data-action="add"> 
                    <span class="icon-add-image"></span>
                </a>
            </li>

            <li class="unlocked-only" >
                <a id="comment-button"  data-action="comment"> 
                    <span class="icon-edit-comment"></span>
                    <span class="icon-edit-comment active-comment"></span>
                </a>
            </li>

            <li class="unlocked-only">
                <a id="remove-button" data-action="remove"> 
                    <span class="icon-bin"></span>
                    <span class="icon-bin active-bin"></span>
                </a>
            </li>            

            <li>
                <a data-action="close">
                    <span class="icon-up-arrow"></span>
                </a>
            </li>
        </ul>

    </div>

    <div id="container" class="drag" data-master="true">

        <div class="static-container"> 
            
        </div>
        
        <div id="header" class="header" data-x="0" data-y="0" /> </div>

        

    </div>

    <!-- jQuery 1.11.0 CDN + fallback -->
    <script src="assets/js/vendor/jquery-2.1.1.min.js"></script>

    <script src="/socket.io/socket.io.js"></script>
    
    <!-- build:remove:dist -->
    <script src="assets/js/src/plugins.js?v=5"></script>
    <script src="assets/js/src/main.js?v=5"></script>     
    <!-- /build -->

    <!-- build:remove:dev -->
    <script src="assets/js/script.min.js"></script>
    <!-- /build -->

   

  </body>
</html>
