<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Tea Recipe</title>
	<link rel="icon" href="tea.ico">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/ef4342f3da.js" crossorigin="anonymous"></script> <!--This is font awesome V5-->
	<link href="style.css" rel="stylesheet" />
  </head>

  <body>
	<div id="container">
		<header>
			<h1 class="font-rubik">How to make a cup of tea</h1>
			
			<img src="https://image.freepik.com/free-photo/cup-tea-chill-woman-lying-couch-holding-legs-coffee-table-drinking-hot-coffee-enjoying-morning-being-dreamy-relaxed-mood-girl-oversized-shirt-takes-break-home_176420-11905.jpg">

			<p>Tea is a British staple in nearly all households across Britain. Mostly it is drunk as a breakfast beverage with milk and sugar. Although in recent years it has become increasingly popular to drink healthy tea such as herbal tea, chamomile tea, green tea etc., which have many health benefits!</p>

		</header>
			
		<section onmouseover="ingredientsHover()" onmouseout="ingredientsNormal()">
			<h2 class="font-rubik"><i id="ingredients" class="fas fa-mug-hot"></i>Ingredients  </h2>
			<ul>
				<li>Tea Bag</li>
				<li>Water</li>
				<li>Milk - Dairy/Plant based (Optional)</li>
				<li>Sugar/Honey (Optional)</li>
			</ul>
		</section>
			
		<section onmouseover="prepHover()" onmouseout="prepNormal()">
			<h2 class="font-rubik"><i id="prep" class="far fa-comment-dots"></i>Preparation  </h2>
			<ol>
				<li>Fill your kettle with enough water to make a cup of tea for your sized cup, and boil.</li>
				<li>Meanwhile while the kettle is boiling place your tea bag into your cup and add in your desired amount of sugar or honey if you want to add some sweetness to your tea.</li>
				<li>Once the kettle has boiled, pour the water into the cup filling at least 3/4 of the cup. Depending on how much milk you like in your tea will determain how much water to pour in, as well as how much tea you want! </li>
				<li>Once the water is in, stir immediately to ensure the sugar/honey starts to disolve and then let sit for a minute or two to let the tea bag brew. <strong>This is the most crucial part to a cup of tea!</strong></li>
				<li>Using a spoon, press the tea bag against the inside of the cup to squeeze out the remaining tea water from the tea bag. Do this slightly higher in the cup, out of the water.</li>
				<li>Lastly pour in the milk, stir and enjoy!</li>
			</ol>
			
		</section>
		
			
		<footer>
			<p>&copy Copyright Jade 2022</p>
			<a href="https://icons8.com/icon/GxawOkApwr31/tea" target="_blank">Tea icon by Icons8</a> <!-- target="_blank" on a link will result in the link opening in another tab automatically -->
		</footer>
	</div>
	<script src="index.js"></script>
  </body>
</html>
