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
	background: rgba(99, 22, 22, 0.2);
	padding: 1em;
	border-radius: 4px;
	box-shadow: 0 0 black;
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
}
.horbox .description {
	font-weight: bold;
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

</style>

<div class="horbox" style="background-image:url(/img/photos/applebin.jpg)">
	<div class="row">
		<div class="offset-6 col-6 horbox-text">
			<h3>Jabuke sa Peska</h3>
			<div class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</div>
		</div>
	</div>
</div>


<div>
	<a class="horbox"
		style="background-color:#631616;min-height:120px;"
		href="/contact/"
	>
		<div class="row flex-row">
			<div class="flex-3"></div>
			<div class="flex-6">
				<div class="description">Kovács János 6782</div>
				<div class="description">00+381 24 882-230</div>
			</div>
			<div class="flex-3"></div>
		</div>
	</a>
</div>

<div>
	<a class="horbox"
		href="/apple-varieties/"
		style="background-color:#646945;min-height:120px;background-image:url(/img/bushel.png);background-blend-mode: overlay;"
	>
		<div class="row flex-row">
			<div class="flex-3">
				<div class="roundimg" style="background-image:url(/img/bushel.png);"></div>
			</div>
			<div class="flex-9">
				<h3>Apple Varieties</h3>
				<div class="description">We sell a variety of apple types.</div>
				
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
			<div class="flex-9">
				<h3>Technology</h3>
				<div class="description">Learn how we farm our apples.</div>
			</div>
			<div class="flex-3">
				<div class="roundimg" style="background-image:url(/img/technology.png);"></div>
			</div>
		</div>
	</a>
</div>

