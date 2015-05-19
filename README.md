### Spotify's Web API
The purpose of this repository is to work as the public issue tracker for [Spotify's Web API](https://developer.spotify.com/web-api). If you've found a bug in the API, or have ideas on how we could improve it, please [create an issue](https://www.github.com/spotify/web-api/issues). It's greatly appreciated.

The repository also contains the [RAML™ specification](https://github.com/spotify/web-api/tree/master/specifications/raml) for the Spotify Web API. [RAML](http://raml.org/index.html) is a YAML-based language that describes RESTful APIs and provides all the information necessary to describe RESTful APIs, create API client-code and API server-code generators, and create API user documentation from RAML API definitions.

If you have ideas, bug reports, or any other type of feedback to Spotify that doesn't relate to the Web API, please submit these at [Spotify's Community forums](https://community.spotify.com/).

For bugs and features related to the mobile SDKs, please visit the repositories for the [Android SDK](https://github.com/spotify/android-sdk/) or the [iOS SDK](https://github.com/spotify/ios-sdk/).

We refer to [Stack Overflow](http://stackoverflow.com/questions/tagged/spotify) for programming related issues. Remember to add the `spotify` tag to your question.

For API announcements, follow [@SpotifyPlatform](https://www.twitter.com/spotifyplatform) on Twitter, visit the [API Change Log](https://developer.spotify.com/web-api/change-log/), or subscribe to our [newsletter](https://developer.spotify.com/web-api/).

#### Bug report format
Please provide a **description** including when the bug occurred and the API endpoints involved. If you believe the bug is related to authentication or authorization, please also provide the scopes given to your application.

Also include necessary **steps to reproduce** the issue, which may simply be a link to the [API console](https://developer.spotify.com/web-api/console/). Finally, please provide the difference between the **expected behaviour** and **actual behaviour** of the API.

##### Example

>Cannot retrieve profile for user with user ID "^"

>Issue found on February 19th 2015.

>Endpoint(s): /users/<user_id>
Scope(s): None (application is not using authentication)

>Steps to reproduce: Use the API Console, https://developer.spotify.com/web-api/console/get-users-profile/?user_id=%5E

>Expected behaviour: A public user object as described on https://developer.spotify.com/web-api/object-model/#user-object-public. 

>Actual behaviour: 500 Server Error (consistently)

