# SwaggerParser-BurpExtension

With this extension, you can parse Swagger Documents. You can view the parsed requests in the table and send them to Repeater, Intruder, Scanner.

## How to use

**1- Extension written in Python. That's why he works with Jython. We need to add the Jython jar file to Burp.**




**2- After adding Jython to Burp, we can also add the Extension to Burp with the Extension's python file.**




**3- If the extension has been installed successfully, the "Swagger Parser" tab will be added. You can see the extension screen by clicking this tab.**




**Custom Headers Panel:** Headers written below in this panel are added to all requests while parsing.



**Output Panel:** After the parse process is completed, all endpoints are listed in Markdown format.



**Request History Panel:** After the parse process is completed, the requests are listed in the table and can be sent to the Repeater, Intruder, Scanner.




**4- We right-click on the Swagger Document request we want to parse and select the "Send to Swagger Parser" option and the parsing process begins.**

