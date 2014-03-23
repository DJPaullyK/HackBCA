HackBCA
=======
<!DOCTYPE html>
<!--HTML5 doctype-->
<html>

	<head>
		<meta charset="UTF-8">
		<link rel="stylesheet" type="text/css" href="jqm/jquery.mobile-min.css">
		<link rel="stylesheet" type="text/css" href="css/index_main.less.css" class="main-less">
		<title>Your New Application</title>
		<meta http-equiv="Content-type" content="text/html; charset=utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=0">
		<style type="text/css">
			/* Prevent copy paste for all elements except text fields */
			*  { -webkit-user-select:none; -webkit-tap-highlight-color:rgba(255, 255, 255, 0); }
			input, textarea  { -webkit-user-select:text; }
		</style>
		<script src="intelxdk.js"></script>
		<script type="text/javascript">
			/* This code is used to run as soon as Intel activates */
			var onDeviceReady=function(){
			//hide splash screen
			intel.xdk.device.hideSplashScreen();
			};
			document.addEventListener("intel.xdk.device.ready",onDeviceReady,false);
		</script>
		<script type="application/javascript" src="js/jquery.min.js"></script>
		<script type="application/javascript" src="jqm/jquery.mobile-min.js" data-ver="0"></script>
		<script type="application/javascript" src="sidebar/js/jquery.event.move.js"></script>
		<script type="application/javascript" src="sidebar/js/jquery.event.swipe.js"></script>
		<script type="application/javascript" src="sidebar/js/sidebar.js"></script>
		<script type="application/javascript" src="sidebar/js/swipe.js"></script>
		<script type="application/javascript" src="js/index_user_scripts.js"></script>
	</head>

	<body>
		<!-- content goes here-->
		<div class="uwrap">
			<div class="upage" id="home" data-role="page">
				<div class="upage-outer">
					<div data-role="header" class="container-group inner-element uib_w_2" data-uib="jquery_mobile/header" data-ver="0" data-theme="c">
						<h1>Home</h1>
						<div class="widget-container wrapping-col single-centered"></div>
						<div class="widget-container content-area horiz-area wrapping-col left"></div>
						<div class="widget-container content-area horiz-area wrapping-col right"></div>
					</div>
					<div class="upage-content" id="mainsub">

						<div class="grid grid-pad urow uib_row_1 row-height-1" data-uib="layout/row" data-ver="0">
							<div class="col uib_col_1 col-0_12-12" data-uib="layout/col" data-ver="0">
								<div class="widget-container content-area vertical-col">

									<div class="widget uib_w_10 ui-content no_wrap outset-margin d-margins" data-uib="jquery_mobile/listview" data-ver="0">
										<ul data-role="listview">
											<li class="widget uib_w_11" data-uib="jquery_mobile/listitem" data-ver="0" id="Home_Button" href="#mainpage" data-transition="fade"><span>Home</span>
											</li>
											<li class="widget uib_w_12" data-uib="jquery_mobile/listitem" data-ver="0" id="Leagues_Button"><span>Leagues</span>
											</li>
											<li class="widget uib_w_13" data-uib="jquery_mobile/listitem" data-ver="0" id="Settings_Button"><span>Settings</span>
											</li>
										</ul>
									</div><span class="uib_shim"></span>
								</div>
							</div>
							<span class="uib_shim"></span>
						</div>
					</div>
					<!-- /upage-content -->

				</div>
				<!-- /upage-outer -->

			</div>
			<div class="upage" id="NHL" data-role="page">
				<div class="upage-outer">
					<div data-role="header" class="container-group inner-element uib_w_19" data-uib="jquery_mobile/header" data-ver="0" data-theme="c">
						<h1>NHL</h1>
						<div class="widget-container wrapping-col single-centered"></div>
						<div class="widget-container content-area horiz-area wrapping-col left"></div>
						<div class="widget-container content-area horiz-area wrapping-col right"></div>
					</div>
					<div id="NHLsub" class="upage-content ">
					</div>
				</div>
				<!-- /upage-outer -->
			</div>

			<div class="upage" id="NBA" data-role="page">
				<div class="upage-outer">
					<div data-role="header" class="container-group inner-element uib_w_18" data-uib="jquery_mobile/header" data-ver="0" data-theme="c">
						<h1>NBA</h1>
						<div class="widget-container wrapping-col single-centered"></div>
						<div class="widget-container content-area horiz-area wrapping-col left"></div>
						<div class="widget-container content-area horiz-area wrapping-col right"></div>
					</div>

					<div id="NBAsub" class="upage-content ">
					</div>
				</div>
				<!-- /upage-outer -->
			</div>
			<div class="upage" id="settings" data-role="page">
				<div class="upage-outer">
					<div data-role="header" class="container-group inner-element uib_w_9" data-uib="jquery_mobile/header" data-ver="0" data-theme="c">
						<h1>Settings</h1>
						<div class="widget-container wrapping-col single-centered"></div>
						<div class="widget-container content-area horiz-area wrapping-col left"></div>
						<div class="widget-container content-area horiz-area wrapping-col right"></div>
					</div>
					<div id="settingssub" class="upage-content ">
					</div>
				</div>
				<!-- /upage-outer -->
			</div>
			<div class="upage" id="leagues" data-role="page">
				<div class="upage-outer">
					<div data-role="header" class="container-group inner-element uib_w_8" data-uib="jquery_mobile/header" data-ver="0" data-theme="c">
						<h1>Leagues</h1>
						<div class="widget-container wrapping-col single-centered"></div>
						<div class="widget-container content-area horiz-area wrapping-col left"></div>
						<div class="widget-container content-area horiz-area wrapping-col right"></div>
					</div>
					<div id="Leaguessub" class="upage-content ">

						<div class="grid grid-pad urow uib_row_2 row-height-2" data-uib="layout/row" data-ver="0">
							<div class="col uib_col_2 col-0_12-12" data-uib="layout/col" data-ver="0">
								<div class="widget-container content-area vertical-col">

									<div class="widget uib_w_14 ui-content no_wrap outset-margin d-margins" data-uib="jquery_mobile/listview" data-ver="0">
										<ul data-role="listview">
											<li class="widget uib_w_15" data-uib="jquery_mobile/listitem" data-ver="0" id="NBA_Button" href="#settings" data-transition="fade">
												<img src="http://7poundbag.com/wp-content/uploads/2012/11/nba-logo.jpg" class="ui-li-icon"><span>NBA</span>
											</li>
											<li class="widget uib_w_16" data-uib="jquery_mobile/listitem" data-ver="0" href="#NBA" data-transition="fade" id="NHL_Button">
												<img src="http://www.shermanreport.com/wp-content/uploads/2012/08/nhl-logo.jpg" class="ui-li-icon"><span>NHL</span>
											</li>
											<li class="widget uib_w_17" data-uib="jquery_mobile/listitem" data-ver="0" id="MLB_Button">
												<img src="http://www.hexanine.com/zeroside/wp-content/media/2010/04/mlb_logo_blog1.gif" class="ui-li-icon"><span>MLB</span>
											</li>
										</ul>
									</div>
									<span class="uib_shim"></span>
								</div>
							</div>
							<span class="uib_shim"></span>
						</div>
					</div>
				</div>
				<!-- /upage-outer -->
			</div>
			<!-- /upage -->

		</div>
		<!-- /uwrap -->
	</body>

</html>
