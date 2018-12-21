# Download files from web-pages programmatically

## HTTP (Hypertext Transfer Protocol)
HTTP, the Hypertext Transfer Protocol, is the language that web browsers (like Chrome or Safari) and web servers (basically computers where the contents of a website are stored) speak to each other. Every time you open a web page, or download a file, or watch a video, it's HTTP that makes it possible.

HTTP is a request/response protocol:

- Your computer, a.k.a. the client, sends a request to a server for some file. "Get me the file 1-the-wizard-of-oz-1939-film.txt", for example. GET is the name of the HTTP request method (of which there are multiple) used for retrieving data.
- The web server sends back a response. If the request is valid: "Here is the file you asked for:", then followed by the contents of the 1-the-wizard-of-oz-1939-film.txt file itself.

![image](https://user-images.githubusercontent.com/25883512/50339895-6fd80b00-0521-11e9-8264-f5989dc6cc8c.png)

In the Jupyter Notebook, I have programmatically download all of the Roger Ebert review text files to a folder called ebert_reviews using the Requests library. 

For more information:
I encourage you to check out the following documentation: http://docs.python-requests.org/en/master/
