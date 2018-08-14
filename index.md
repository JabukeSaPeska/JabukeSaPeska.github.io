---
layout: default
permalink: /
---

<style type="text/css">
.wrapper {
	max-width: 100%;
	margin-left: 0;
	margin-right: 0;
	padding-left: 0;
	padding-right: 0;
}
.page-content {
	/*padding-top: 0;*/
}
.wrapper {
	padding-top: 0;
}
.horbox {
	display: flex;
	flex-direction: column;
	justify-content: center;
	min-height: 320px;
	padding: 1em;
	color: #fff;
	background-size: cover;
	background-position: center;
	text-shadow: 0 0 4px #000;
}
a.horbox {
	color: #fff;
	flex-direction: row;
	transition: opacity 0.4s;
}
a.horbox:hover {
	text-decoration: none;
	opacity: 0.9;
}
.horbox-text {
	background: rgba(99, 22, 22, 0.5);
	padding: 1em;
	border-radius: 40px;
	box-shadow: 0 0 1px black;
	box-sizing: border-box;
}
.horbox .flex-row {
	width: 100%;
}
.horbox div[class*="flex-"] {
	align-items: center;
}
.horbox h3 {
	font-size: 2em;
	font-weight: bold;
	text-transform: uppercase;
	padding: 0em 0.5em;
}
.horbox .description {
	font-weight: bold;
}
.horbox .description + .description {
	margin-top: 1em;
}
.roundimg {
	background-position: center;
	background-size: cover;
	border-radius: 50%;
	width: 128px;
	height: 128px;
	margin: 0 auto;
	box-shadow: 0 0 2px #000;
}

.horbox .description[class*="lang-"] {
	padding-left: 80px;
	background-position: left center;
	background-size: 70px 39px;
	background-repeat: no-repeat;
}

</style>

<div class="horbox" style="background-image:url(/img/photos/applebin.jpg)">
	<div class="row">
		<div class="horbox-text">
			<h3 class="text-center">Jabuke sa Peska</h3>
			<div class="description lang-en">Welcome to our farm. We offer a wide selection of apples. Due to the unique micro-climate our apples have a distinct taste with attractive colors. Because of the control storage technology, apples are available from September to May.</div>
			<div class="description lang-hu">Szeretettel köszöntjük web oldalunkon. Évtizedek óta termeljük es kináljuk almáinkat eladásra. Az ideális mikro-klimának és az extenziv termesztési technologiának köszönve almáink különlegesen izletesek es szinesek. Ellenörzott tárolási körülmények segitségevel a termést szeptembertöl-májusig tudjuk kinálni.</div>
			<div class="description lang-sb">Dobrodošli na našu farmu. Nudimo širok izbor jabuka. Zahvaljujući jedinstvenoj mikro-klimi i neintenzivnoj tehnologiji, naša jabuka ima poseban ukus sa atraktivnim bojama. Zbog tehnologije za skladištenje, jabuke su dostupne od septembra do maja.</div>
		</div>
	</div>
</div>


<div>
	<a class="horbox"
		href="/apples-for-sale/"
		style="background-color:#646945;min-height:120px;background-image:url(/img/bushel.png);background-blend-mode: overlay;"
	>
		<div class="row flex-row">
			<div class="flex-3">
				<div class="roundimg" style="background-image:url(/img/bushel.png);"></div>
			</div>
			<div class="flex-9">
				<h3>Apples For Sale</h3>
			</div>
		</div>
	</a>
</div>


<div>
	<a class="horbox"
		href="/technology/"
		style="background-color:#646945;min-height:120px;background-image:url(/img/technology.png);background-blend-mode: soft-light;"
	>
		<div class="row flex-row">
			<div class="offset-3 flex-6">
				<h3 class="text-">Technology</h3>
			</div>
			<div class="flex-3">
				<div class="roundimg" style="background-image:url(/img/technology.png);"></div>
			</div>
		</div>
	</a>
</div>

