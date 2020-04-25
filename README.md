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

##Run swagger ui -- NOT WORKING YET

**run using docker**

	docker pull swaggerapi/swagger-ui
	docker run -p 8080:8080 -e BASE_URL=/swagger -e SWAGGER_JSON=/foo/swagger.yaml -v ./:/foo swaggerapi/swagger-ui

**run using podman**

	podman pull swaggerapi/swagger-ui
	podman run -p 8080:8080 -e BASE_URL=/swagger -e SWAGGER_JSON=/foo/swagger.yaml -v ./:/foo swaggerapi/swagger-ui

then open a browser at :

	[localhost](http://localhost:8080)

than enjoy you can surf the api

