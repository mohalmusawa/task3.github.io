# Landingpage.github.io


<!doctype html>
<html>

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, maximum-scale=1">
	<title>Homepage</title>
	<link rel="icon" href="favicon.png" type="image/png">
	<link href="css/bootstrap.css" rel="stylesheet" type="text/css">
	<link href="style.css" rel="stylesheet" type="text/css">
	<link href="css/linecons.css" rel="stylesheet" type="text/css">
	<link href="css/font-awesome.css" rel="stylesheet" type="text/css">
	<link href="css/responsive.css" rel="stylesheet" type="text/css">
	<link href="css/animate.css" rel="stylesheet" type="text/css">

	<link href='https://fonts.googleapis.com/css?family=Lato:400,900,700,700italic,400italic,300italic,300,100italic,100,900italic' rel='stylesheet' type='text/css'>
	<link href='https://fonts.googleapis.com/css?family=Dosis:400,500,700,800,600,300,200' rel='stylesheet' type='text/css'>


	<script type="text/javascript" src="js/jquery.1.8.3.min.js"></script>
	<script type="text/javascript" src="js/bootstrap.js"></script>
	<script type="text/javascript" src="js/jquery-scrolltofixed.js"></script>
	<script type="text/javascript" src="js/jquery.easing.1.3.js"></script>
	<script type="text/javascript" src="js/jquery.isotope.js"></script>
	<script type="text/javascript" src="js/wow.js"></script>
	<script type="text/javascript" src="js/classie.js"></script>

	<script type="text/javascript">
		$(document).ready(function(e) {
			$('.res-nav_click').click(function() {
				$('ul.toggle').slideToggle(600)
			});

			$(document).ready(function() {
				$(window).bind('scroll', function() {
					if ($(window).scrollTop() > 0) {
						$('#header_outer').addClass('fixed');
					} else {
						$('#header_outer').removeClass('fixed');
					}
				});

			});


		});

		function resizeText() {
			var preferredWidth = 767;
			var displayWidth = window.innerWidth;
			var percentage = displayWidth / preferredWidth;
			var fontsizetitle = 25;
			var newFontSizeTitle = Math.floor(fontsizetitle * percentage);
			$(".divclass").css("font-size", newFontSizeTitle)
		}
	</script>
</head>

<body>

	<!--Header_section-->
	<header id="header_outer">
		<div class="container">
			<div class="header_section">
				<div class="logo"><a href="javascript:void(0)"><img src="img/logob.png" alt=""></a></div> 
				<nav class="nav" id="nav">
					<ul class="toggle">
						<li><a href="#top_content">Home</a></li>
						<li><a href="#service">Services</a></li>
						<li><a href="#work_outer">Work</a></li>
						<li><a href="#client_outer">Clients</a></li>
						<li><a href="#team">Team</a></li>
						<li><a href="#contact">Contact</a></li>
					</ul>
					<ul class="">
						<li><a href="#top_content">Home</a></li>
						<li><a href="#service">Services</a></li>
						<li><a href="#work_outer">Work</a></li>
						<li><a href="#client_outer">Clients</a></li>
						<li><a href="#team">Team</a></li>
						<li><a href="#contact">Contact</a></li>
					</ul>
				</nav>
				<a class="res-nav_click animated wobble wow" href="javascript:void(0)"><i class="fa-bars"></i></a> </div>
		</div>
	</header>
	<!--Header_section-->

	<!--Top_content-->
	<section id="top_content" class="top_cont_outer">
		<div class="top_cont_inner">
			<div class="container">
				<div class="top_content">
					<div class="row">
						<div class="col-lg-5 col-sm-7">
							<div class="top_left_cont flipInY wow animated">
								<h3>Effeciency &amp; Cost-effective!</h3>
								<h2>Maxsimizng Business communication efficieny &amp; Minmizing operational cost</h2>
								<p> By the use of the new evoloving Internt of Things (IOT) technology and the presense of wide netwrok coverage world-wide. The company is commited to help business achieving their objectives by provding a relaiable netwrok and communication services using the latest technologyical decives. </p>
								<a href="#service" class="learn_more2">Learn more</a> </div>
						</div>
						<div class="col-lg-7 col-sm-5"> </div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!--Top_content-->

	<!--Service-->
	<section id="service">
		<div class="container">
			<h2>Services</h2>
			<div class="service_area">
				<div class="row">
					<div class="col-lg-4">
						<div class="service_block">
							<div class="service_icon delay-03s animated wow  zoomIn"> <span><i class="fa-flash"></i></span> </div>
							<h3 class="animated fadeInUp wow">Sattelite Services</h3>
							<p class="animated fadeInDown wow">A World-Wide covearge of sattelite services which icludes either a dedicated 1:1 or shared 1:4/1:8/1:16 communication services for hard operation field implementation.</p>
						</div>
					</div>
					<div class="col-lg-4">
						<div class="service_block">
							<div class="service_icon delay-03s animated wow  zoomIn"> <span><i class="fa-flash"></i></span> </div>
							<h3 class="animated fadeInUp wow">IOT solutions</h3>
							<p class="animated fadeInDown wow">Installing &amp; Maitaining IOT based solutions from tempreture/Humdity montiroring to smart cities/project services while maintaining an excellent netwrok speed with less cost. Effeciency &amp; Cost-effective!</p>
						</div>
					</div>
					<div class="col-lg-4">
						<div class="service_block">
							<div class="service_icon icon3  delay-03s animated wow zoomIn"> <span><i class="fa-shield"></i></span> </div>
							<h3 class="animated fadeInUp wow">Security</h3>
							<p class="animated fadeInDown wow">All services are highly secured by all means of direct sattelite or netweork access.</p>
						</div>
					</div>
					<div class="col-lg-4">
						<div class="service_block">
							<div class="service_icon icon2  delay-03s animated wow zoomIn"> <span><i class="fa-comments"></i></span> </div> ## change
							<h3 class="animated fadeInUp wow">Support</h3>
							<p class="animated fadeInDown wow">24/7 customer support</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!--Service-->

	<section id="work_outer">
		<!--main-section-start-->
		<div class="top_cont_latest">
			<div class="container">
				<h2>Latest Work</h2>
				<div class="work_section">
					<div class="row">
						<div class="col-lg-6 col-sm-6 wow fadeInLeft delay-05s">
							<div class="service-list">
								<div class="service-list-col1"> <i class="icon-doc"></i> </div>
								<div class="service-list-col2">
									<h3>Dashboard</h3>
									<p>A fully intergated dashboard for services monitroing.</p>
								</div>
							</div>
							<div class="service-list">
								<div class="service-list-col1"> <i class="icon-comment"></i> </div>
								<div class="service-list-col2">
									<h3>24/7 support</h3>
									<p>24/7 customers support by phone or email.</p>
								</div>
							</div>
							<div class="service-list">
								<div class="service-list-col1"> <i class="icon-database"></i> </div>
								<div class="service-list-col2">
									<h3>Hosting & Storage</h3>
									<p>All information are hosted and storaged on a dedicated dashboard.</p>
								</div>
							</div>
							<div class="service-list">
								<div class="service-list-col1"> <i class="icon-cog"></i> </div>
								<div class="service-list-col2">
									<h3>Customization options</h3>
									<p>Customers are free to customize the speed, alert meassages, and readings at all time.</p>
								</div>
							</div>
							<div class="work_bottom"> <span>Ready to minmize you operational cost and maxsmise your effeicieny?</span> <a href="#contact" class="contact_btn">Contact Us</a> </div>
						</div>
						<figure class="col-lg-6 col-sm-6  text-right wow fadeInUp delay-02s"> </figure>
					</div>
				</div>
			</div>
			<!--<div class="work_pic"><img src="img/dashboard_pic.png" alt=""></div>-->
		</div>
	</section>
	<!--main-section-end-->

	

</section>

-->

	<section class="main-section" id="client_outer">
		<!--main-section client-part-start-->
		<h2>Satisfied Clients</h2>
		<div class="client_area ">
			<div class="client_section animated  fadeInUp wow">
				<div class="client_profile">
					<div class="client_profile_pic"><img src="img/client-pic1.jpg" alt=""></div>
					<h3>Tim cook</h3>
					<span>Tim Inc</span> </div>
				<div class="quote_section">
					<div class="quote_arrow"></div>
					<p><b><img src="img/quote_sign_left.png" alt=""></b> I run a maritime company and we have suffered with regards of network communication with many of our overseas ships and cruise. This company have made this exprience something from the past. Absolutely top services provider. <small><img src="img/quote_sign_right.png" alt=""></small>						</p>
				</div>
				<div class="clear"></div>
			</div>
			<div class="client_section animated  fadeInDown wow">
				<div class="client_profile flt">
					<div class="client_profile_pic"><img src="img/client-pic2.jpg" alt=""></div>
					<h3>Jim sears</h3>
					<span>Surrey University</span> </div>
				<div class="quote_section flt">
					<div class="quote_arrow2"></div>
					<p><b><img src="img/quote_sign_left.png" alt=""></b> It is not because I know the company's CEO. But, the company is a world-class in this business. <small><img src="img/quote_sign_right.png" alt=""></small>						</p>
				</div>
				<div class="clear"></div>
			</div>
		</div>
	</section>
	<!--main-section client-part-end-->

	<div class="c-logo-part">
		
	<section class="main-section team" id="team">
		<!--main-section team-start-->
		<div class="container">
			<h2>The Team</h2>
			<h6>Take a closer look into our amazing team. We won’t bite.</h6>
			<div class="team-leader-block clearfix">
				<div class="team-leader-box">
					<div class="team-leader wow fadeInDown delay-03s">
						<div class="team-leader-shadow"><a href="javascript:void(0)"></a></div>
						<img src="img/team-leader-pic1.jpg" alt="">
						<ul>
							<li><a href="javascript:void(0)" class="fa-twitter"></a></li>
							<li><a href="javascript:void(0)" class="fa-facebook"></a></li>
						</ul>
					</div>
					<h3 class="wow fadeInDown delay-03s">Mohammed</h3>
					<span class="wow fadeInDown delay-03s">Chief Executive Officer</span>
					
				</div>
				<div class="team-leader-box">
					<div class="team-leader  wow fadeInDown delay-06s">
						<div class="team-leader-shadow"><a href="javascript:void(0)"></a></div>
						<img src="img/team-leader-pic2.jpg" alt="">
						<ul>
							<li><a href="javascript:void(0)" class="fa-twitter"></a></li>
							<li><a href="javascript:void(0)" class="fa-facebook"></a></li>
						</ul>
					</div>
					<h3 class="wow fadeInDown delay-06s">Jim</h3>
					<span class="wow fadeInDown delay-06s">Advisor</span>
					
				</div>
				<div class="team-leader-box">
					<div class="team-leader wow fadeInDown delay-09s">
						<div class="team-leader-shadow"><a href="javascript:void(0)"></a></div>
						<img src="img/team-leader-pic3.jpg" alt="">
						<ul>
							<li><a href="javascript:void(0)" class="fa-twitter"></a></li>
							<li><a href="javascript:void(0)" class="fa-facebook"></a></li>
						</ul>
					</div>
					<h3 class="wow fadeInDown delay-09s">Trump</h3>
					<span class="wow fadeInDown delay-09s">Shareholder</span>
					
				</div>
			</div>
		</div>
	</section>
	<!--main-section team-end-->

	<section class="twitter-feed">
		<!--twitter-feed-->
		<div class="container  animated fadeInDown delay-07s wow">
			<div class="twitter_bird"><span><i class="fa-twitter"></i></span></div>
			<p> MyCompany is one of the leading company on the IOT and communication services. It was an honor to meet the company's team</p>
			<span>About 46 mins ago</span> </div>
	</section>
	<!--twitter-feed-end-->
	<footer class="footer_section" id="contact">
		<div class="container">
			<section class="main-section contact" id="contact">
				<div class="contact_section">
					<h2>Contact Us</h2>
					<div class="row">
						<div class="col-lg-4">
							<div class="contact_block">
								<div class="contact_block_icon rollIn animated wow"><span><i class="fa-home"></i></span></div>
								<span> UK, Surrey, Guildford, GU1 </span> </div>
						</div>
						<div class="col-lg-4">
							<div class="contact_block">
								<div class="contact_block_icon icon2 rollIn animated wow"><span><i class="fa-phone"></i></span></div>
								<span> 07719018524 </span> </div>
						</div>
						<div class="col-lg-4">
							<div class="contact_block">
								<div class="contact_block_icon icon3 rollIn animated wow"><span><i class="fa-pencil"></i></span></div>
								<span> <a href="mailto:moh.almusawa@gmail.com"> moh.almusawa@gmail.com</a> </span> </div>
						</div>
					</div>
				</div>
				<div class="row">
					<div class="col-lg-6 wow fadeInLeft">
						<div class="contact-info-box address clearfix">
							<h3>Don’t hesitate to get in tough!.</h3>
							<p>We welcome any questions to find our more and more about our services in any of the areas the company operate within.</p>
							<p>Any orders should also be sent to our CEO (Mohammed) for further discussions.</p>
						</div>
						<ul class="social-link">
							<li class="twitter animated bounceIn wow delay-02s"><a href="javascript:void(0)"><i class="fa-twitter"></i></a></li>
							<li class="facebook animated bounceIn wow delay-03s"><a href="javascript:void(0)"><i class="fa-facebook"></i></a></li>
				
						</ul>
					</div>
					<div class="col-lg-6 wow fadeInUp delay-06s">
						<div class="form">
							<div id="sendmessage">Your message has been sent. Thank you!</div>
							<div id="errormessage"></div>
							<form action="" method="post" role="form" class="contactForm">
								<div class="form-group">
									<input type="text" name="name" class="form-control input-text" id="name" placeholder="Your Name" data-rule="minlen:4" data-msg="Please enter at least 4 chars" />
									<div class="validation"></div>
								</div>
								<div class="form-group">
									<input type="email" class="form-control input-text" name="email" id="email" placeholder="Your Email" data-rule="email" data-msg="Please enter a valid email" />
									<div class="validation"></div>
								</div>
								<div class="form-group">
									<input type="text" class="form-control input-text" name="subject" id="subject" placeholder="Subject" data-rule="minlen:4" data-msg="Please enter at least 8 chars of subject" />
									<div class="validation"></div>
								</div>
								<div class="form-group">
									<textarea class="form-control" name="message" rows="5" data-rule="required" data-msg="Please write something for us" placeholder="Message"></textarea>
									<div class="validation"></div>
								</div>

								<button type="submit" class="btn input-btn">SEND MESSAGE</button>
							</form>
						</div>
					</div>
				</div>
			</section>
		</div>
		
	</footer>
	<script type="text/javascript">
		$(document).ready(function(e) {
			$('#header_outer').scrollToFixed();
			$('.res-nav_click').click(function() {
				$('.main-nav').slideToggle();
				return false

			});

		});
	</script>
	<script>
		wow = new WOW({
			animateClass: 'animated',
			offset: 100
		});
		wow.init();
		document.getElementById('').onclick = function() {
			var section = document.createElement('section');
			section.className = 'wow fadeInDown';
			section.className = 'wow shake';
			section.className = 'wow zoomIn';
			section.className = 'wow lightSpeedIn';
			this.parentNode.insertBefore(section, this);
		};
	</script>
	<script type="text/javascript">
		$(window).load(function() {

			$('a').bind('click', function(event) {
				var $anchor = $(this);

				$('html, body').stop().animate({
					scrollTop: $($anchor.attr('href')).offset().top - 91
				}, 1500, 'easeInOutExpo');
				/*
				if you don't want to use the easing effects:
				$('html, body').stop().animate({
					scrollTop: $($anchor.attr('href')).offset().top
				}, 1000);
				*/
				event.preventDefault();
			});
		})
	</script>

	<script type="text/javascript">
		jQuery(document).ready(function($) {
			// Portfolio Isotope
			var container = $('#portfolio-wrap');


			container.isotope({
				animationEngine: 'best-available',
				animationOptions: {
					duration: 200,
					queue: false
				},
				layoutMode: 'fitRows'
			});

			$('#filters a').click(function() {
				$('#filters a').removeClass('active');
				$(this).addClass('active');
				var selector = $(this).attr('data-filter');
				container.isotope({
					filter: selector
				});
				setProjects();
				return false;
			});


			function splitColumns() {
				var winWidth = $(window).width(),
					columnNumb = 1;


				if (winWidth > 1024) {
					columnNumb = 4;
				} else if (winWidth > 900) {
					columnNumb = 2;
				} else if (winWidth > 479) {
					columnNumb = 2;
				} else if (winWidth < 479) {
					columnNumb = 1;
				}

				return columnNumb;
			}

			function setColumns() {
				var winWidth = $(window).width(),
					columnNumb = splitColumns(),
					postWidth = Math.floor(winWidth / columnNumb);

				container.find('.portfolio-item').each(function() {
					$(this).css({
						width: postWidth + 'px'
					});
				});
			}

			function setProjects() {
				setColumns();
				container.isotope('reLayout');
			}

			container.imagesLoaded(function() {
				setColumns();
			});


			$(window).bind('resize', function() {
				setProjects();
			});

		});
		$(window).load(function() {
			jQuery('#all').click();
			return false;
		});
	</script>
	<script src="contactform/contactform.js"></script>

</body>
</html>
