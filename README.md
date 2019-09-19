"# cURL-Lab" 

3. HTTP request & response:
> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*

< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Thu, 19 Sep 2019 12:23:43 GMT

4. 	curl -o http-easy.html http://www.jmarshall.com/easy/http/

5. 	curl -o -v duckduckgo.html http://www.duckduckgo.com/
	curl -o -v duckduckgo.txt http://www.duckduckgo.com/
	
6.	curl -o science1.txt https://duckduckgo.com/?q=science&t=h_&ia=web/
	curl -o computer-science.txt https://duckduckgo.com/?q=computer+science&t=h_&ia=web/

7.	curl -o gmit.json https://duckduckgo.com/?q=gmit&format=json

8.	354 HTTP requests from "The Irish Times".
	341 HTTP requests from "The Independent".