<template>
    <div>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
        <!-- navbar -->
        <nav class="navbar navbar-expand-lg fixed-top navbar-dark">
            <div class="container">
                <a :class="`navbar-brand logo-text page-scroll`" href="#header" style="margin-top: -20px">Richard Gonzales.</a>

                <button class="navbar-toggler p-0 border-0" type="button" data-toggle="offcanvas">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
                    <ul class="navbar-nav ml-auto" style="margin-top: -20px">
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#header">Home <span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#services">Services</a>
                        </li>
                        <!-- <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Drop</a>
                            <div class="dropdown-menu" aria-labelledby="dropdown01">
                                <a class="dropdown-item page-scroll" href="project.html">Project Details</a>
                                <div class="dropdown-divider"></div>
                                <a class="dropdown-item page-scroll" href="terms.html">Terms Conditions</a>
                                <div class="dropdown-divider"></div>
                                <a class="dropdown-item page-scroll" href="privacy.html">Privacy Policy</a>
                            </div>
                        </li> -->
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#contact">Contact</a>
                        </li>
                    </ul>
                    <span class="nav-item social-icons" style="margin-top: -15px">
                        <span class="fa-stack">
                            <a href="https://www.facebook.com/richard.gonzales.94695" target="_blank">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-facebook-f fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="https://github.com/rGonzales10" target="_blank">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-github fa-stack-1x"></i>
                            </a>
                        </span>
                    </span>
                </div>
            </div>
        </nav>


        <!-- Header -->
        <header id="header" class="header">
            <div class="container">
                <div class="row">
                    <div class="col-lg-6">
                        <div class="text-container">
							<h1 class="h1-large">I love to create beautiful and efficient websites</h1>
                            <a class="btn-solid-lg page-scroll" href="#about">Discover</a>
                            <a class="btn-outline-lg page-scroll" href="#contact"><i class="fas fa-user"></i>Contact Me</a>
                        </div>
                    </div>
                </div>
            </div>
        </header>


        <!-- About-->
        <div id="about" class="basic-1 bg-gray">
            <div class="container">
                <div class="row">
                    <div class="col-lg-4">
                        <div class="text-container first">
                            <h3>Hi there I'm Richard,</h3>
                            <p>And I love to create beautiful and efficient websites for my customers. I love going through the entire process with the customer from concept, to design and then development and launch</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container second">
                            <div class="time">2019 - PRESENT</div>
                            <h6>Freelance Web Developer</h6>
                            <p>Working happily on my own web projects</p>
                            <div class="time">2018 - 2019</div>
                            <h6>Lead Web Developer</h6>
                            <p>Beautiful project for a major digital agency</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container third">
                            <div class="time">2017 - 2018</div>
                            <h6>Senior Web Designer</h6>
                            <p>Inhouse web designer for ecommerce firm</p>
                            <div class="time">2016 - 2017</div>
                            <h6>Junior Web Designer</h6>
                            <p>Junior web designer for small web agency</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <!-- Services -->
        <div id="services" class="basic-2">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <h2 class="h2-heading">Offered services</h2>
                        <p class="p-heading">Web design and development have been my bread and butter for more than 5 years. During that time I've discovered that I can help startups and companies with the following services</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-4">
                        <div class="text-box services-offered">
                            <i class="fa-solid fa-gem"></i>
                            <h4>DESIGN</h4>
                            <p>Successful online projects start with good design. It establishes a solid foundation for future development and allows for long term growth</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-box services-offered">
                            <i class="fa-solid fa-code"></i>
                            <h4>DEVELOPMENT</h4>
                            <p>I can code my own designs or even use the customer's design as base. My focus is to generate clean code that's well structured for reliability</p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-box services-offered">
                            <i class="fa-solid fa-tv"></i>
                            <h4>BASIC SEO</h4>
                            <p>i can setup your project to use basic SEO principles which will push your project to the first page on search engines and save you ads money</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <!-- Details -->
        <!-- <div class="split">
            <div class="area-1">
            </div>
            <div class="area-2 bg-gray">
                <div class="container">    
                    <div class="row">
                        <div class="col-lg-12">
                            <div class="text-container">
                                <h2>Why Work With Me</h2>
                                <p>I am a great communicator and love to invest the necessary time to understand the customer's problem very well</p>
                                <h5>DESIGN TOOLS</h5>
                                <p>My favorite design tools are Photoshop and Illustrator but I can create designs in Figma, Sketch and Adobe XD too</p>
                                <h5>DEVELOPMENT SKILLS</h5>
                                <p>I am familiar and work on a daily basis with HTML, CSS, JavaScript, Bootstrap and other modern frameworks</p>
                                
                                <div class="icons-container">
                                    <img src="@/assets/images/details-icon-photoshop.png" alt="alternative">
                                    <img src="@/assets/images/details-icon-illustrator.png" alt="alternative">
                                    <img src="@/assets/images/details-icon-html.png" alt="alternative">
                                    <img src="@/assets/images/details-icon-css.png" alt="alternative">
                                    <img src="@/assets/images/details-icon-bootstrap.png" alt="alternative">
                                    <img src="@/assets/images/details-icon-javascript.png" alt="alternative">
                                </div>
                            </div> 

                        </div>
                    </div>
                </div>
            </div>
        </div> -->


        <!-- Projects -->
        <div id="projects" class="basic-3">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <h2 class="h2-heading">Delivered projects</h2>
                        <p class="p-heading">Listed below are some of the most representative projects I've worked on. They range from basic web design for presentation sites to advanced web development for online shops</p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-12">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/project-1.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Jumbotron, <strong>Project:</strong> web design for their corporate websites and landing pages for marketing campaigns <a class="blue" href="#">details</a></p>
                        </div>
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/project-2.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Carsrepo, <strong>Project:</strong> designed and developed modern platform for purchasing second hand cars online <a class="blue" href="#">details</a></p>
                        </div>
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/project-3.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Truevideo, <strong>Project:</strong> created a custom video editing and upload web app for this awesome team <a class="blue" href="#">details</a></p>
                        </div>
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/project-4.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Evolosim, <strong>Project:</strong> complete redesign of their corporate website and platform update for their online shop <a class="blue" href="#">details</a></p>
                        </div>
                    </div> 
                </div>
            </div>
        </div>


        <!-- Works -->
        <div class="basic-4">
            <div class="container">
                <div class="row">
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-1.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Zigoland, <strong>Project:</strong> started a new website from ground up for a new product <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-2.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Visodream, <strong>Project:</strong> developed a new forum for the Visodream community <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-3.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Primoday, <strong>Project:</strong> complete redesign of their corporate website and platform <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-4.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Nextlite, <strong>Project:</strong> created a custom video editing and upload web app <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-5.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Syncnow, <strong>Project:</strong> web design for their corporate websites and landing pages <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="text-container">
                            <div class="image-container">
                                <a href="project.html">
                                    <img class="img-fluid" src="@/assets/images/work-6.jpg" alt="alternative">
                                </a>
                            </div>
                            <p><strong>For:</strong> Shifter, <strong>Project:</strong> started a new website from ground up for a new product <a class="blue" href="project.html">details</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Testimonials -->
        <div class="cards-1">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <h2 class="h2-heading">A few words from people that chose to work with me</h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-12">
                        
                        <div class="card">
                            <div class="card-body">
                                <p class="testimonial-text">“Richard is a skilled developer which will do everything possible to deliver the project on time and I really appreciate that”</p>
                                <div class="details">
                                    <img src="@/assets/images/testimonial-1.jpg" alt="alternative">
                                    <div class="text">
                                        <div class="testimonial-author">Samantha Bloom</div>
                                        <div class="occupation">Team Leader - Syncnow</div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Card -->
                        <div class="card">
                            <div class="card-body">
                                <p class="testimonial-text">“Loved to work with Richard he's such an awesome developer with great attention to details. He also has a great eye for design”</p>
                                <div class="details">
                                    <img src="@/assets/images/testimonial-2.jpg" alt="alternative">
                                    <div class="text">
                                        <div class="testimonial-author">John Rowling</div>
                                        <div class="occupation">Marketing Manager - Nexlite</div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="card">
                            <div class="card-body">
                                <p class="testimonial-text">“So glad we started working with Richard. We've used many times his design and development skills for our inhouse online projects”</p>
                                <div class="details">
                                    <img src="@/assets/images/testimonial-3.jpg" alt="alternative">
                                    <div class="text">
                                        <div class="testimonial-author">Lana Smith</div>
                                        <div class="occupation">General Manager - Shifter</div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>

        <!-- Section Divider -->
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <hr class="section-divider">
                </div>
            </div>
        </div>


        <!-- Questions -->
        <div class="accordion-1">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <h2 class="h2-heading">Frequent questions</h2>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-12">

                        <div class="accordion" id="accordionExample">
                            <div class="card">
                                <div class="card-header" id="headingOne">
                                    <button class="btn btn-link btn-block text-left" type="button" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                        How can I contact you and quickly get a quote for my online project?
                                    </button>
                                </div>
                                <div id="collapseOne" class="collapse show" aria-labelledby="headingOne" data-parent="#accordionExample">
                                    <div class="card-body">
                                        The best way to reach me is through the contact form of by messaging me on my social media accounts. For a fast quote make sure your provide many project details
                                    </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingTwo">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                        Do you create designs from the ground up or you are using themes?
                                    </button>
                                </div>
                                <div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordionExample">
                                    <div class="card-body">
                                        The best way to reach me is through the contact form of by messaging me on my social media accounts. For a fast quote make sure your provide many project details
                                    </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingThree">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                        Will I receive any included maintenance or warranty after project delivery?
                                    </button>
                                </div>
                                <div id="collapseThree" class="collapse" aria-labelledby="headingThree" data-parent="#accordionExample">
                                    <div class="card-body">
                                        The best way to reach me is through the contact form of by messaging me on my social media accounts. For a fast quote make sure your provide many project details
                                    </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingFour">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                                        If something goes wrong with the project can I have my money back?
                                    </button>
                                </div>
                                <div id="collapseFour" class="collapse" aria-labelledby="headingFour" data-parent="#accordionExample">
                                    <div class="card-body">
                                        The best way to reach me is through the contact form of by messaging me on my social media accounts. For a fast quote make sure your provide many project details
                                    </div>
                                </div>
                            </div>
                            <div class="card">
                                <div class="card-header" id="headingFive">
                                    <button class="btn btn-link btn-block text-left collapsed" type="button" data-toggle="collapse" data-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                                        What's your preferred method of payment and do you need an advance?
                                    </button>
                                </div>
                                <div id="collapseFive" class="collapse" aria-labelledby="headingFive" data-parent="#accordionExample">
                                    <div class="card-body">
                                        The best way to reach me is through the contact form of by messaging me on my social media accounts. For a fast quote make sure your provide many project details
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
        </div>


        <!-- Contact -->
        <div id="contact" class="form-1 bg-gray">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <h2>Contact details</h2>
                        <p class="p-heading">For any type of online project please don't hesitate to get in touch with me. The fastest way is to send me your message thru this <a class="blue no-line" href="mailto:richardgonzales9797@gmail.com">email</a></p>
                    </div>
                </div>
                <div class="row">
                    <div class="col-lg-12">
                        
                        <!-- Contact Form -->
                        <form id="contactForm">
                            <div class="form-group">
                                <input type="text" class="form-control-input" id="cname" required>
                                <label class="label-control" for="cname">Name</label>
                            </div>
                            <div class="form-group">
                                <input type="email" class="form-control-input" id="cemail" required>
                                <label class="label-control" for="cemail">Email</label>
                            </div>
                            <div class="form-group">
                                <textarea class="form-control-textarea" id="cmessage" required></textarea>
                                <label class="label-control" for="cmessage">Project details</label>
                            </div>
                            <div class="form-group">
                                <button type="submit" class="form-control-submit-button">Submit</button>
                            </div>
                        </form>

                    </div>
                </div>
            </div>
        </div>


        <!-- Footer -->
        <div class="footer bg-gray">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="social-container">
                            <span class="fa-stack">
                                <a href="#your-link">
                                    <i class="fas fa-circle fa-stack-2x"></i>
                                    <i class="fab fa-facebook-f fa-stack-1x"></i>
                                </a>
                            </span>
                            <span class="fa-stack">
                                <a href="#your-link">
                                    <i class="fas fa-circle fa-stack-2x"></i>
                                    <i class="fab fa-twitter fa-stack-1x"></i>
                                </a>
                            </span>
                            <span class="fa-stack">
                                <a href="#your-link">
                                    <i class="fas fa-circle fa-stack-2x"></i>
                                    <i class="fab fa-pinterest-p fa-stack-1x"></i>
                                </a>
                            </span>
                            <span class="fa-stack">
                                <a href="#your-link">
                                    <i class="fas fa-circle fa-stack-2x"></i>
                                    <i class="fab fa-instagram fa-stack-1x"></i>
                                </a>
                            </span>
                            <span class="fa-stack">
                                <a href="#your-link">
                                    <i class="fas fa-circle fa-stack-2x"></i>
                                    <i class="fab fa-youtube fa-stack-1x"></i>
                                </a>
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </div>


        <!-- Copyright -->
        <div class="copyright bg-gray">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <p class="p-small">Copyright © <a class="no-line" target="_blank" href="https://www.facebook.com/richard.gonzales.94695">Richard Gonzales</a></p>
                    </div>
                </div>
            </div>

            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style>
body,
html {
    width: 100%;
	height: 100%;
    scroll-behavior: smooth;
}

#header {
    transition: .5s ease-in-out;
}

* {
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

body, p {
	color: #4d5055; 
	font: 400 1rem/1.625rem "Open Sans", sans-serif;
}

h1 {
	color: #24262a;
	font-weight: 700;
	font-size: 2.5rem;
	line-height: 3.25rem;
	font-family: "Poppins"
}

h2 {
	color: #24262a;
	font-weight: 700;
	font-size: 2rem;
	line-height: 2.5rem;
	font-family: "Poppins"
}

h3 {
	color: #24262a;
	font-weight: 700;
	font-size: 1.75rem;
	line-height: 2.25rem;
	font-family: "Poppins"
}

h4 {
	color: #24262a;
	font-weight: 700;
	font-size: 1.5rem;
	line-height: 2rem;
	font-family: "Poppins"
}

h5 {
	color: #24262a;
	font-weight: 700;
	font-size: 1.25rem;
	line-height: 1.625rem;
	font-family: "Poppins"
}

h6 {
	color: #24262a;
	font-weight: 700;
	font-size: 1rem;
	line-height: 1.375rem;
	font-family: "Poppins"
}

.p-large {
	font-size: 1.125rem;
	line-height: 1.75rem;
}

.p-small {
	font-size: 0.875rem;
	line-height: 1.5rem;
}

.testimonial-text {
	font-style: italic;
}

.testimonial-author {
	font-weight: 700;
	font-size: 1rem;
	line-height: 1.5rem;
}

.li-space-lg li {
	margin-bottom: 0.5rem;
}

a {
	color: #4d5055;
	text-decoration: underline;
}

a:hover {
	color: #4d5055;
	text-decoration: underline;
}

.no-line {
	text-decoration: none;
}

.no-line:hover {
	text-decoration: none;
}

.blue {
	color: #2259ec;
}

.bg-gray {
	background-color: #f7f9fb;
}

.section-divider {
	display: block;
	height: 1px;
	margin: 0;
	border: none;
	background-color: #d3dae2;
}

.btn-solid-reg {
	display: inline-block;
	padding: 1.375rem 2.25rem 1.375rem 2.25rem;
	border: 1px solid #0b36a8;
	background-color: #0b36a8;
	color: #ffffff;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	text-decoration: none;
	transition: all 0.2s;
}

.btn-solid-reg:hover {
	background-color: transparent;
	color: #0b36a8;
	text-decoration: none;
}

.btn-solid-lg {
	display: inline-block;
	padding: 1.625rem 2.625rem 1.625rem 2.625rem;
	border: 1px solid #0b36a8;
	background-color: #0b36a8;
	color: #ffffff;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	text-decoration: none;
	transition: all 0.2s;
}

.btn-solid-lg:hover {
	background-color: transparent;
	color: #0b36a8;
	text-decoration: none;
}

.btn-outline-reg {
	display: inline-block;
	padding: 1.375rem 2.25rem 1.375rem 2.25rem;
	border: 1px solid #24262a;
	background-color: transparent;
	color: #24262a;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	text-decoration: none;
	transition: all 0.2s;
}

.btn-outline-reg:hover {
	background-color: #24262a;
	color: #ffffff;
	text-decoration: none;
}

.btn-outline-lg {
	display: inline-block;
	padding: 1.625rem 2.625rem 1.625rem 2.625rem;
	border: 1px solid #24262a;
	background-color: transparent;
	color: #24262a;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	text-decoration: none;
	transition: all 0.2s;
}

.btn-outline-lg:hover {
	background-color: #24262a;
	color: #ffffff;
	text-decoration: none;
}

.btn-outline-sm {
	display: inline-block;
	padding: 1rem 1.5rem 1rem 1.5rem;
	border: 1px solid #24262a;
	background-color: transparent;
	color: #24262a;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	text-decoration: none;
	transition: all 0.2s;
}

.services-offered {
	text-align: center;
}

.services-offered i {
	color: #2259ec;
	font-size: 50px;
	margin-bottom: 10px;
}

.btn-outline-sm:hover {
	background-color: #24262a;
	color: #ffffff;
	text-decoration: none;
}

.form-group {
	position: relative;
	margin-bottom: 1.25rem;
}

.label-control {
	position: absolute;
	top: 0.875rem;
	left: 1.5rem;
	color: #7d838a;
	opacity: 1;
	font-size: 0.875rem;
	line-height: 1.375rem;
	cursor: text;
	transition: all 0.2s ease;
}

.form-control-input:focus + .label-control,
.form-control-input.notEmpty + .label-control,
.form-control-textarea:focus + .label-control,
.form-control-textarea.notEmpty + .label-control {
	top: 0.125rem;
	color: #4d5055;
	opacity: 1;
	font-size: 0.75rem;
	font-weight: 700;
}

.form-control-input,
.form-control-select {
	display: block;
	width: 100%;
	padding-top: 1.125rem;
	padding-bottom: 0.125rem;
	padding-left: 1.5rem;
	border: 1px solid #cbcbd1;
	background-color: #ffffff;
	color: #4d5055;
	font-size: 0.875rem;
	line-height: 1.875rem;
	transition: all 0.2s;
	-webkit-appearance: none;
}

.form-control-select {
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
	height: 3.25rem;
	color: #7d838a;
}

select {
    -webkit-appearance: none;
	-moz-appearance: none;
	-ms-appearance: none;
    -o-appearance: none;
    appearance: none;
    background-image: url('@/assets/images/down-arrow.png');
    background-position: 96% 50%;
    background-repeat: no-repeat;
    outline: none;
}

.form-control-textarea {
	display: block;
	width: 100%;
	height: 14rem;
	padding-top: 1.5rem;
	padding-left: 1.3125rem;
	border: 1px solid #cbcbd1;
	background-color: #ffffff;
	color: #4d5055;
	font-size: 0.875rem;
	line-height: 1.5rem;
	transition: all 0.2s;
}

.form-control-input:focus,
.form-control-select:focus,
.form-control-textarea:focus {
	border: 1px solid #a1a1a1;
	outline: none;
}

.form-control-input:hover,
.form-control-select:hover,
.form-control-textarea:hover {
	border: 1px solid #a1a1a1;
}

.checkbox {
	font-size: 0.75rem;
	line-height: 1.25rem;
}

input[type='checkbox'] {
	vertical-align: -10%;
	margin-right: 0.5rem;
}

.form-control-submit-button {
	display: inline-block;
	width: 100%;
	height: 3.25rem;
	border: 1px solid #0b36a8;
	border-radius: 32px;
	background-color: #0b36a8;
	color: #ffffff;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0;
	cursor: pointer;
	transition: all 0.2s;
}

.form-control-submit-button:hover {
	border: 1px solid #24262a;
	background-color: transparent;
	color: #24262a;
}

/*     Navigation     */
.navbar {
	background-color: #24262a !important;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0.875rem;
    padding: 10px 0;
	box-shadow: 0 1px 6px 0 rgba(0, 0, 0, 0.025);
}

.navbar .navbar-brand {
	padding-top: 0.125rem;
	padding-bottom: 0.125rem;
}

.navbar .logo-text {
	color: #ffffff;
	font-weight: 700;
	font-size: 1.875rem;
	line-height: 1rem;
	text-decoration: none;
}

.offcanvas-collapse {
	position: fixed;
	top: 3.25rem;
	bottom: 0;
	left: 100%;
	width: 100%;
	padding-right: 1rem;
	padding-left: 1rem;
	overflow-y: auto;
	visibility: hidden;
	background-color: #24262a;
	transition: visibility .3s ease-in-out, -webkit-transform .3s ease-in-out;
	transition: transform .3s ease-in-out, visibility .3s ease-in-out;
	transition: transform .3s ease-in-out, visibility .3s ease-in-out, -webkit-transform .3s ease-in-out;
}

.offcanvas-collapse.open {
	visibility: visible;
	-webkit-transform: translateX(-100%);
	transform: translateX(-100%);
}

.navbar .navbar-nav {
	margin-top: 0.75rem;
	margin-bottom: 0.5rem;
}

.navbar .nav-item .nav-link {
	padding-top: 0.625rem;
	padding-bottom: 0.625rem;
	color: #ffffff;
	text-decoration: none;
	transition: all 0.2s ease;
}

.navbar .nav-item.dropdown.show .nav-link,
.navbar .nav-item .nav-link:hover,
.navbar .nav-item .nav-link.active {
	color: #9c9ead;
}

/* Dropdown Menu */
.navbar .dropdown .dropdown-menu {
	animation: fadeDropdown 0.2s;
}

@keyframes fadeDropdown {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
	}
}

.navbar .dropdown-menu {
	margin-top: 0.5rem;
	margin-bottom: 0.5rem;
	border: none;
	background-color: #24262a;
}

.navbar .dropdown-item {
	padding-top: 0.5rem;
	padding-bottom: 0.5rem;
	color: #ffffff;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 0.875rem;
	text-decoration: none;
}

.navbar .dropdown-item:hover {
	background-color: #24262a;
	color: #9c9ead;
}

.navbar .dropdown-divider {
	width: 100%;
	height: 1px;
	margin: 0.5rem auto 0.5rem auto;
	border: none;
	background-color: #505050;
}

.navbar .fa-stack {
	width: 2em;
	margin-right: 0.25rem;
	font-size: 0.75rem;
}

.navbar .fa-stack-2x {
	color: #0b36a8;
	transition: all 0.2s ease;
}

.navbar .fa-stack-1x {
	color: #ffffff;
	transition: all 0.2s ease;
}

.navbar .fa-stack:hover .fa-stack-2x {
	color: #ffffff;
}

.navbar .fa-stack:hover .fa-stack-1x {
	color: #0b36a8;
}

.navbar .navbar-toggler {
	padding: 0;
	border: none;
	font-size: 1.25rem;
}

/* Header */
.header {
	padding-top: 7rem;
	padding-bottom: 5.5rem;
	background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('@/assets/images/bg.jpg') center center no-repeat;
	background-size: cover;
	background-color: rgb(66, 66, 66);
	background-blend-mode: luminosity;
	/* -moz-filter: url("data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\'><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0\'/></filter></svg>#grayscale");
	-o-filter: url("data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\'><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0\'/></filter></svg>#grayscale");
	-webkit-filter: grayscale(100%);
	filter: gray;
	filter: url("data:image/svg+xml;utf8,<svg xmlns=\'http://www.w3.org/2000/svg\'><filter id=\'grayscale\'><feColorMatrix type=\'matrix\' values=\'0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0.3333 0.3333 0.3333 0 0 0 0 0 1 0\'/></filter></svg>#grayscale"); */
	text-align: center;
}

.header .h1-large {
	margin-bottom: 1.75rem;
	color: #ffffff;
}

.header .btn-solid-lg:hover {
	border: 1px solid #ffffff;
	color: #ffffff;
}

.header .btn-outline-lg {
	padding: 1.625rem 1.625rem 1.625rem 1.625rem;
	border: none;
	color: #ffffff;
}

.header .btn-outline-lg:hover {
	background: transparent;
	color: #9c9ead;
	text-decoration: none;
}

.header .btn-outline-lg .fas {
	margin-right: 0.375rem;
}


/*****************/
/*     About     */
/*****************/
.basic-1 {
	padding-top: 7.75rem;
	padding-bottom: 5.25rem;
}

.basic-1 .text-container {
	margin-bottom: 3rem;
}

.basic-1 .time {
	margin-bottom: 0.5rem;
	color: #0b36a8;
	font-weight: 600;
	font-size: 0.875rem;
	line-height: 1.5rem;
	font-family: "Poppins";
}

.basic-1 h6 {
	margin-bottom: 0.125rem;
}
/*     Services     */
.basic-2 {
	padding-top: 7.75rem;
	padding-bottom: 5.25rem;
}

.basic-2 .h2-heading {
	margin-bottom: 0.75rem;
	text-align: center;
}

.basic-2 .p-heading {
	margin-bottom: 4rem;
	text-align: center;
}

.basic-2 .text-box {
	margin-bottom: 3rem;
	padding: 3.5rem 1rem 2.125rem 1rem;
	border: 1px solid #cfd7de;
}

.basic-2 .fas,
.basic-2 .far {
	margin-bottom: 1.75rem;
	color: #0b36a8;
	font-size: 3.5rem;
}

.basic-2 h4 {
	letter-spacing: 1px;
}

/*     Details     */
.split .area-1 {
	height: 430px;
	background: linear-gradient(to bottom right, rgba(25, 26, 29, 0.5), rgba(25, 26, 29, 0.5)), url('@/assets/images/details-background.jpg') center center no-repeat;
	background-size: cover;
}

.split .area-2 {
	padding-top: 7.75rem;
	padding-bottom: 7.75rem;
}

.split p {
	margin-bottom: 2.25rem;
}

.split .icons-container {
	margin-top: 3rem;
}

.split .icons-container img {
	width: 50px;
	margin-right: 0.625rem;
	margin-bottom: 0.75rem;
}

/*     Projects     */
.basic-3 {
	padding-top: 7.75rem;
	padding-bottom: 1rem;
}

.basic-3 .h2-heading {
	margin-bottom: 0.75rem;
	text-align: center;
}

.basic-3 .p-heading {
	margin-bottom: 4rem;
	text-align: center;
}

.basic-3 .text-container {
	margin-bottom: 4rem;
}

.basic-3 .image-container {
	margin-bottom: 1rem;
}

/* Hover Animation */
.basic-3 .image-container {
	overflow: hidden;
	margin-right: auto;
	margin-left: auto;
}

.basic-3 .image-container img {
	margin: 0;
	transition: all 0.2s;
}

.basic-3 .image-container:hover img {
	-moz-transform: scale(1.1);
	-webkit-transform: scale(1.1);
	transform: scale(1.1);
} 

/*     Works     */
.basic-4 {
	padding-bottom: 1rem;
}

.basic-4 .text-container {
	margin-bottom: 4rem;
}

.basic-4 .image-container {
	margin-bottom: 1rem;
}

/* Hover Animation */
.basic-4 .image-container {
	overflow: hidden;
	margin-right: auto;
	margin-left: auto;
}

.basic-4 .image-container img {
	margin: 0;
	transition: all 0.2s;
}

.basic-4 .image-container:hover img {
	-moz-transform: scale(1.15);
	-webkit-transform: scale(1.15);
	transform: scale(1.15);
} 

/*     Testimonials     */
.cards-1 {
	padding-top: 3rem;
	padding-bottom: 3.875rem;
}

.cards-1 .h2-heading {
	margin-bottom: 3rem;
	text-align: center;
}

.cards-1 .card {
	margin-bottom: 4rem;
	border: none;
}

.cards-1 .card-body {
	padding: 0;
	text-align: center;
}

.cards-1 .testimonial-text {
	margin-bottom: 1.625rem;
}

.cards-1 img {
	display: inline-block;
	width: 60px;
	margin-bottom: 0.875rem;
	border-radius: 50%;
}

.cards-1 .text {
	margin-top: 0.375rem;
}

.cards-1 .testimonial-author {
	color: #24262a;
}

.cards-1 .testimonial-author,
.cards-1 .occupation {
	font-size: 0.875rem;
	line-height: 1.375rem;
}

/*     Questions     */
.accordion-1 {
	padding-top: 7.75rem;
	padding-bottom: 6.75rem;
}

.accordion-1 .h2-heading {
	margin-bottom: 2.5rem;
	text-align: center;
}

.accordion-1 .card {
	margin-bottom: 1.75rem;
	border: none;
}

.accordion-1 .card-header {
	padding: 0;
	border: none;
	background-color: transparent;
}

.accordion-1 .card button {
	padding: 0;
	color: #24262a;
	font-weight: 600;
	font-size: 1.125rem;
	line-height: 1.75rem;
	font-family: 'Poppins';
}

.accordion-1 .card button:hover {
	text-decoration: none;
}

.accordion-1 .card button:before {
	float: left;
	margin-right: 0.625rem;
	font-family: 'Font Awesome 5 Free';
	font-weight: 900;
	content: "\f078";
	transition: all 0.2s;
}

.accordion-1 .card button.collapsed:before {
	-webkit-transform: rotate(180deg);
	-moz-transform: rotate(180deg);
	transform: rotate(180deg);
} 

.accordion-1 .card-body {
	padding: 0.75rem 1.5rem 0.5rem 1.5rem;
}

/*     Contact     */
.form-1 {
	padding-top: 7.75rem;
	padding-bottom: 7rem;
	text-align: center;
}

.form-1 .h2-heading {
	margin-bottom: 0.75rem;
	text-align: center;
}

.form-1 .p-heading {
	margin-bottom: 4rem;
}

/*     Footer     */
.footer {
	padding-top: 6.25rem;
	padding-bottom: 2rem;
	background-color: #24262a;
	text-align: center;
}

.footer a {
	text-decoration: none;
}

.footer .fa-stack {
	width: 2em;
	margin-bottom: 1.25rem;
	margin-right: 0.375rem;
	font-size: 1.5rem;
}

.footer .fa-stack .fa-stack-1x {
    color: #ffffff;
	transition: all 0.2s ease;
}

.footer .fa-stack .fa-stack-2x {
	color: #0b36a8;
	transition: all 0.2s ease;
}

.footer .fa-stack:hover .fa-stack-1x {
	color: #0b36a8;
}

.footer .fa-stack:hover .fa-stack-2x {
    color: #ffffff;
}

/*     Copyright     */
.copyright {
	padding-top: 1rem;
	padding-bottom: 1rem;
	background-color: #24262a;
	text-align: center;
}

.copyright .p-small {
	color: #9da6ac;
	text-align: center;
}

.copyright a {
	color: #9da6ac;
}


/*     Back To Top Button     */
a.back-to-top {
	position: fixed;
	z-index: 999;
	right: 12px;
	bottom: 12px;
	display: none;
	width: 42px;
	height: 42px;
	border-radius: 30px;
	background: #3a424d url("@/assets/images/up-arrow.png") no-repeat center 47%;
	background-size: 18px 18px;
	text-indent: -9999px;
}

a:hover.back-to-top {
	background-color: #0b36a8;
}

.ex-header {
	padding-top: 8.5rem;
	padding-bottom: 4rem;
	background-color: #24262a;
}

.ex-header h1 {
	color: #ffffff;
}

.ex-basic-1 .list-unstyled .fas {
	font-size: 0.375rem;
	line-height: 1.625rem;
}

.ex-basic-1 .list-unstyled .media-body {
	margin-left: 0.5rem;
}

.ex-basic-1 .text-box {
	padding: 1.25rem 1.25rem 0.5rem 1.25rem;
	background-color: #f7f9fb;
}

.ex-cards-1 .card {
	border: none;
	background-color: transparent;
}

.ex-cards-1 .card .fa-stack {
	width: 2em;
	font-size: 1.125rem;
}

.ex-cards-1 .card .fa-stack-2x {
	color: #0b36a8;
}

.ex-cards-1 .card .fa-stack-1x {
	color: #ffffff;
	font-weight: 700;
	line-height: 2.125rem;
}

.ex-cards-1 .card .list-unstyled .media-body {
	margin-left: 0.75rem;
}

.ex-cards-1 .card .list-unstyled .media-body h5 {
	margin-top: 0.125rem;
	margin-bottom: 0.375rem;
}

/*     Media Queries     */
/* Min-width 768px */
@media (min-width: 768px) {
	.header {
		padding-top: 11rem;
		padding-bottom: 9rem;
	}
	.basic-2 .text-box {
		padding-right: 2.125rem;
		padding-left: 2.125rem;
	}

	/* Extra Pages */
	.ex-basic-1 .text-box {
		padding: 1.75rem 2rem 0.875rem 2rem;
	}
}


/* Min-width 992px */
@media (min-width: 992px) {
	.h2-heading {
		width: 35.25rem;
		margin-right: auto;
		margin-left: auto;
	}

	.p-heading {
		width: 46rem;
		margin-right: auto;
		margin-left: auto;
	}


	/* Navigation */
	.navbar {
		padding-top: 1.75rem;
		background-color: transparent;
		box-shadow: none;
		transition: all 0.2s;
	}

	.navbar.top-nav-collapse {
		padding-top: 0.5rem;
		padding-top: 0.5rem;
		background-color: #24262a;
		box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.025);
	}

	.offcanvas-collapse {
		position: static;
		top: auto;
		bottom: auto;
		left: auto;
		width: auto;
		padding-right: 0;
		padding-left: 0;
		background-color: transparent;
		overflow-y: visible;
		visibility: visible;
	}

	.offcanvas-collapse.open {
		-webkit-transform: none;
		transform: none;
	}

	.navbar .navbar-nav {
		margin-top: 0;
		margin-bottom: 0;
	}
	
	.navbar .nav-item .nav-link {
		padding-right: 0.625rem;
		padding-left: 0.625rem;
	}

	.navbar .dropdown-menu {
		margin-top: 0.25rem;
		box-shadow: 0 3px 3px 1px rgba(0, 0, 0, 0.08);
	}

	.navbar .dropdown-divider {
		width: 90%;
	}

	.navbar .social-icons {
		margin-left: 0.5rem;
	}
	
	.navbar .fa-stack {
		margin-right: 0;
		margin-left: 0.25rem;
	}

	.header {
		padding-top: 15rem;
		padding-bottom: 14rem;
		text-align: left;
	}

	.split {
		height: 760px;
	}
	
	.split .area-1 {
		height: 100%;
		width: 50%;
		display: inline-block;
	}
	
	.split .area-2 {
		height: 100%;
		width: 50%;
		display: inline-block;
		vertical-align: top;
	}

	.split .text-container {
		width: 400px;
		/* margin-left: 3rem; */
	}

	.cards-1 .card {
		display: inline-block;
		width: 290px;
		vertical-align: top;
	}

	.cards-1 .card:nth-of-type(3n+2) {
		margin-right: 1.5rem;
		margin-left: 1.5rem;
	}

	.cards-1 .card-body {
		text-align: left;
	}

	.cards-1 .details {
		display: flex;
		align-items: flex-start;
	}
	
	.cards-1 .details .text {
		flex-direction: column;
	}
	
	.cards-1 .details img {
		margin-right: 1.125rem;
	}
	.accordion-1 .accordion {
		width: 730px;
		margin-right: auto;
		margin-left: auto;
	}


	.form-1 form {
		width: 790px;
		margin-right: auto;
		margin-left: auto;
	}


	.ex-cards-1 .card {
		display: inline-block;
		width: 296px;
		vertical-align: top;
	}

	.ex-cards-1 .card:nth-of-type(3n+2) {
		margin-right: 1rem;
		margin-left: 1rem;
	}
}


/* Min-width 1200px */
@media (min-width: 1200px) {
	.h1-large {
		font-size: 3.75rem;
		line-height: 4.625rem;
	}

	.navbar .container {
		max-width: 1330px;
	}

	.header {
		padding-top: 18.25rem;
		padding-bottom: 17.25rem;
	}

	.basic-1 .text-container.first {
		margin-right: 2rem;
	}

	.basic-1 .text-container.second {
		margin-right: 1rem;
		margin-left: 1rem;
	}

	.basic-1 .text-container.third {
		margin-left: 2rem;
	}

	.split {
		height: 700px;
	}

	.split .text-container {
		width: 460px;
		margin-left: 5rem;
	}

	.cards-1 .card {
		width: 338px;
	}
	
	.cards-1 .card:nth-of-type(3n+2) {
		margin-right: 2.625rem;
		margin-left: 2.625rem;
	}
	
	.ex-cards-1 .card {
		width: 336px;
	}

	.ex-cards-1 .card:nth-of-type(3n+2) {
		margin-right: 2.875rem;
		margin-left: 2.875rem;
	}
}

</style>