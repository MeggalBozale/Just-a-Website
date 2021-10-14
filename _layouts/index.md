
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
        <title>Website sketch</title>
    </head>
    <script>
    $(document).ready(function() {
    var path = window.location.pathname;
    if(path == '/homepage.html')
            $('#home').addClass('activeNavColor');
    else if(path == '/page1.html')
            $('#projects').addClass('activeNavColor');
    else if(path == '/page1.html')
            $('#social').addClass('activeNavColor');
    else if(path == '/page1.html')
            $('#about').addClass('activeNavColor');
    else if(path == '/page1.html')
            $('#contact').addClass('activeNavColor');
    });
    </script>
    <style>
        .activeNavColor
        {
            color:rgb(0,0,0);
        }
        .navbar
        {
            list-style-type: none;
            margin:0;
            padding:0;
            background-color:rgb(150, 200, 250);
            overflow:hidden;
            text-align:center;
            position:fixed;
            left:0px;
            top:0px;
            width:100%;
            height:50px;
            
            
        }
        .navbar li
        {
            float:left;
            
        }
        .navbar li a
        {
            display:block;
            padding: 15.3px 10px;
            margin:0px;
            background-color:rgb(140,190,240);
            text-align: inherit;
            font-family: sans-serif;
            color:rgb(255,255,255);
            text-decoration: none;
            
        }
        .navbar li a:hover
        {
            color:rgb(230,230,230);
        }
    </style>
    <body>
        <ul class="navbar">
            <li><a href="default.asp"><i id = "home" class="material-icons" >house</i></a></li>
            <li><a id = "projects" href="news.asp">Projects</a></li>
            <li><a id = "social" href="contact.asp">Social Media</a></li>
            <li><a id = "about" href="about.asp">About Me</a></li>
            <li><a id = "contact" href="contact.asp">Contact Me</a></li>
        </ul>
        <h1>WIP</h1>
    </body>
</html>
