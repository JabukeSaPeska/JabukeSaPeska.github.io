---
layout: page
title: pages.apples_for_sale
permalink: /apples-for-sale/
---

<style type="text/css">
.apple-variety {
	margin-bottom: 36px;
}
.apple-variety > .flex-4:nth-of-type(1) {
	text-align: center;
}
.apple-variety > .flex-4:nth-of-type(1) + .flex-8 {
	display: flex;
	flex-direction: column;
	justify-content: center;
	padding: 0 1em;
	box-sizing: border-box;
}
.shadow-outline {
	box-shadow: 0 0 4px #000;
}
.apple-variety h3 {
	font-weight: bold;
	margin-bottom: 0;
	line-height: 1;
}
.apple-variety h3 a {
	color: #B22;
}
</style>

<div>
	<p>{% translate apple_varieties.intro_text %}</p>

	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/idared.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Idared">{% translate apple_varieties.idared_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/gloster.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/List_of_apple_cultivars">{% translate apple_varieties.gloster_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/jonagold.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Jonagold">{% translate apple_varieties.jonagold_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/golden_delicious.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Golden_Delicious">{% translate apple_varieties.golden_delicious_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/pink_lady.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Cripps_Pink">{% translate apple_varieties.pink_lady_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/mutsu.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Mutsu_(apple)">{% translate apple_varieties.mutsu_heading %}</a></h3>
		</div>
	</div>
	<div class="flex-row apple-variety">
		<div class="flex-4">
			<img src="/img/apple-varieties/granny_smith.jpg" class="shadow-outline">
		</div>
		<div class="flex-8">
			<h3><a href="https://en.wikipedia.org/wiki/Granny_Smith">{% translate apple_varieties.granny_smith_heading %}</a></h3>
		</div>
	</div>


	<h3>{% translate apple_varieties.industrial_heading %}</h3>

	<p>{% translate apple_varieties.industrial_below %}</p>
	
	<div class="flex-row apple-variety">
		<div class="flex-12">
			<img src="/img/apple-varieties/industrial1.jpg" class="shadow-outline">
		</div>
	</div>
</div>

