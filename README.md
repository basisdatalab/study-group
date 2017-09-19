


Task Week 4
===========

Bab: HTTP Request and Basic Routing with [ExpressJS](http://expressjs.com/)

Deadline: **Selasa, 19 September 2017 pk 19.19**

 1. Pahami perbedaan request GET dan POST
> 	 ref: https://www.w3schools.com/tags/ref_httpmethods.asp
 
 2. Pahami *Route paths*
 > ref: http://expressjs.com/en/starter/basic-routing.html
 
 3. Pahami *Route parameters*
 > req.params: http://expressjs.com/en/4x/api.html#req.params
 
 > req.query: http://expressjs.com/en/4x/api.html#req.query
 
 4. Buat 5 *routes* yang berbeda, dengan spesifikasi:
	 1. Route biasa
	 2. Route biasa with spesific route
	 3. Routing using [req.params](http://expressjs.com/en/4x/api.html#req.params)
	 4. Routing using [req.query](http://expressjs.com/en/4x/api.html#req.query)
	 
	 Contoh
	-  Baris pertama: Get request url nya
	-  Baris kedua: Hasil print di browsernya
 > 1. /route_biasa
	 
	 Hello world!
 > 2. /ini_juga_route_biasa
	
	Hello kalian!
 > 3. /route_kedua/ini_spesific_route
	
	Ini juga Hello world!
> 4. a. /route_ketiga/foo bar
	
	Heelllooo! foo bar
> 4. b. /route_ketiga/paijooke
	
	Heellooo! paijooke
> 5. /route_keempat/user?nama=Basisdata Laboratory
	
	Welcome to route empat, Basisdata Laboratory
