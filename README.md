# How Web Works Exercise

### Part One: Solidify Terminology
#### **In your own terms, define the following terms:**

**HTTP**: HTTP stands for Hyper Text Transfer Protocol and dictates people to getting/sending data to a server.

**URL**: URL stands for Uniform Resource Locator, it's an address that allows you to access a websites content.

**DNS**: DNS stands for Domain Name System, this system takes human-readable URLs, converting them into IP addresses. It's effectively a phonebook for the internet.

**Query String**: A Query String passes key-value pairs into the URL.

**List two HTTP verbs and their use cases**: `GET` retrieves data from a specific resource that you request. `DELETE` method deletes the specific resource.

**What is an HTTP Request?**: An `HTTP` Request is a request from a client to a server following the HTTP protocol, and sends back the content that you would get from HTT protocol, such as the HTML, CSS, and JavaScript of the server.

**What is an HTTP header? Give a couple examples of request and reponse headers you have seen.**:

Headers give you more information on the request/response to a domain 
#### Request Headers
- `Host:` Gets the domain host of the website
- `Accept-Launguage:` Gets the accepted languages of the website (eg. en-US, etc.)
#### Reponse Headers
- `Content-Type:` Used to indicate the orginal media type of the resource (eg. mulipart/form-data, etc.)
- `Cache-Control:` Holds instructions in both requests and responses, they control caching in browsers and shared chaches (i.e. CDNs, Proxies, etc.)

**What are the processes that happen when you type "http://somesite.com/some/page.html" into a browser?**

1. Your browser turns the name into an IP address using the Domain Name System (DNS)
2. Your browser makes a request to that IP with headers(cookies, information about the browser your using, etc)
3. The server sends a response with HTML and hopefully a status code 200 if successful
4. Browser then creates a DOM from the HTML the server sent, and other resources that are needed such as the CSS, JavaScript, SQL, Images, etc.
5. The browser finally creates separate HTTP requests for those extra resources and will get reponses for each of those requests from the server.
6. Page content is loaded (assuming every went as planned beforehand)!
