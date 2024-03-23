# avvalish is a Simple Bank

It will provide APIs for the frontend to do the following things:

- Create and manage bank accounts.
- Record all balance changes to each of the accounts.
- Perform a money transfer between 2 accounts.

# about avvalish

The programming language we use to develop the service is Golang,
key words in this project:
design the database, docker for local development, Git to manage our codes, and GitHub Action to run unit tests automatically.
RESTful HTTP APIs using Gin, handling errors, authenticating users, and securing the APIs with JWT and PASETO access tokens.  
build our app with Docker and deploy it to a production Kubernetes cluster on AWS. 
managing user sessions, building gRPC APIs, using gRPC gateway to serve both gRPC and HTTP requests at the same time, embedding Swagger documentation as part of the backend service, partially updating a record using optional parameters, and writing structured logger HTTP middlewares and gRPC interceptors.
asynchronous processing in Golang using background workers and Redis as its message queue.
Gmail SMTP server.
 
## avvalish as a bank service

The service that we’re going to build is a bank. It will provide APIs for the frontend to do following things:

1. Create and manage bank accounts, which are composed of owner’s name, balance, and currency.
2. Record all balance changes to each of the account. So every time some money is added to or subtracted from the account, an account entry record will be created.
3. Perform a money transfer between 2 accounts. This should happen within a transaction, so that either both accounts’ balance are updated successfully or none of them are.


