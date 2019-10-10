
<!DOCTYPE html>
<html lang="vi" class="no-js">
<meta http-equiv="content-type" content="text/html;charset=UTF-8" />

<head>
	<!-- Document Settings -->
	<meta charset="UTF-8" />

	<!-- Page Meta -->
	<title>Ngủ thôi nào</title>
	<meta name="description" content="Ngủ thôi nào" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<!--Favicons-->
	<link rel="shortcut icon" href="images/favicon-phucnd.ico" type="image/x-icon">
	<!-- Styles -->
	<link href="https//fonts.googleapis.com/css?family=Open+Sans:400,400italic,700,700italic%7CRoboto+Slab:400,700" rel="stylesheet" type="text/css" />
	<link rel="stylesheet" type="text/css" media="all" href="https://dinhphuc.github.io/sleep/css/bootstrap.min.css" />
	<link rel="stylesheet" type="text/css" media="all" href="https://dinhphuc.github.io/sleep/css/style.css" />

	<!-- Scripts -->
	<script>(function (html) { html.className = html.className.replace(/\bno-js\b/, 'js') })(document.documentElement);</script>


</head>

<body>
	<div class="wrap">
		<main id="main" class="site-main">

			<!-- Front -->
			<div id="front" class="site-front">
				<div class="inner">

					<!-- Header -->
					<header class="site-header">
						<p class="site-logo fade-in"><img src="https://dinhphuc.github.io/sleep/images/logo.png" width="150" height="60"
								alt="InTime Logo" /></p>
						<h1 class="site-title screen-reader-text">Đi ngủ thôi</h1>
					</header>

					<section class="content">
						<h2 class="section-title">Ngủ thôi nào </h2>

						<!-- Countdown timer -->
						<div class="countdown-timer">
							<p class="subtitle">You will be the last thing I think of before I fall asleep and the first
								thing I think of when I wake up</p>

						</div>
						<div class="container">
							<div class="row">
								<div class="col">
									<label for="giờ">H (giờ)</label>
								</div>
								<div class="col">
									<label for="phút">M (phút)</label>
								</div>
								<div class="col">
									<label for="Chu kỳ">Chu kỳ</label>
								</div>
								<div class="col">
									<label for="Time Sleep">Time Sleep (M)</label>
								</div>
								<div class="col">
									<label for="none"></label>
								</div>

							</div>
							<div class="row">
								<div class="col">
									<div class="form-group">
										<input type="number" class="form-control" id="hour" min="0" max="23"
											placeholder="h">
									</div>
								</div>
								<div class="col">
									<div class="form-group">
										<input type="number" class="form-control" id="minutes" min="0" max="59"
											placeholder="m">
									</div>
								</div>
								<div class="col">
									<div class="form-group">
										<select class="form-control" id="timeCycle">
											<option>3</option>
											<option>4</option>
											<option selected>5</option>
											<option>6</option>
											<option>7</option>
											<option>8</option>
										</select>
									</div>
								</div>
								<div class="col">
									<div class="form-group">
										<input type="number" class="form-control" id="timeToSleep" min="0" max="59"
											value="15">
									</div>
								</div>
								<div class="col">
									<div class="form-group">
										<input type="button" class="btn btn-success" id="btnProcess" value="Tính Toán">
									</div>
								</div>

							</div>

							<div class="row" style="padding-top: 2rem">
								<div class="alert alert-success" role="alert" style="width: 100%;">
									<h4 class="alert-heading" style="margin-bottom: 10px">Well done!</h4>
									<p id="result" style="margin-bottom: 2px">

									</p>
								</div>
							</div>
							<div class="row" style="padding-top: 2rem">
								<div class="alert alert-success" role="alert" style="width: 100%;">
									<div class="row">
										<table class="table">
											<thead class="thead-dark">
												<tr>
													<th scope="col">#</th>
													<th scope="col">Bắt đầu</th>
													<th scope="col">Thức dậy</th>
													<th scope="col">Sleep Time</th>
													<th scope="col">Chu kỳ</th>
												</tr>
											</thead>
											<tbody id="renderSuggest">

											</tbody>
										</table>

									</div>

								</div>
							</div>

						</div>





						<!-- Social links -->
						<div class="social-links">
							<a href="https://www.facebook.com/seakBz.rua.IT" target="_blank"><i class="fa-facebook"
									aria-hidden="true"></i><span class="screen-reader-text">Facebook</span></a>
							<a href="https://twitter.com/BinzPhuc" target="_blank"><i class="fa-twitter"
									aria-hidden="true"></i><span class="screen-reader-text">Twitter</span></a>
							<a href="https://plus.google.com/" target="_blank"><i class="fa-google-plus"
									aria-hidden="true"></i><span class="screen-reader-text">Google+</span></a>
							<a href="https://www.instagram.com/dinhh.phuc/" target="_blank"><i class="fa-instagram"
									aria-hidden="true"></i><span class="screen-reader-text">Instagram</span></a>
							<a href="https://github.com/seakBz" target="_blank"><i class="fa-github"
									aria-hidden="true"></i><span class="screen-reader-text">Vimeo</span></a>
						</div>

					</section>

					<!-- Modal toggle -->
					<div class="modal-toggle">
						<span class="modal-note">Read More</span>
						<button id="modal-open"><span class="screen-reader-text">Open</span><span aria-hidden="true"
								class="icon-plus"></span></button>
					</div>

				</div><!-- .inner -->
			</div><!-- .site-front -->

			<!-- Modal (About Us) -->
			<div id="modal" class="site-modal">
				<div class="modal-scrollable">
					<div class="inner">

						<!-- Modal toggle -->
						<div class="modal-toggle">
							<button id="modal-close"><span class="screen-reader-text">Close</span><span
									aria-hidden="true" class="icon-plus"></span></button>
						</div>

						<section class="content">
							<h2 class="section-title">About me</h2>

							<!-- Columns -->
							<div class="row">
								<div class="one-half">
									<p>I'm Sauanla</p>
								</div>
								<div class="one-half">
									<h3><i class="fa-phone" aria-hidden="true"></i> Phone</h3>
									<p>Phone: (+84) 973 642 632 </p>
									<h3><i class="fa-envelope" aria-hidden="true"></i> Email</h3>
									<p>phucnd.zit@gmail.com</p>
									<h3><i class="fa-map-marker" aria-hidden="true"></i> Address</h3>
									<p>Pham Van Dong - Cau Giay - Ha Noi </p>
								</div>
							</div>

						</section>

					</div><!-- .inner -->
				</div><!-- .modal-scrollable -->
			</div><!-- .site-modal -->

		</main><!-- .site-main -->
	</div><!-- .wrap -->

	<!-- Background overlay -->
	<div class="overlay"></div>

	<!-- Loading... -->
	<div id="preload">
		<div id="preload-content">
			<div class="preload-spinner">
				<span class="bounce1"></span>
				<span class="bounce2"></span>
				<span class="bounce3"></span>
			</div>
			<div class="preload-text">Loading...</div>
		</div>
	</div>

	<!-- Scripts -->

	<script type="text/javascript" src="https://dinhphuc.github.io/sleep/js/jquery-1.12.4.min.js"></script>
	<script type="text/javascript" src="https://dinhphuc.github.io/sleep/js/bootstrap.min.js"></script>
	<script type="text/javascript" src="https://dinhphuc.github.io/sleep/js/plugins.js"></script>
	<script type="text/javascript" src="https://dinhphuc.github.io/sleep/js/scripts.js"></script>
	<script type="text/javascript" src="https://dinhphuc.github.io/sleep/js/sleepcaculator.js"></script>

</body>
 

</html>
