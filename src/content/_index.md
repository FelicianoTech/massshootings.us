---
title: "Mass Shootings in the United States"
---

<script type="text/JavaScript">
	var lastDate = "2018-09-02";
	var curDate = new Date();
	var difference = Math.floor(( curDate - Date.parse( lastDate )) / 86400000);
</script>

<div class="metrics">
<div class="metric">
	<span class="number">245</span>
	<span class="label">this year</span>
</div>
<div class="metric">
	<span class="number"></span>
	<span class="label">days since<br />
	last incident</span>
</div>
</div>

<a class="twitter-share-button"
	href="https://twitter.com/share"
	data-text="There have been 245 mass shootings in the U.S. already this year! "
	data-hashtags="MarchForOurLives"
	data-url="https://massshootings.us"
	data-via="FelicianoTech"
	data-related="AMarch4OurLives">
Tweet</a>

[data source](http://www.gunviolencearchive.org/reports/mass-shooting)

<script type="text/JavaScript">
	$( "div.metric span.number" ).eq(1).html( difference );
</script>
