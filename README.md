# HTTP-Server-with-Go

Github Summary - HTTP Server with Go
This code represents an HTTP server written in the Go programming language. The server serves static files from the static directory and handles two specific HTTP endpoints: /form and /hello.

The /form endpoint expects a POST request with two parameters, name and address, and responds with a message indicating whether the request was successful and the values of the two parameters. The /hello endpoint expects a GET request and simply responds with the message "hello!".

The http package is used to create the server and handle incoming requests. The http.Handle() function is used to set up a file server to serve static files from the static directory. The http.HandleFunc() function is used to handle the /form and /hello endpoints.

Finally, the server is started by calling http.ListenAndServe() with a port number of 8080. If an error occurs while starting the server, it will be logged to the console using the log.Fatal() function.

Overall, this code provides a simple example of how to create an HTTP server with basic endpoint handling using the Go programming language.
