# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Bearer Authorization

[Intro to JWT](https://jwt.io/introduction/)

- A JSON web token is an open standard that defines a compact self-contained way for securely transmitting information between parties as a JSON object.
- JSON web tokens should be used during authorization and information exchange. Authorization is the most common scenario, once a user is logged in and every request after will include JWT. Information exchange are just a good way to transmit data between parties.
- The payload (2nd part of the token) is where all 3 types of claims are expected. Registered claims are predefined claims which are not mandatory but recommended. Public claims are defined at will by those using JWTs. Private claims are custom claims created to share information between parties.

[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

- Because they are much more complex than people understand.  You would have to find out which secret someone used if trying to alter the code.  So unless you know which secret was used it is an extremely difficult thing to figure out.
- They both must know a shared secret. For now knowing the secret we would append Hash(payload + secret).
- It can be sent due to the secret.  Unless someone knows the underlying information of the secret it still maintains the privacy.

[JWTs explained](https://www.youtube.com/watch?v=926mknSW9Lo)

- JWTs are an excellent way to securely transmit information between parties because they can be signed which solidifies the sender as who they are.
- JWT are ways to send information between two parties as an object of data.
- JWT consist of a header which consists of the type of token and the signing algorithm. The payload which holds the claims being transferred. Lastly, the signature itself takes the encoded header, payload, secret and algo in the header and sign that.

## Bookmark

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

## Class Notes

## Things I want to know more about
