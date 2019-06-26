- [Commands](#commands)
- [Technology Used](#technology-used)
- [Developer](#developer)

# LIRI-Bot

LIRI (Let It Research It) Bot is an app, which runs in the terminal, that searches movie or music facts at a of a hat! LIRI takes the inconvenience of waiting for webpage to load up.


## Commands

1. `node liri.js concert-this <artist/band name here>`

   * This will search the Bands in Town Artist Events API (`"https://rest.bandsintown.com/artists/" + artist + "/events?app_id=codingbootcamp"`) for an artist and will bring up the following information about each event to the terminal:

     * Name of the venue (i.e TD Waterhouse Arena)

     * Venue location (i.e. Orlando)

     * Date of the Event (use moment to format this as "MM/DD/YYYY")


2.  `node liri.js spotify-this-song '<song name here>'`

   * This will show the following information about the song in your terminal

     * Artist(s)

     * The song's name

     * A preview link of the song from Spotify

     * The album that the song is from

3.  `node liri.js movie-this '<movie name here>'`

   * This will output the following information to your terminal:

       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.


## Technology Used

- Javascript

- [Node-Spotify-API](https://www.npmjs.com/package/node-spotify-api)

- [Axios](https://www.npmjs.com/package/axios)

- [OMDB API](http://www.omdbapi.com)

- [Bands In Town API](http://www.artists.bandsintown.com/bandsintown-api)

- [DotEnv](https://www.npmjs.com/package/dotenv)


## Developer

[Andrew](https://github.com/ahok89)