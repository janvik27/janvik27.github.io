<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title> module2 assignment </title>
	<style>
		*{
			box-sizing: border-box;
			margin: 0;
			padding: 10px;
		}
		h1{
			margin-bottom: 25px;
			text-align: center;
		}
		section{
		border: 2px solid black;
		background-color: lightblue;
		width: 90%;
		height: 150px;
		text-align: justify;
		float: left;
		color: black;
		position: relative;	
		clear: left;
	}

	p1{
		width: 80px;
		height: 25px;
		margin: 0px;
		padding: 0px 2px 0px 2px;
		border: 1px solid black;
		background-color: maroon;
		text-align: center;
		color: white;
		
		position: absolute;
		top: 0px;
		right: 0px;

		
	}
	p2{
		width: 80px;
		height: 25px;
		margin: 0px;
		padding: 0px 2px 0px 2px;
		text-align: center;
		border: 1px solid black;
		background-color: green;
		color: white;
		margin-bottom: 2px;
		position: absolute;
		top: 0px;
		right: 0px;
	}
	p3{
		width: 80px;
		height: 25px;
		margin: 0px;
		padding: 0px 2px 0px 2px;
		text-align: center;
		border: 1px solid black;
		background-color: pink;
		color: black;
		margin-bottom: 2px;
		position: absolute;
		top: 0px;
		right: 0px;
	}

		.row{
			width: 100%;
		}
		@media(min-width: 992px){
			.col-lg-4{
				width: 33.33%;
				float: left;
			}
		}
		@media(max-width: 991px) and (min-width: 768px){
        	.col-md-6{
	       		width: 50%;
				float: left;
}
		}
		@media(max-width: 767px){
			.col-sm-12{
				width: 100%;
				float: left;
			}
		}
	</style>
</head>
<body>
<h1> Our Menu</h1>
<div class="row">
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p1> chicken </p1> <div><br> media queries allows you to group styles together and target them to devies based on some criteria. floating elements can produce very flexible layouts. floats are taln ou of normal document flow.</div> </section> </div>
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p2> beef</p2> <div> <br> media queries allows you to group styles together and target them to devies based on some criteria. floating elements can produce very flexible layouts. floats are taln ou of normal document flow. </div> </section> </div>
	<div class="col-lg-4 col-md-6 col-sm-12"> <section> <p3> sushi </p3> <div> <br> media queries allows you to group styles together and target them to devies based on some criteria. floating elements can produce very flexible layouts. floats are taln ou of normal document flow.</div> </section> </div>
</div>
</body>
</html>
