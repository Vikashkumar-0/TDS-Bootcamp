--- Before Day-4 ---
I already knew the basic concepts of APIs, web requests, and how browsers communicate with servers. I had some experience using Python and had heard of HTTP methods and status codes, but I had not practiced them in depth.

---

## Day-4 Checklist

* [x] I know the 5 core HTTP methods (GET, POST, PUT, PATCH, DELETE) and what each is used for
* [x] I can read a status code and know what went wrong — e.g., 401 vs. 403 vs. 404 vs. 500
* [x] I can open Chrome DevTools Network tab, find a request, and inspect its headers, payload, and response
* [x] I can copy a browser request as a cURL command and run it in the terminal
* [x] I can change the User-Agent in the browser and see the change in the Network tab
* [x] I can use curl to make a GET request with query parameters and a POST request with a JSON body
* [x] I have a running FastAPI app with at least two endpoints (GET /health and POST /echo)
* [x] I can test my API using the Swagger UI at /docs and via curl from the terminal

---

## After Day-4

I learned how HTTP requests and responses work in practice rather than just theory. I became comfortable using Chrome DevTools to inspect network traffic, understanding request headers, payloads, and responses. I learned how to use curl for testing APIs from the terminal and how to build and test simple FastAPI endpoints. I also gained a better understanding of HTTP status codes and how they help diagnose API issues.

---

## Feedback (Suggestions for the TDS Team)

The hands-on exercises were useful for understanding APIs and HTTP concepts. The combination of browser tools, curl, and FastAPI helped connect theory with practice. It would be helpful to include a few more real-world debugging examples involving authentication errors, malformed requests, and server-side failures to strengthen troubleshooting skills.

---

You can write your personal notes here; they will not be parsed and are for your own reference.

* Difference between PUT and PATCH:

  * PUT replaces the entire resource.
  * PATCH updates only specific fields.

* Common status codes:

  * 200 OK
  * 201 Created
  * 400 Bad Request
  * 401 Unauthorized
  * 403 Forbidden
  * 404 Not Found
  * 500 Internal Server Error

* FastAPI automatically generates interactive API documentation at /docs.

* curl is useful for testing APIs without a browser.
