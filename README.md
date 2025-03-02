<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/e8eafd6834.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <ul id="sidemenu">
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <i class="fa-solid fa-circle-xmark" onclick="closemenu()"></i>
            </ul>
            <i class="fa-solid fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
            <p>Web Designer and Data Analyst</p>
            <h1>Hi, I'm <span>Amit Madavi</span><br>From Bharati Vidyapeeth<br>University</h1>
        </div>
    </div>
</div>
<!------------about---------->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/user.png.jpeg">
            </div>
            <div class="about-col-2">
                <h1> <class="sub-title">About Me</h1>
                <p>Hi, Myself Amit Madavi I am currently pursuing my B.Tech in Electronics and Communication Engineering, and I am in my 3rd year at Bharati Vidyapeeth University College Of Engineering Pune.
                 Throughout my academic journey, I have developed a strong foundation in the principles of electronics, communication systems. I am passionate about exploring emerging technologies, enhancing my problem-solving skills, and applying theoretical knowledge to practical projects.
                 Enthusiastic and passionate about technology and expanding my domain in this growing world, as well as extracting insights from data to drive business decisions.
                 When I'm not focused on my studies, I enjoy indulging in activities that help me grow both personally and professionally. Some of my hobbies include:
                 Sports: I actively participate in sports like Cricket, Vollyball, Badminton etc, which helps me develop teamwork, leadership, and strategic thinking.</p>

            <div class="tab-titles">
                <p class="tab-links active-link" onclick="opentab('Skills')">Skills</p>
                <p class="tab-links" onclick="opentab('Experience')">Experience</p>
                <p class="tab-links" onclick="opentab('Education')">Education</p>
            </div> 
            <div class="tab-contents active-tab" id="Skills">
                <ul>
                    <li><spam>Web Development</spam><br>Designing Web Interfaces</li>
                    <li><spam>SQL Data Analyst</spam><br>Quering and Maniulating Data Stored</li>
                    <li><spam>VLSI Design</spam><br>Designing and Development of Chips/ICs</li>
                    <li><spam>IOT</spam><br>Internet Of Things</li>
                </ul>
            </div>
            <div class="tab-contents" id="Experience">
                <ul>
                    <li><spam>Intern Trainee at Acmegrade</spam><br>Internet Of Things</li>
                    <li><spam>Intern Trainee at CodeAlpha</spam><br>Java Programming</li>
                    <li><spam>Trainee at Internshala</spam><br>VLSI Design</li>
                </ul>
            </div>
            <div class="tab-contents" id="Education">
                <ul>
                    <li><spam>Completed Schooling in 2020 with 72% </spam><br>From School of Scholars</li>
                    <li><spam>Completed 12th in 2022 with 86.67%</spam><br>From Mohsinbhai Zaweri Junior College Wadsa</li>
                    <li><spam>Persuing Btech From BVDU Pune</spam><br>Currntly in 3rd Year</li>
                </ul>
            </div>
            </div>
        </div>
    </div>
</div>
<!----------------sevices--------------->
<div id="services">
    <div class="container">
        <h1> <class="sub-title">My Services</h1>
        <div class="services-list">
             <div>
                <i class="fa-solid fa-globe"></i>
                <h2>Web Design</h2>
                <p>Web design services involve creating and maintaining websites with a focus on custom design, user experience (UX).
                   These services ensure a functional, visually appealing, and user-friendly online presence.</p>
                   <a href="#">Learn more</a>
             </div>
             <div>
                <i class="fa-solid fa-microchip"></i>
                <h2>VLSI Design</h2>
                <p>This services offer remote assistance in designing, simulating, and verifying integrated circuits.
                   These services include access to design tools, expert consultations, and cloud-based platforms</p>
                   <a href="#">Learn more</a>
             </div>
             <div>
                <i class="fa-solid fa-cloud"></i>
                <h2>Data Analyst</h2>
                <p>This collect, process, and analyze data to provide valuable insights for decision-making. 
                    They clean and organize data, identify trends or patterns, and create reports or dashboards to present findings.</p>
                   <a href="#">Learn more</a>
             </div>
        </div>
    </div>
</div>
<!------------portfolio---------->
<div id="portfolio">
      <div class="container">
        <h1> <class="sub-title">My Certifications</h1>
        <div class="certification-list">
        <div class="certifications">
            <img src="images/acmegrade.png">
            <div class="layer">
                <h3>Acmegrade</h3>
                <p>Internet Of Things</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        <div class="certifications">
            <img src="images/nptle.png">
            <div class="layer">
                <h3>NPTEL</h3>
                <p>Sensors Technologies: Physics,Fabrication, and Circuits</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        <div class="certifications">
            <img src="images/tata.png">
            <div class="layer">
                <h3>TATA (Forage)</h3>
                <p>Cybersecurity Analyst Job Simulation</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        <div class="certifications">
            <img src="images/internshala.png">
            <div class="layer">
                <h3>Internshala</h3>
                <p>SQL for Data Analytics</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        <div class="certifications">
            <img src="images/master.png">
            <div class="layer">
                <h3>Mastercard (Forage)</h3>
                <p>Cybersecurity Job Simulation</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        <div class="certifications">
            <img src="images/uniathene.png">
            <div class="layer">
                <h3>UniAthena</h3>
                <p>Basics of Pandas</p>
                <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
        </div>
        </div>
        </div>
        <a href="#" class="btn">See more</a>
      </div>
</div>
<!-------------contact------------>
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-solid fa-paper-plane"></i>amitmadavi534@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>8766793098</p>
                <div class="social-icons">
                    <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                    <a href=""><i class="fa-brands fa-twitter-square"></i></a>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                    <a href=""><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <a href="" class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="email" name="Email" placeholder="Your Email" required>
                    <textarea name="Message" row="6" placeholder="Your Message"></textarea>
                    <button type="Submit" class="btn btn2">Submit</button>
                </form>
                <span id="msg"></span>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>© 2025 Amit Madavi. All rights reserved.<br>Term of Services</p>
    </div>
</div>


<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
    
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
}

</script>
<script>

    var sidemenu = document.getElementById("sidemenu");

    function openmenu(){
        sidemenu.style.right = "0";
    }
    function closemenu(){
        sidemenu.style.right = "-230px";
    }
</script>
<script>
    const scriptURL = 'https://script.google.com/macros/s/AKfycbx5zrOnfo8xazKC6Norm3-tVG1GEAnrn9TnJlQQPmmSD_0SJgpPgfZr3kEj0s1WrqUD/exec'
    const form = document.forms['submit-to-google-sheet']
    const msg = document.getElementById("msg")
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => {
            msg.innerHTML = "Message Sent Successfully"
            setTimeout(function(){
                msg.innerHTML =""
            },5000)
            form.reset()
        })
        .catch(error => console.error('Error!', error.message))
    })
  </script>
</body>
</html>
