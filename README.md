# Nginx with Node.js Challenge

Challenge presented in the Full Cycle course (Docker module).

The challenge is to present a message on the screen using nginx with node.js.

When a call is made to the application, it must save a record in the database (MySQL).
Then the page should display the message ```Full Cycle Rocks!```, just below a list of the database records.

Note: The page must be built on node but will be accessed by nginx through a reverse proxy!

---

### To run the application use docker-compose.

```
docker-compose up -d 
```

---

### To access, enter the following address in the browser:

[http://localhost:8080/](http://localhost:8080/)

---
If you get a 502 error, wait a few more seconds and refresh the page.
