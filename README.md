Web API feita em .NET Core


### Request

Dê um array não ordenados de nomes e receba um ordenado de volta.


`GET /sort/`

    curl -X 'GET' \
    'https://localhost:7040/sort?names=d&names=h&names=e&names=b' \
    -H 'accept: text/plain'
  
  
 ### Response
  
    content-type: application/json
    charset=utf-8  date: Tue,20 Dec 2022 23:04:59 GMT  
    server: Kestrel  x-firefox-spdy: h2 
  
    ["b","d","e","h"]
