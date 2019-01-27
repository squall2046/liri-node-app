# :headphones:liri-node-app

### Overview
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

> :tv:
> Click  >>>**[Here](https://youtu.be/F9wBMugsnOE)**<<<  and check the video to see how it works.

## Instruction

##  :guitar:1. node liri.js concert-this <artist/band name here>
     * Name of the venue
     * Venue location
     * Date of the Event (use moment to format this as "MM/DD/YYYY")

## :microphone:2. node liri.js spotify-this-song '<song name here>'
     * Artist(s)
     * The song's name
     * A preview link of the song from Spotify
     * The album that the song is from

--    * If no song is provided then your program will default to "The Sign" by Ace of Base.

## :clapper:3. node liri.js movie-this '<movie name here>'10:59 PM 1/26/201910:59 PM 1/26/2019
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.

--   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

##:page_facing_up:4. node liri.js do-what-it-says
     * It will run `spotify-this-song` for "I Want it That Way" as follows the text in local `random.txt`.

### :ballot_box_with_check:Log
* Each command you run will append to the `log.txt` file.

## :headphones:Author:
* [Isaac Wu](https://github.com/squall2046)
* [Game Repo](https://github.com/squall2046/liri-node-app)

## Copyright
Isaac Wu © 2018 All Rights Reserved

