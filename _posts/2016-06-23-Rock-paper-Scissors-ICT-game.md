---
title: Rock paper Scissors ICT game
layout: post
author: joshua.larkin
permalink: /rock-paper-scissors-ict-game/
source-id: 1w8zt81MlFfYEbouG1LLeUkuns1xpnGvpTBJW4zNVPS4
published: true
---
// When the BBC micro:bit runs.

function onStart(  ) {

	microbit.say("Lets play", 75);

	globals.computerPicks = Random.number(1, 3);

	

}

function onPressA(  ) {

	microbit.say("You chose PAPER", 75);

	globals.playerPicks = 1;

	

}

function onPressB(  ) {

	microbit.say("You chose ROCK", 75);

	globals.playerPicks = 2;

	

}

function onPressAandB(  ) {

	microbit.say("You chose SCISSCORS", 75);

	

}

function onStart(  ) {

	if (globals.playerPicks == microbit.buttonAPressed) {

		

		microbit.say(___);

		

	}

	

	

}

