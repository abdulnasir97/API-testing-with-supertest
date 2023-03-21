# API-testing-with-supertest

In the app.test.js file, you will write tests to:

Ensure that the POST /todos endpoint handles a request containing the todo data by
assigning a new id to the note
storing the note
and returning a 201 status code and the stored note as JSON on success
Ensure that the POST /todos endpoint returns a 400 status code if the title property is missing or empty in the incoming request body
Ensure that the GET /todos/:todoId handler returns an error if the :todoId does not exist
Ensure that the API returns the correct error message if the user tries to visit a route that is not defined:
`Not found: ${req.originalUrl}`;
