# Ads-board - application that allows you to manage online offers - notice board.

Functionality checked with Postman.
Basic error handling, endpoint nomenclature, support for HTTP methods and returned HTTP response codes.
A collection containing examples of requests for all prepared functions has been attached.
The port used by the application is set using environment variables (not included - private data base).
1. The application responds to requests sent to / heartbeat with the current date and time
2. The application allows you to add an advertisement
3. The application allows you to return all ads and a single ad
4. The application allows you to delete the selected advertisement
5. The application allows you to modify the selected advertisement
6. The application allows you to search for an advertisement (author, title, price, year, tags)
7. The application saves the ads in the database (MongoDB)
8. Removing and modifying ads is password protected (password verification middleware, basic solution)
9. The application has 3 permanently defined users, each of them can delete and modify only those ads that he added himself
10. After starting the application with the (node app.js debug) parameter, it saves in the file the time of receipt of each request, the HTTP method and the address to which the request came
11. After receiving a request to an address that does not exist, the application returns a static image instead of the default 404 error page
12. In case of application errors, details of the error are saved in console.log
