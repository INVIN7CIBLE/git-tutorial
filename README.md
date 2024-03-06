<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="Home.css">
    <title>Page</title>
</head>
<body>
    <main class="main">
        <div class="img">
          <img src="https://plus.unsplash.com/premium_photo-1668024966086-bd66ba04262f?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8bGFuZHNjYXBlfGVufDB8fDB8fHww" alt="TEXT HERE"></div>
        <nav class="nav">
          <ul>
            <li><a href=""><i class="fa fa-home"></i> <span>Home</span></a></li>
            <li><a href=""><i class="fa fa-user"></i> <span>About</span></a></li>
            <li><a href=""><i class="fa fa-certificate"></i> <span>Skills</span></a></li>
            <li><a href="p.html"><i class="fas fa-laptop-code"></i> <span>Portfolio</span></a></li>
            <li class="active"><a href="About.html"><i class="fas fa-address-card"></i> <span>Contacts</span></a></li>
            <li><a href="Skill.html"><i class="fa fa-download"></i> <span> CV</span></a></li>
          </ul>
        </nav>
      </main>   
      <div class="social">
        <a href="https://www.facebook.com/account"><i class="fab fa-facebook"></i></a>
        <a href="https://www.twitter.com/account"><i class="fab fa-twitter"></i></a>
        <a href="https://www.github.com/account"><i class="fab fa-github"></i></a>
        <a href="https://www.linked.com/in/account"><i class="fab fa-linkedin"></i></a>
        <a href="https://wa.me/phone number"><i class="fab fa-whatsapp"></i></a>
        <a href="mailyo:account@gmail.com"><i class="fa fa-at"></i></a>
      </div>
      <script>
        const allLi = document.querySelectorAll("li")

        allLi.forEach(li =>{
        li.addEventListener("click",(evt)=>{
        allLi.forEach(li=>{
            li.classList.remove("active")
        })
        evt.currentTarget.classList.add("active")
        })
        })
      </script>
</body>
</html>
