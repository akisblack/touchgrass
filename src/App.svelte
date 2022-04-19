<audio loop autoplay>
	<source src="./assets/music.mp3" type="audio/mpeg">
</audio>

<audio loop autoplay>
	<source src="./assets/candyland.mp3" type="audio/mpeg">
</audio>

<h1>
	Touch grass.
</h1>

<style>
	:global(body) {
		background-image: url("./assets/outside.jpg");
		background-repeat: repeat;
		color: white;
	}


	@font-face {
		font-family: 'Comic Sans MS';
		src: url("./assets/comicsans.ttf");
	}

	h1 {
		position: absolute;
		transform: translate(-50%, -50%);
		top: 50%;
		left: 50%;
		margin: 0;
		font-size: 5em;
		text-align: center;
		color: #b00b69;
		animation: text 5s infinite;
		font-family: 'Comic Sans MS';
	}

	@keyframes text {
		0% {
			color: aqua;
		}
		30% {
			color: green;
		}
		60% {
			color: chartreuse;
		}
		100% {
			color: #b00b69;
		}
	}
</style>