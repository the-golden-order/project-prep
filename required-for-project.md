Technical merit is graded based on the following criteria:

### Front-End

- Good and proper use of React
  - Installed and configured using create-react-app
  - Clear, readable, and efficient structure
  - Proper use of ES6 Class Based Components, extending from `React.Component`
  - Managing component state using `this.state` and `this.setState`
  - Allow for user authentication via Auth0
  - Correctly passes props, identifying both shared state and behaviors (methods) to child components
  - Organized into nested components for DRY code

- Good and proper use of React-Bootstrap
  - Clear, readable, and efficient styles
  - Designed with a mobile-first approach

- Good and proper use of JavaScript and
  - Clear, readable, and efficient code
  - Uses domain models to encapsulate data and behavior, such as objects and constructors
  - Uses React to respond to user events, receive and process user input, and display new content to the user
  - Contains no unnecessary or commented-out code

- Deployed live on the Internet via Netlify

- Clear documentation in the README.md

### Back-End

- The project must utilize at least one third-party API

- Server side code must:
  - Use Node and Express, and other NPM packages as appropriate
  - Utilize a Mongo database as described in detail below
  - Routes should follow standard REST conventions
  - Implement authentication via Auth0

- Data is persisted in a Mongo database
  - Mongo database provisioned in the cloud
  - Logical schemas with appropriate data types
  - Data model that maps to the problem domain
  - Ability to read records from the database
  - Ability to create new resources and persist them in the database
  - Ability to update records in the database
  - Ability to delete records in the database

- Clear documentation in the README.md

- Generally useful and functional
  - The project must utilize a professional Netlify domain name
  - Works as expected with no bugs
  - Has at least three distinct pages with clear navigation, one of which must be an "About Us" page
  - Has at least two pages that accept and process user input
  - Deployed live on the Internet via Heroku

## Eden's First thoughts

*dead inside*  
Need 1 or more API's and the use of MongoDB
a fairly simple way to utilize this.. would be to connect to an API that randomly generates something for the user and allows them to save their favorites to the database 
Could be an "I'm bored" site that allows the user to pick between a couple of forms on entertainment: music, games, woodworking project, books, or short-term gratification memes and save the ones that interest them. 
Could potentially even have separate routes to the DB to keep the saved items separate, so on the users result page they can filter which topic the within their favorites to choose one to work on. 
I feel like we could start with two topics to start with 
say books and games and have that be our MVP, maybe also not having them separated within the DB would be MVP and separating them within the DB could be a stretch. 

### Alternatively. 

we could make a game, I've thought a lot about my previous project from 201 Codle, and how that could have been a 301 project. 
We could call to a database for terms to randomly generate and allow the user to save what words they guessed to the DB. Obviously I wouldn't want to do Codle again, but a similar idea for game making would be pretty simple in.. theory.. 
Something like hangman would be easy.. in theory 
Maybe an API that generates a word within a topic
allow the user to pick a topic
API calls to grab the word within that topic, and you guess till you get it or run out of tries. depending on the API the words could have definitions attached to them, could store the words a user has gotten and the definition of the word in the DB and allow the user to view those on a separate page. 

### Maybe

I had this idea for 201 but we could do a neat build your own adventure game, If we could find an API we could call to that would build small snippets of a story, like a sentence or two at a time, and display 2-3 options for the user to pick between, build out a story and save the story in the DB, could save multiple stories. Mayybe too simple, not totally sold on this

### Another game?

I imagine that building a sort of memory card game would also be relatively simple with react.. bring in an API to randomly generate cute animal pictures :) and then have the user match them based on flipping and memory? Who knows could work

## Thomas's First thoughts

I like Eden's "I'm bored" site idea and I think we could take it pretty far with the time we have

Some API's that we could use for that:
  -[https://www.boredapi.com/]
  -[https://www.freetogame.com/api-doc/]
  -[https://pprathameshmore.github.io/QuoteGarden/]
  -[https://picsum.photos/]

### Day off planner

An app that give's you random suggestions to do with your 'day off' based on location like restaurants to go to, entertainment, what movies are playing, concerts in the area and let's you save the suggestion's you like
  -[https://app.swaggerhub.com/apis/Bandsintown/PublicAPI/3.0.0]
  -[https://www.yelp.com/developers/documentation/v3]
  -[https://developer.movieglu.com/]

### Music Taste Portfolio

A portfolio website that allows you to search for music and showcase your music taste. Could have a page for favorite songs, favorite lyrics, and fav artists, upcoming events
  -[https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/]
  -[https://lyricsovh.docs.apiary.io/]
