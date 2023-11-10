<!DOCTYPE html>
<html lang="en">
    
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Complete Responsive Personal Portfolio Website HTML CSS Javascript | Codeha1</title>

     <!----box icons-->
     <link href ='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

     <link rel="stylesheet" href="style.css"/>

     
</head>

<body>

    <!------header design----->
    <header class="header">
        <a href="#" class="logo">Aditi.<span class="animate"  style="--i:1;"></span></a>
       <!----<label for="check" class="icons">---->
        <i class='bx bx-menu' id="menu-icon"></i>
       
        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#education">Education</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
            
            <span class="active-nav"></span>
            <span class="animate"  style="--i:2;"></span></a>

        </nav>
    </header>

    <!-------home section design----------->
    <section class="home" id="home">
        <div class="home-content">
            <h1>Hi,I'm<br>ADITI SINGH....</br></h1>
            <div class="text-animate">
            </div>
          
             <div class="btn-box">
                <a href="#" class="btn">Hire Me</a>
                <a href="#" class="btn">Let's Talk</a>
             </div>
        </div>

        <div class="home-sci">
            <a href="#"><i class='bx bxl-facebook'></i></a>
            <a href="#"><i class='bx bxl-whatsapp' ></i></a>
            <a href="#"><i class='bx bxl-instagram' ></i></a>
            <a href="#"><i class='bx bxl-linkedin-square' ></i></a>
        </div>
        <div class="home-imgHover"></div>
    </section>

    <!------about section--------->
    <section class="about" id="about">
        <h2 class="heading">About <span>Me</span></h2>
        <div class="about-img">
            <img src="4653585d-8572-48e7-bafa-3fb3c16b8720.jpg">
        </div>

        <div class="about-content">
            <h3>Software Developer!!</h3>
            <p> I'm a passionate girl who is always enthusiastic and dedicated towards learning in a COMPUTER SCIENCE ENGINEERING.
                I have choosen a Btech in AIML field because I always wanted to know and understand about ROBOTICS and I am sure that in the
             upcoming years ROBOTICS is definitely going to be advance OUR INDIA. I am a girl who always loves to do coding.In all over my
             academics from my school life to college life I was always a "SCHOLAR GIRL" and got multiple CERTIFICATE OF ACHIEVEMENTS.
             </p>

             <div class="btn-box btns">
            <a href="#" class="btn">Read More</a>
             </div>
        </div>
    </section>

    <!-----------education section------------------->
<section class="education"  id="education">
    <h2 class="heading">My <span>Education</span></h2>

    <div class="education-row">
        <div class="education-column">
            <h3 class="title">Education</h3>

            <div class="education-box">
                <div class="education-content">
                    <div class="content">
                            <h3>Bachelor Degree- COMPUTER SCIENCE ENGINEERING from AIML</h3>
                            <P> I have been pursuing Btech in COMPUTER SCIENCE(AIML) from 'AXIS INSTITUTE OF TECHNOLOGY AND MANAGEMENT'
                                and did my schooling from 'DR.VIRENDRA SWARUP PUBLIC SCHOOL CANTT KANPUR' which was affiliate
                                from an ICSE BOARD and got 90% in INTERMEDIATE and 93% in HIGH SCHOOL.I secured first position 
                                in Sir RAMANUJAN MATHEMATICS COMPETITION.Moreover apart from studies I was very much interested in 
                                extra-curricular activities like Sports,Debate,Declamation,Extempore.</P>
                        </div>
                    </div>
                </div>
            </div>


    </div>
</section>

<!--------skills---------->
<section class="skills" id="skills"> 
    <h2 class="heading">My <span>Skills</span></h2>

    <div class="skills-row">
        <div class="skills-column">
            <h3 class="title">Coding Skills</h3>

            <div class="skills-box">
                <div class="skills-content">
                        <h3>HTML</h3>
                        <h3>CSS</h3>
                        <h3>Python</h3>
                        <h3>C</h3>
                        <h3>C++</h3>
        
                    </div>
                       
                    </div>
                </div>
            </div>
        </div>
        <div class="skills-column">
            <h3 class="title">Other Skills</h3>

            <div class="skills-box">
                <div class="skills-content">
                        <h3>Leadership</h3>
                        <h3>Communication</h3>
                        <h3>Time Management</h3>
                        <h3>Teamwork</h3>
                        <h3>Critical Thinking and Problem Solving</h3>
        
                    </div>
                       
                    </div>
                </div>
            </div>
        </div>



    </div>
</section>

<!----------CONTACT------------------------->
 <section class="contact" id="contact">
    <h2 class="heading">Contact <span>Details!!</span></h2>

    <form action="#">
        <div class="input-box">
            <div class="input-field">
                <input type="text"  placeholder="Full Name" required>
                <span class="focus"></span>
            </div>
            <div class="input-field">
                <input type="text"  placeholder="Email Address" required>
                <span class="focus"></span>
            </div>
            </div>

<div class="textarea-field">
    <textarea name="" id="" cols="30" rows="10" placeholder="Your Message" required></textarea>
    <span class="focus"></span>
</div>

<div class="btn-box btns">
    <button type="submit" class="btn">Submit</button>
</div>
    </form>
 </section>

 <!-----------footer design-------------->
 <footer class="footer">
    <div class="footer-text">
        <p>Copyright@ ADITI.Made with</p>
    </div>

    <div class="footer-iconTop">
        <a href="#"><i class='bx bx-up-arrow-alt'></i></a>
    </div>
 </footer>


    <script src="js/script.js"></script>
<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</body>
</html>

