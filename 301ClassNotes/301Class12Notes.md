# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: CRUD

[Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1.
In your own words, describe what each group of status code represents:

    100’s = Informational status codes. Usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of client.

    200’s = These are the success codes. They tell the client that its request was accepted.

    300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.

    400’s = These are the client error codes. They are all about invalid requests a client sent to a server.

    500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies

2. Status code 202 is Accepted. Request was valid but it is processing and will finish sometime in the future.
3. Status code 308 is Permanent Redirect. Tells the client to use another URL to access the resource.
4. Status code 204 No Content. This means data WAS NOT RETURNED to the client.
5. Status code 410 Gone. This is like the 404, but the resource used to exist but no longer does.
6. Status code 403 Forbidden. Client has authorized or doesn't need to authorize itself, but still has NO PERMISSIONS to access the resource.

[Build A REST API WIth Node.js, Expres, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

- Watch the first 20 minutes

1. Because we will want to use something that is not our local host so we place it into our environmental variable.
2. Middleware is software that allows different applications to communicate.
3. app.use(express.json()) is a built-in middleware function and it parses incoming JSON information.
4. /:id in a route allows us to have a parameter that we will access everything that is typed past that.
5. PATCH allows the information to get partially updated based off the input received where PUT would update everything everytime something is put in.
6. We created a variable for the schema that we can set objects in the schema to have default values, such as the name, subscriberToChannel, and subscribeDate that was used in the video.
7. Status Code 500 Interval Server Error which means the server encountered an unexpected condition that prevent the request from being fulfilled.
8. Status Code 200 means the request was received, understood and processed. Where the status code 201 means the request means only the request was successful and created the resource.

## Class Notes

## Things I want to know more about
