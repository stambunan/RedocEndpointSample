# RedocEndpointSample
Sample redoc repository to check HEAD and GET requests when using RedocUI

To test requests: 

1) Run the solution
2) A GET request to http://localhost:5021/api-docs returns 200 OK
3) A Head request to http://localhost:5021/api-docs returns 404

I'm expecting both GET and HEAD requests to return 200 OK similar to Swagger's endpoint

http://localhost:5021/swagger/index.html returns 200 OK for both GET and HEAD requests
