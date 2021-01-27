# HTML - CSS

This repository is about HTML & CSS and about how the internet works and web development fundamentals.

# How The Internet Works

Internet is a wire buried in the ground. Is usefull because 2 servers connected to the wire, can comunicate between themselves and web pages are files on the server hard drive.

Every server has a unique IP address, so computers know how to find each other. Every IP has a domain name. Clients use ISP(internet service provider). When something is travelling on interner computers split the information into Packages.

Everything connected to the internet has an IP address. Anywhere where 2 or more parts of the internet intersect there is a router. Router direct your packages across the internet. Is wrapping your package with layers, until it gets to server, than when is sent back the layers are deleted on the reverse.

ex: 
- https://codewithmosh.com/ - URL (uniform resource location)
- 127.0.0.1 - ip for localhost
- :5500 - server is waiting http requests on this port

HTTP - Hypertext Transfer Protocol - client and server use to talk with each other, plain text language
HTTPS - HTTP + Encryption

Server send the file type, if it is html, it build the DOM(document object model). From this we discover other references to other resources like images, fonts. Each resource has a separate url, so separate http request to the server, to fetch that resource, many of them are sent in parallel so we can see as fast as possible. After we got all the resources that we need the browser will render the HTML document.

# HTML 

- http://validator.w3.org/ - Validate markup
- HTML (Hypertext Markup Language) is a markup language used to define the structure and contents of web pages.

# CSS

- http://jigsaw.w3.org/css-validator/ - CSS validator
- CSS (Cascading Stylesheets) are used for styling web pages
