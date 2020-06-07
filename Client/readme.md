There are two folders in this project. The first for the client package, and the second for the server package.

The server package in the "server" folder is operational as is. When started, it will host a JSON api on port 3000 with GET /todos, GET /todos/{id}, and POST /todos endpoints.

The client package is in the "client" folder. It is only a very brief (and incomplete) example of one way the server can be used. It consists of a single html document (in public folder) which loads jquery and then uses jquery to fetch the todos list from the server and render it on the page.  I doesn't use any frontend frameworks, only jquery for the ajax helper.

Your task is to write a fully functioning front-end web app using the back-end server.