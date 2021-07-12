## ~~reading-notes-13~~

## In your own words, describe what each group of status code represents:
***100’s =These are informational status codes; they usually tell the client that the header part of the request has been received***
***200’s =These are the success codes. They tell the client that its request was accepted***
***300’s =These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.***
***400’s =These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc.***
***500’s =These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.***

## What is a status code 202?
***often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.***

## What is a status code 308?
***this is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.***

## What code would you use if an update didn’t return data to a client?
***204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.***

## What code would you use if a resource used to exist but no longer does?
***204 No Content*** 

## What is the ‘Forbidden’ status code?
***403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.***




## Why do we need to pull our MongoDB database string out of our server and put it into our .env?
***to query and update data***

## What is middleware?
***provide common services and capabilities to applications outside of what’s offered by the operating system.***

## What does app.use(express.json()) do?
***recognize the incoming Request Object as a JSON Object***

## What does the /:id mean in a route?
***meaning that your actions can execute without the ID provided as part of the URL.***

## What is the difference beween PUT and PATCH?
***the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.***

## How do you make a defalut value in a schema?
***Make mongoose string schema type default value as blank and make the field optional.***

## What does a 500 error status code mean?
***500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request***

## What is the difference between a status 200 and a status 201?
***The 200 status code is by far the most common returned,that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result***
