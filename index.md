<!DOCTYPE html>
<html lang="en" >

<head>
 	 <meta charset="UTF-8">
  	<title>V M I</title>
  	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">

 	<style>
      /* NOTE: The styles were added inline because Prefixfree needs access to your styles and they must be inlined if they are on local disk! */  
		@import url(https://fonts.googleapis.com/css?family=Roboto+Condensed);

		* {
		  box-sizing: border-box;
		  overflow: hidden;
		}

		body {
		  padding-top: 10em;
		  text-align: center;
		}

		.loader {
		  position: relative;
		  margin: auto;
		  width: 350px;
		  color: white;
		  font-family: "Roboto Condensed", sans-serif;
		  font-size: 250%;
		  background: linear-gradient(180deg, #222 0, #444 100%);
		  box-shadow: inset 0 5px 20px black;
		  text-shadow: 5px 5px 5px rgba(0,0,0,0.3);
		}

		.loader:after {
		  content: "";
		  display: table;
		  clear: both;
		}

		span {
		  float: left;
		  height: 100px;
		  line-height: 120px;
		  width: 50px;
		}

		.loader > span {
		  border-left: 1px solid #444;
		  border-right: 1px solid #222;
		}

		.covers {
		  position: absolute;
		  height: 100%;
		  width: 100%;
		}

		.covers span {
		  background: linear-gradient(180deg, white 0, #ddd 100%);
		  animation: up 2s infinite;
		}

		@keyframes up {
		  0%   { margin-bottom: 0; }
		  16%  { margin-bottom: 100%; height: 20px; }
		  50% { margin-bottom: 0; }
		  100% { margin-bottom: 0; }
		}

		.covers span:nth-child(2) { animation-delay: .142857s; }
		.covers span:nth-child(3) { animation-delay: .285714s; }
		.covers span:nth-child(4) { animation-delay: .428571s; }
		.covers span:nth-child(5) { animation-delay: .571428s; }
		.covers span:nth-child(6) { animation-delay: .714285s; }
		.covers span:nth-child(7) { animation-delay: .857142s; }

	</style>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>
	<meta http-equiv="refresh" content="3;url=https://abhishek477.github.io/VMS/examples/landing-page.html" />

</head>

<body style="background-color: black">

  	<div class="loader">
	  	<span>L</span>
	  	<span>O</span>
	  	<span>A</span>
	  	<span>D</span>
	  	<span>I</span>
	  	<span>N</span>
	  	<span>G</span>
		  
	  	<div class="covers">
		    <span></span>
		    <span></span>
		    <span></span>
		    <span></span>
		    <span></span>
		    <span></span>
		    <span></span>
  		</div>
	</div>
</body>

</html>