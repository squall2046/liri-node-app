# :headphones: liri-node-app

## Overview
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. It is a Node **command line app** that takes in parameters and gives you back data. 
####   :point_right: Click  **[>>>Here<<<](https://youtu.be/F9wBMugsnOE)**  Check my :tv: video to see how it works.
![concert](/imgs/w6.jpg)


## Instruction

##  :guitar: 1. node liri.js concert-this <artist/band name here>
     * Name of the venue
     * Venue location
     * Date of the Event (use moment to format this as "MM/DD/YYYY")

![concert](/imgs/scr1.png)


## :microphone: 2. node liri.js spotify-this-song <song name here>
     * Artist(s)
     * The song's name
     * A preview link of the song from Spotify
     * The album that the song is from

![concert](/imgs/scr2.png)

:fast_forward:   * If no song is provided then your program will default to "The Sign" by Ace of Base.

![concert](/imgs/scr3.png)

## :clapper: 3. node liri.js movie-this <movie name here>
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.

![concert](/imgs/scr4.png)

:fast_forward:   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

![concert](/imgs/scr5.png)

## :page_facing_up: 4. node liri.js do-what-it-says
     * It will run `spotify-this-song` for "I Want it That Way" as follows the text in local `random.txt`.

![concert](/imgs/scr6.png)

:ballot_box_with_check:   * Each command you run will append to the `log.txt` file.

![concert](/imgs/scr7.png)

## Author
* [Isaac Wu](https://github.com/squall2046)
* [Game Repo](https://github.com/squall2046/liri-node-app)

## Copyright
Isaac Wu © 2019 All Rights Reserved

