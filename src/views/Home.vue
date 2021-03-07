<template>
	<div class="home">
		<h1>welcome</h1>
		<p>
			I'm Jon <u>Rickard</u> Yxelflod from Gothenburg, Sweden. This is my little
			corner on GitHub.<span class="more"
				><router-link to="/about">More&hellip;</router-link></span
			>
		</p>
		<h2>current status</h2>
		<p>
			I'm studying web development: frontend (with some backend) at
			<a href="https://www.iths.se/" target="_blank">IT&#8209;högskolan</a>.
			Thus far we've covered HTML, CSS &amp; Sass, JavaScript and Vue.js. We're
			going to learn &mdash; among other things &mdash; DB, PHP and React up
			ahead.
		</p>
		<h2>goals</h2>
		<ul>
			<li>
				Finish my education and find a job where I can be part of something
				creative
			</li>
			<li>Learn A-Frame and Three.js</li>
			<li>Learn C++ so I can work with Arduino and Korg Logue SDK</li>
		</ul>
		<h2>dreams</h2>
		<ul>
			<li>Learn Basic and develop a game for C64</li>
			<li>
				Hike through Russia and China, cross the Bering Strait over to Alaska
				and on through Canada and the United States
			</li>
		</ul>
		<h2>guilty pleasures</h2>
		<ul>
			<li>Coffee</li>
			<li>Dr Pepper</li>
			<li>Boylan Cane Cola</li>
		</ul>
	</div>
</template>

<script>
export default {
	name: "Home",
	components: {},
};
</script>

<style lang="scss" scoped></style>
