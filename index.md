<html>
<head>
	<meta charset="utf-8">
	<title> module2 assignment </title>
	<style>
		
		*{
			box-sizing: border-box;
			margin: 0;
			padding: 5px;
		}
		h1{
			margin-bottom: 25px;
			text-align: center;
			font-size: 175%;
		}
		section{
		border: 2px solid black;
		background-color: lightblue;
		width: 90%;
		height: 205px;
		font-size: 16px;
		text-align: center;
		overflow: hidden;
		margin-right: auto;
                margin-left: auto;
		color: black;
		position: relative;	
		clear:left;
		float:left;
	}
	p1{
		width: 80px;
		height: 25px;
		padding: 0px 1px 2px 1px;
		border: 1px solid black;
		background-color: maroon;
		text-align: center;
		color: white;
		font-size: 125%;
		position: absolute;
		top: 0px;
		right: 0px;
		
	}
	p2{
		width: 80px;
		height: 25px;
		padding: 0px 1px 2px 1px;
		text-align: center;
		border: 1px solid black;
		background-color: green;
		color: white;
		margin-bottom: 2px;
		position: absolute;
		top: 0px;
		right: 0px;
		font-size: 125%;
	}
	p3{
		width: 80px;
		height: 25px;
		
		padding: 0px 1px 2px 1px;
		text-align: center;
		border: 1px solid black;
		background-color: pink;
		color: black;
		margin-bottom: 2px;
		position: absolute;
		top: 0px;
		right: 0px;
		font-size: 125%;
	}
		.row{
			width: 100%;
		}
		@media (min-width: 992px){
			.col-lg-4{
				width: 33.33%;
				float: left;
				}
			}
		@media(min-width:768px) and (max-width: 991px){
        	.col-md-6{
	       		width: 50%;
				float: left;
			}
		}
		@media(max-width: 767px){
			.col-sm-12{
				width: 100%;
				float:left;
			}
		}
	</style>
</head>
<body>
<h1> Our Menu</h1>
<div class="row">
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p1> chicken </p1> <div><br>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do euismod tempor incididunt ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat . Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div> </section> </div>
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p2> beef</p2> <div> <br>lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do euismod tempor incididunt ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. </div> </section> </div>
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p3> sushi </p3> <div> <br> lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do euismod tempor incididunt ut labore et dolore magna aliqua. ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat . Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div> </section> </div>
</div>
</body>
</html>
