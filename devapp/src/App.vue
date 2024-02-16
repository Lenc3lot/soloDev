<template>
	<header class="header">
		<h1 class="logo">Etu'Connect</h1>
		<ul class="main-nav">
			<li><router-link to="/">Accueil</router-link></li>
			<li><router-link to="/about">Voter</router-link></li>
			<li><router-link to="/login">Connexion</router-link></li>
		</ul>
	</header>
	<router-view />
</template>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	color: black;
	display: flex;
	flex-direction: row;
	height: 100%;	
}

* {
	box-sizing: border-box;
}

body {
	font-family: 'Montserrat', sans-serif;
	line-height: 1.6;
	margin: 0px;
	padding: 0px;
	min-height: 100vh;
	background: linear-gradient(270deg, rgb(103, 151, 221) 0%, white 100%);
	height: 40rem;
}

ul {
	margin: 0;
	padding: 0;
	list-style: none;
}


h2,
h3,
a {
	color: #34495e;
}


.logo {
	margin: 0;
	font-size: 1.45em;
	padding: 1%;
}

.main-nav {
	margin-top: 5px;
	display: flex;
	flex-direction: column;
}

.logo a,
.main-nav a {
	padding: 10px 15px;
	text-transform: uppercase;
	text-align: center;
	display: block;
}

.main-nav a {
	color: #34495e;
	font-size: .99em;
}

.main-nav a:hover {
	color: #718daa;
}

.header {
	-webkit-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
	-moz-box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
	box-shadow: 0px 0px 14px 0px rgba(0, 0, 0, 0.75);
	display: flex;
	flex-direction: column;
	width: 13%;
	padding: 1%;
	text-align: center;
	border-top-right-radius: 5%;
	border-bottom-right-radius: 5%;
	margin-right: 1%;
}

.header>*{
	width: 100%;
}
</style>

