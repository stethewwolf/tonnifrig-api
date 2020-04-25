#Tonnifirg-API
##Run swagger enditor
**run using docker**
	docker pull swaggerapi/swagger-editor
	docker run -d -p 8080:8080 -e URL=/foo/swagger.json -v ./:/usr/share/nginx/html/foo swaggerapi/swagger-editor

**run using podman**
	podman pull swaggerapi/swagger-editor
	podman run -d -p 8080:8080 -e URL=/foo/swagger.json -v ./:/usr/share/nginx/html/foo swaggerapi/swagger-editor

then open a browser at :
	[localhost](http://localhost:8080)

than enjoy 
