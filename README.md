# http_status_code
A simple PHP class that sets the appropriate header for requests (Useful for REST APIs).

### To use:

    require 'Response.php'; 
    
	$Response = new Response();
	$Response->setResponse(500); //sets the header to HTTP/1.1 500 Server Error: Internal Server Error'
