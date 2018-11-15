Subiectul 2:
	Pentru a prelua datele din fisierul care reprezinta baza de date, trimit un request AJAX. Pentru ca acest request sa functioneze cu succes, este necesar un server http, intrucat protocolul file:/// nu este suportat implicit de catre browsere si nu as putea incarca datele prin AJAX.

	Pentru a nu obtine eroare CORS este necesar un server http, am folosit:
		https://www.npmjs.com/package/http-server
	