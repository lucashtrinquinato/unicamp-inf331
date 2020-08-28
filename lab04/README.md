# Laboratório 04
## Aluno: Lucas Hervatin Trinquinato

# Tarefa 1
![Componente de Negócio](https://github.com/lucashtrinquinato/unicamp-inf331/blob/master/lab04/resources/Componente%20de%20nego%CC%81cio.png)

# Tarefa 2
![Controller](https://github.com/lucashtrinquinato/unicamp-inf331/blob/master/lab04/resources/Controller.png)

# Tarefa 3
![Model](https://github.com/lucashtrinquinato/unicamp-inf331/blob/master/lab04/resources/Model.png)

# Tarefa 4
* Serviço: Refuge Restrooms
* Breve descrição:
> API utilizada para encontrar banheiros que aceitam o uso por pessoas transgêneras
* URL completa da requisição: https://any-api.com:8443/https://www.refugerestrooms.org/api/v1/restrooms/by_location.json?unisex=true&lat=37.224112&lng=-107.859198
* Cabeçalho HTTP da chamada:
~~~ json
:authority: any-api.com:8443
:method: GET
:path: /https://www.refugerestrooms.org/api/v1/restrooms/by_location.json?unisex=true&lat=37.224112&lng=-107.859198
:scheme: https
accept: application/xml
accept-encoding: gzip, deflate, br
accept-language: pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
if-none-match: W/"9d736dbbfa07559ce350101bf01ebcec"
origin: https://any-api.com
referer: https://any-api.com/refugerestrooms_org/refugerestrooms_org/console/restrooms/GET_version_restrooms_by_location_format_
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: same-site
user-agent: Mozilla/5.0 (Linux; Android 8.0; Pixel 2 Build/OPD3.170816.012) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.105 Mobile Safari/537.36
~~~
* Cabeçalho HTTP da resposta:
~~~ json
access-control-allow-methods: GET, POST, OPTIONS
access-control-allow-origin: *
access-control-expose-headers: server,date,content-length,connection,access-control-allow-origin,access-control-allow-methods,access-control-expose-headers,access-control-max-age,x-total,x-total-pages,x-per-page,x-page,x-next-page,x-prev-page,x-offset,etag,cache-control,x-request-id,x-runtime,strict-transport-security,vary,via,x-final-url
access-control-max-age: 7200
cache-control: max-age=0, private, must-revalidate
cf-cache-status: DYNAMIC
cf-ray: 5ca1127c2829f3d3-GRU
cf-request-id: 04d889e1990000f3d39127c200000001
content-encoding: br
content-type: application/json
date: Fri, 28 Aug 2020 21:19:44 GMT
etag: W/"9d736dbbfa07559ce350101bf01ebcec"
expect-ct: max-age=604800, report-uri="https://report-uri.cloudflare.com/cdn-cgi/beacon/expect-ct"
server: cloudflare
set-cookie: __cfduid=de5ca6d59f84b9af7e9e139ca8e48193d1598649584; expires=Sun, 27-Sep-20 21:19:44 GMT; path=/; domain=.any-api.com; HttpOnly; SameSite=Lax
status: 304
strict-transport-security: max-age=31536000; includeSubDomains
vary: Origin
via: 1.1 vegur
x-final-url: https://www.refugerestrooms.org/api/v1/restrooms/by_location.json?unisex=true&lat=37.224112&lng=-107.859198
x-next-page: 2
x-offset: 0
x-page: 1
x-per-page: 10
x-prev-page
x-request-id: cd4f4cd2-05cd-4c03-b15e-2094160e6a7f
x-request-url: https://www.refugerestrooms.org/api/v1/restrooms/by_location.json?unisex=true&lat=37.224112&lng=-107.859198
x-runtime: 0.416289
x-total: 13
x-total-pages: 2
~~~

* Conteúdo da resposta:
~~~ json
{
    "id": 56510,
    "name": "Home Depo",
    "street": " 1301 S Camino Del Rio",
    "city": "Durango",
    "state": "Co",
    "accessible": true,
    "unisex": true,
    "directions": "its in the back by the gendered bathrooms",
    "comment": "It's a prety nice bathroom",
    "latitude": 37.224112,
    "longitude": -107.859198,
    "created_at": "2020-08-28T01:45:10.571Z",
    "updated_at": "2020-08-28T01:45:10.661Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": true,
    "edit_id": 56510,
    "approved": true,
    "distance": 0,
    "bearing": "0.0"
  },
  {
    "id": 38351,
    "name": "Walmart",
    "street": "1155 S Camino Del Rio",
    "city": "Durango",
    "state": "Colorado",
    "accessible": true,
    "unisex": true,
    "directions": "In the back by the electronics and photo center. It is right by the place where you pick up online ordered packages and where you come to get printed photos",
    "comment": "It is a family restroom",
    "latitude": 37.2299761,
    "longitude": -107.8657186,
    "created_at": "2017-10-24T23:37:36.607Z",
    "updated_at": "2017-10-24T23:37:36.607Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": true,
    "edit_id": 38351,
    "approved": true,
    "distance": 0.54115753440922,
    "bearing": "311.965650632294"
  },
  {
    "id": 42711,
    "name": "Lone Spur Cafe",
    "street": "619 Main Avenue",
    "city": "Durango",
    "state": "Colorado",
    "accessible": false,
    "unisex": true,
    "directions": "",
    "comment": "It's a restaurant so you should probably order a drink or something to use it. You might be able to call in an order and just ask to use the bathroom really quick",
    "latitude": 37.2706,
    "longitude": -107.8819443,
    "created_at": "2018-08-01T20:54:40.818Z",
    "updated_at": "2020-04-14T21:13:55.317Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 42711,
    "approved": true,
    "distance": 3.44704923129094,
    "bearing": "333.927773569002"
  },
  {
    "id": 19172,
    "name": "Student Union 33 and 34 (ground floor by Stairwell C)",
    "street": "1000 Rim Drive",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "Ground floor (same level as El Centro, NAC, Post Office)",
    "comment": "",
    "latitude": 37.2737453,
    "longitude": -107.8710382,
    "created_at": "2015-11-05T18:07:05.728Z",
    "updated_at": "2015-11-05T18:07:05.728Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 19172,
    "approved": true,
    "distance": 3.49061105459171,
    "bearing": "346.582654147001"
  },
  {
    "id": 19170,
    "name": "Fort Lewis College Kroeger Berndt 404 (basement",
    "street": "1000 Rim Drive",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "In the basement of Berndt Hall.  It includes a shower",
    "comment": "",
    "latitude": 37.2737453,
    "longitude": -107.8710382,
    "created_at": "2015-11-05T18:03:18.813Z",
    "updated_at": "2015-11-05T18:03:18.813Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 19170,
    "approved": true,
    "distance": 3.49061105459171,
    "bearing": "346.582654147001"
  },
  {
    "id": 19173,
    "name": "Fort Lewis College Student Union 207 and 208 (2nd fl. in \"back of house\" corridor behind Ballroom)",
    "street": "1000 Rim Drive",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "Near the catering office.",
    "comment": "",
    "latitude": 37.2737453,
    "longitude": -107.8710382,
    "created_at": "2015-11-05T18:09:26.619Z",
    "updated_at": "2015-11-05T18:09:26.619Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 19173,
    "approved": true,
    "distance": 3.49061105459171,
    "bearing": "346.582654147001"
  },
  {
    "id": 19171,
    "name": "Fort Lewis College Student Union 11 and 12 (ground floor across from Post Office)",
    "street": "1000 Rim Drive",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "Ground floor across from post office",
    "comment": "",
    "latitude": 37.2737453,
    "longitude": -107.8710382,
    "created_at": "2015-11-05T18:06:02.105Z",
    "updated_at": "2015-11-05T18:06:02.105Z",
    "downvote": 0,
    "upvote": 1,
    "country": "US",
    "changing_table": false,
    "edit_id": 19171,
    "approved": true,
    "distance": 3.49061105459171,
    "bearing": "346.582654147001"
  },
  {
    "id": 34116,
    "name": "Maria's Bookshop",
    "street": "960 Main Ave",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "Straight towards the back, first door on the right",
    "comment": "Great, popular shop, often has the door left open in warmer weather so it's easy to walk in and out very casually",
    "latitude": 37.2740743,
    "longitude": -107.8801955,
    "created_at": "2017-04-15T19:24:12.093Z",
    "updated_at": "2017-04-15T19:24:12.093Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 34116,
    "approved": true,
    "distance": 3.64010860634279,
    "bearing": "337.204597240628"
  },
  {
    "id": 35171,
    "name": "Starbucks",
    "street": "945 Main Avenue",
    "city": "Durango",
    "state": "CO",
    "accessible": false,
    "unisex": true,
    "directions": "Two neutral stalls and a women's single stall.",
    "comment": "Need to be a paying customer.",
    "latitude": 37.2740853,
    "longitude": -107.8808852,
    "created_at": "2017-05-20T13:26:58.806Z",
    "updated_at": "2017-05-20T13:26:58.806Z",
    "downvote": 0,
    "upvote": 0,
    "country": "US",
    "changing_table": false,
    "edit_id": 35171,
    "approved": true,
    "distance": 3.65303849981538,
    "bearing": "336.540326033363"
  },
  {
    "id": 40227,
    "name": "El Moro Spirits and Tavern",
    "street": "945 Main Ave",
    "city": "Durango",
    "state": "CO",
    "accessible": true,
    "unisex": true,
    "directions": "there are three single room bathrooms. the first one is for people who identify as female, the second two are both gender neutral. ",
    "comment": "this is a restaurant/bar so you may have to be a paying customer to use them. ",
    "latitude": 37.2740927,
    "longitude": -107.8808913,
    "created_at": "2018-03-03T07:34:14.153Z",
    "updated_at": "2018-03-03T07:34:14.153Z",
    "downvote": 0,
    "upvote": 1,
    "country": "US",
    "changing_table": false,
    "edit_id": 40227,
    "approved": true,
    "distance": 3.65363129567654,
    "bearing": "336.537539549135"
  }
~~~

* Serviço: College Football Data
* Breve descrição:
> API utilizada para obter informações de futebol americano Colegial. No caso dessa requisição, utilizei para os jogos do time Florida na primeira semana de 2019.
* URL completa da requisição: https://any-api.com:8443/https://api.collegefootballdata.com/games?year=2019&week=1&seasonType=regular&team=Florida
* Cabeçalho HTTP da chamada: 
~~~ json
:authority: any-api.com:8443
:method: GET
:path: /https://api.collegefootballdata.com/games?year=2019&week=1&seasonType=regular&team=Florida
:scheme: https
accept: */*
accept-encoding: gzip, deflate, br
accept-language: pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
if-none-match: W/"239-PQkscpMDxRxdtAcDMMnATRK4GeI"
origin: https://any-api.com
referer: https://any-api.com/collegefootballdata_com/collegefootballdata_com/console/games/getGames
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: same-site
user-agent: Mozilla/5.0 (Linux; Android 8.0; Pixel 2 Build/OPD3.170816.012) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/84.0.4147.105 Mobile Safari/537.36
~~~
* Cabeçalho HTTP da resposta:
 ~~~ json
access-control-allow-origin: *
access-control-expose-headers: server,date,connection,x-dns-prefetch-control,x-frame-options,strict-transport-security,x-download-options,x-content-type-options,x-xss-protection,access-control-allow-origin,etag,x-final-url
cf-cache-status: DYNAMIC
cf-ray: 5ca11eb4f969f3d3-GRU
cf-request-id: 04d89185190000f3d391303200000001
content-encoding: br
content-type: application/json; charset=utf-8
date: Fri, 28 Aug 2020 21:28:05 GMT
etag: W/"239-PQkscpMDxRxdtAcDMMnATRK4GeI"
expect-ct: max-age=604800, report-uri="https://report-uri.cloudflare.com/cdn-cgi/beacon/expect-ct"
server: cloudflare
set-cookie: __cfduid=dd4e724d22a6bb70399a85f0819d06c0e1598650084; expires=Sun, 27-Sep-20 21:28:04 GMT; path=/; domain=.any-api.com; HttpOnly; SameSite=Lax
status: 304
strict-transport-security: max-age=15552000; includeSubDomains
x-content-type-options: nosniff
x-dns-prefetch-control: off
x-download-options: noopen
x-final-url: https://api.collegefootballdata.com/games?year=2019&week=1&seasonType=regular&team=Florida
x-frame-options: SAMEORIGIN
x-request-url: https://api.collegefootballdata.com/games?year=2019&week=1&seasonType=regular&team=Florida
x-xss-protection: 1; mode=block
 ~~~
* Conteúdo da resposta:
~~~ json
 {
    "id": 401110723,
    "season": 2019,
    "week": 1,
    "season_type": "regular",
    "start_date": "2019-08-24T23:00:00.000Z",
    "start_time_tbd": null,
    "neutral_site": true,
    "conference_game": false,
    "attendance": 66543,
    "venue_id": 4013,
    "venue": "Camping World Stadium",
    "home_id": 57,
    "home_team": "Florida",
    "home_conference": "SEC",
    "home_points": 24,
    "home_line_scores": [
      7,
      0,
      10,
      7
    ],
    "home_post_win_prob": "0.9059534582132265",
    "away_id": 2390,
    "away_team": "Miami",
    "away_conference": "ACC",
    "away_points": 20,
    "away_line_scores": [
      3,
      10,
      0,
      7
    ],
    "away_post_win_prob": "0.09404654178677352",
    "excitement_index": "8.7679102419"
  }
~~~
