<!--

Thanks for your interest in the Spotify Web API!
If you're submitting a bug, please use the following template.
If your issue is a feature request, please include your use-case so that we have all the necessary info.

-->

<!-- Title: Cannot retrieve profile for user with user ID "^" -->

Issue found on February 19th 2015.

#### Endpoint(s):
* `GET /v1/users/{user_id}`

#### Scope(s):
* None (application is not using authentication)

#### Steps to reproduce:
1. Open the API Console
2. Call the `get-users-profile` endpoint with `user_id` `%5E`

#### Expected behaviour:
A public user object as described on `https://developer.spotify.com/web-api/object-model/#user-object-public`.

#### Actual behaviour:
500 Server Error (consistently)

