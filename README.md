Simple app to control multiple Spotify clients from a single server. Use is to listen to music with your friends over the internet! Work in progress.

## Installation

Clone the repository and install its dependencies running:

    $ npm install

### Using your own credentials
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application. For the example, we registered these Redirect URIs:

* http://localhost:8888/callback

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in the examples with the ones you get from My Applications.

Finally, start the server, and point your friends to it. Every user has to have their own Spotify client running. Once this is done, any connected user can play a Spotify track through its URI link and it will be streamed to each client.
