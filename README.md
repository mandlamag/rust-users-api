# Rust Users API

For that, we are going to use the ** Rocket framework ** for the API and Diesel ORM framework for persisting features. This framework will cover all the things mentioned below. So, it will be much easier than implementing it from scratch.

1. Start a web server and open a PORT
2. Listen to requests on this PORT
3. If a request comes in, look at the Path in the HTTP header
4. Route the request to the handler according to the Path
5. Help you extract the information from the reque
6. Pack the generated data (created by you) and form a response
7. Send the response back to the sender
