HTTP is a protocol used for transmitting data over the internet. It defines how messages are formatted and transmitted, and how web servers and browsers should respond to various commands. HTTP is the foundation of data communication on the World Wide Web.

A URL (Uniform Resource Locator) is the address used to access resources on the internet. It specifies the location of a resource and the protocol used to retrieve it. A URL typically includes the protocol (e.g., HTTP or HTTPS), the domain name, and the path to the resource.

DNS is a system that translates human-readable domain names (like www.example.com) into IP addresses that computers use to identify each other on the network. DNS servers resolve domain names to IP addresses, making it easier for users to access websites.

A query string is a part of a URL that contains data to be passed to web applications. It follows the ? symbol in the URL and consists of key-value pairs separated by &. For example, in http://example.com/page?name=John&age=30, the query string is name=John&age=30.

GET: This verb requests data from a specified resource. For example, fetching a web page or retrieving data from an API.
POST: This verb submits data to be processed to a specified resource. For example, submitting form data or uploading a file.

An HTTP request is a message sent by a client (e.g., a web browser) to a server to request a resource.

An HTTP response is a message sent by a server to a client in response to an HTTP request. 
HTTP headers are key-value pairs sent in both HTTP requests and responses to convey additional information about the request or response. 

DNS Lookup, TCP Connection, HTTP Request, Server Response, Rendering. 

curl -H "Accept: application/json" "https://icanhazdadjoke.com/search?term=pirate"

dig icanhazdadjoke.com