Build RESTful API with Hapi
Develop a web server using the Hapi framework. build projects with more real-life scenarios in building application systems.

1 - Web Server can store records
The web server can store the records added through the web application. Simply store them in the server memory in the form of a JavaScript array.

2 - Web Server can display notes
Next is that the web server can display notes. This requires the web server to send all or specifically the stored notes data.

 3 - Web Server can modify notes
The third is that the web server can change the notes. The changes can be in the form of title, content, or note tags. When a client requests a note change, it will make a request to the path '/notes/{id}', use the 'PUT' method, and bring JSON data in the body of the request which is the latest note data.

4 - Web Server can delete notes
Finally, the web server can delete notes. To delete a note, the client will make a request to the path '/notes/{id}' with the 'DELETE' method.
