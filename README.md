# Rust Users API
For that, we are going to use the Rocket framework for the API and Diesel ORM framework for persisting features. This framework will cover all the things mentioned below. So, it will be much easier than implementing it from scratch.
Start a web server and open a PORT.
Listen to requests on this PORT.
If a request comes in, look at the Path in the HTTP header.
Route the request to the handler according to the Path.
Help you extract the information from the request.
Pack the generated data (created by you) and form a response.
Send the response back to the sender.