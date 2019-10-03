# Liri-node-app
## Overview
LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface,
LIRI is a Language Interpretation and Recognition Interface.LIRI will be a command line node app that 
takes in parameters and gives you back data. LIRI will search Spotify for songs, Bands in Town for 
concerts, and OMDB for movies.

## Installation
The package.json lists dependent node packages, but for your convenvice, these are the ones to install.

***Config:***
npm install dotenv

***FS:***
npm install fs

***Request:***
npm install request

***Spotify:***
npm install node-spotify-api

## Motivation 
I wanted to learn making interactive program which the liri bot is facinating me , and throwing me 
insights on what a program can do and challenge. This was a huge learning experience which I showed 
to my family.

## Get started
What Each Command Does:

## concert-this:

This will search the Bands in Town Artist Events API for an artist and render the following 
information about each event to the terminal:

* Name of the venue 
* Venue location
* Date of the Event 


***screenshot:***
![bands](https://user-images.githubusercontent.com/52009314/66092854-97ddab80-e542-11e9-8678-b344ee79ec61.JPG)

## spotify-this-song:

This will show the following information about the song in your terminal/bash window

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from

If no song is provided then your program will default to **"The Sign" by Ace of Base.**

***screenshot:***
![song](https://user-images.githubusercontent.com/52009314/66095354-1ab73400-e54c-11e9-928e-279caa5be3ee.JPG)
## movie-this:

This will output the following information to your terminal/bash window:

* Title of the movie
* Year the movie came out
* IMDB Rating of the movie
* Rotten Tomatoes Rating of the movie
* Country where the movie was produce
* Language of the movie
* Plot of the movie
* Actors in the movie

If the user doesn't type a movie in, the program will output data for the movie **'Mr. Nobody.'**

***screenshot:***
![movie](https://user-images.githubusercontent.com/52009314/66092868-a6c45e00-e542-11e9-8115-c5ec575a04e7.JPG)

## do-what-it-says

Using the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of
**LIRI's commands.**

***screenshot:***
![dowhat](https://user-images.githubusercontent.com/52009314/66092858-9d3af600-e542-11e9-8fe6-c7365fdee61e.JPG)

## loging the usercommands
Loging all the user command in the text file.

***screenshot:***
![log](https://user-images.githubusercontent.com/52009314/66092862-a1ffaa00-e542-11e9-8115-e949787886cd.JPG)

## Usage
```
Launch project from any code editor i.e. Sublime, Atom, VS Code, etc.

Open app in any supported web browser i.e. Chrome, Firefox, Safari, etc.
```
## Technologies used

* Node.js
* javaScript
* jQuery
* axios

## Contributing
```
Pull requests are welcome. For major changes, please open an issue first to discuss what you
would like to change.
```
## History
```
This marks the end of unit 10 where we have learned Node.js fundamentals,as well as axios.
```
## Credits
```
The Coding Bootcamp @ University of Washington

Instructor: Joel Stedman & TA s : Nicklas Aaland, Austin Williams, Tassa
```

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Copyright
(c) [2019] [Prasamsha Sharma]
