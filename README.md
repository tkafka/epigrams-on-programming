Node.js module that gives you a list of epigrams on programming from [Alan J. Perlis](http://en.wikipedia.org/wiki/Alan_Perlis).

Use:

	var epigrams = require('epigrams-on-programming');
	
	var epigramOfTheDay = epigrams[Math.floor(Math.random()*epigrams.length)];
	
	console.log(epigramOfTheDay);

Epigrams taken from [http://pu.inf.uni-tuebingen.de/users/klaeren/epigrams.html](http://pu.inf.uni-tuebingen.de/users/klaeren/epigrams.html).
