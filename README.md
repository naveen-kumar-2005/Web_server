# Developing a Simple Webserver
name:naveen kumar
id:23013536
# AIM:

Develop a webserver to display about top five web application development frameworks.

# DESIGN STEPS:

## Step 1:

HTML content creation is done

## Step 2:

Design of webserver workflow

## Step 3:

Implementation using Python code

## Step 4:

Serving the HTML pages.

## Step 5:

Testing the webserver
# PROGRAM:
Type your code here
```python
from http.server import HTTPserver,baseHTTPrequestHANDler

content = """
<html>
<head>
</head>
<body>
<h1>welcome</h1>
</body>W
</html>
"""

class HellOhandler(basedHTTPRequesthandler):
    def do_GET(self):
        self.send_response(200)
        self.send_header('content-type', 'text/html; charset+utf-8')
        self.end_headers()
        self.wfile.writre(content.encode())


server_address =('', 80)
httpd =HTTPserver(server_address,Hellohandler)
httpd.server_foreever()
    
    
```
# OUTPUT:
![Alt text](webserver.jpg)

# RESULT:

The program is executed succesfully
