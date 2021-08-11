<h1>Flask App to predict % of drinks in a glass & Recommend food or drinks</h1>
<h2>Flask, Yolo-v5, Content Based & Collaborative Recommendation system</h2>
<p>This is our final capstone project for Computer Vision and Recommendation System. Here we have trained YOLOV5 Model to detect our custome objects.We trained our model to detect top of glass, level of drink and base of drink in a glass. Once these objects in image are detected we calculate the % by dividing the distance between <b>base to level</b>/<b>base to top</b>. If % of drink is more than 50% then system recommends food using collaborative filtering and if its below 50% it recommends beers using content based filtering.</p>
<img src="drinksless.png">
<img src="drinksmore.png">
<hr>
<h2>How We did it?</h2>
<p>We took picture of 3 Different types of drinks in 4 different types of glasses.
<img src="glassnliquid.jpg">
</p>
