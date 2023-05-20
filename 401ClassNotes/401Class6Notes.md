# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[Securing Woods](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

- Hashing is the aspect of applying randomly generated over passwords in databases to safeguard people's passwords.  That
way if someone gets into the database, all they get are these hash algorithms.  This is how passwords can be safely stored.
- BCrypt is a way to slow down brute force attacks to minimize the impact they present on the database.
- To calculate how expensive a hash function will be.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

- Basic authentication is a method for an HTTP user agent(web browser) to provide a user name and password. 
- The BA mechanism needs to be sent in every header HTTP request.
- They are both combined with a single colon, then encoded into an octet sequence, then encoded using a variant base and finally an authorization method and space character are prepended into the encoded string.

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

- The authentication process involves verifying who someone claims to be. Commonly a user name and password that are supposed to be privately owned by the user.
- They are determined the criticality of the application.  Sending generic messages can be confusing or misleading in their issues.
- Link bookmarked.

## Bookmark

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

## Class Notes

## Things I want to know more about
