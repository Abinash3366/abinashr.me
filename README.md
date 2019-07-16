# abinashr.me
@media screen and (max-height: 450px) {
  .sidebar {padding-top: 15px;}
  .sidebar a {font-size: 18px;}
}   
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

* {
  box-sizing: border-box;
}

.bg-image {

  background-image: url("download.jpg");
  
  filter: blur(8px);
  -webkit-filter: blur(8px);
  

  height: 100%; 
  
 
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}


.bg-text {
  background-color: rgb(0,0,0);
  background-color: rgba(0,0,0, 0.4); 
  color: white;
  font-weight: bold;
  border: 3px solid #f1f1f1;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 2;
  width: 80%;
  padding: 20px;
  text-align: center;
}
</style>
</head>

<div id="mySidebar" class="sidebar">
        <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">×</a>
        <a href="index.html">Home</a>
        <a href="blog.html">Blog</a>
        <a href="blog.html">Tech Support</a>
        <a href="contact_us.html">Contact Us</a>
      </div>
      <script>
            function openNav() {
              document.getElementById("mySidebar").style.width = "250px";
              document.getElementById("main").style.marginLeft = "250px";
            }
            
            function closeNav() {
              document.getElementById("mySidebar").style.width = "0";
              document.getElementById("main").style.marginLeft= "0";
            }
            </script>
        
<body>

<div class="bg-image"></div>

<div class="bg-text">
  <h2>Under Construction</h2>
  <h1 style="font-size:50px">Still Under Construction</h1>
  <p>Construction Finishes in 2090</p>
  <button class="openbtn" onclick="openNav()">Back</button> 
</div>

</body>
</html>

