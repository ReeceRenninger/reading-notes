# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

- A query string parameter is appended to the URL and consists of key-value pairs separated by ampersands, used to provide additional information or modify the behavior of a request. A path parameter, on the other hand, is part of the URL path itself and is used to identify a specific resource or entity being requested, typically denoted by a placeholder within the URL path.
-
  - API follows a standard routing structure with a version number (v3), model name (stuff), and an ID parameter (things)
  - The v3 references the version number.
  - server would respond with information related to the model of stuff endpoint.
  - server would respond with the information related to the specific entity identified by the ID things in the stuff data model.
- The interface is what allows you to navigate a website or a terminal if you are using a CLI with something like inquirer.

[Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

- To implement basic authentication using middleware, create a function that extracts and validates the "Authorization" header with the username and password. If the credentials are valid, allow the request; otherwise, return an authentication error. For bearer authentication, extract and verify the "Authorization" header with a token format. Validate the token's authenticity, integrity, and expiration before allowing the request. Register these middleware functions in the request pipeline to handle authentication.
- The handshake necessary to implement OAuth involves a series of interactions between the client application, the user, and the authorization server. The client initiates the process by redirecting the user to the authorization server, where the user grants permission to the client. The authorization server then issues an access token to the client, allowing it to access protected resources on behalf of the user.
- RBAC is a way to manage and control access to resources based on user roles and permissions. It simplifies administration by separating privileges into roles and ensures users only have access to the resources required for their roles, enhancing security and scalability in systems with multiple users.

## Class Notes

## Things I want to know more about
