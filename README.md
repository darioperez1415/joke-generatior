# Get Jokes
[![Netlify Status](https://api.netlify.com/api/v1/badges/339c4ae9-fc7f-41b4-9b49-2dab0a20eaba/deploy-status)](https://app.netlify.com/sites/dp-joke-generator/deploys)

[View App](https://dp-joke-generator.netlify.app/)

## Get Started 
```
$ git clone git@github.com:darioperez1415/joke-generatior.git
$ cd joke-generator
```
## About the User
- The user can get random tech jokes! 

## Features 
- Text appears on open displaying Joke Generator with a button below that says "Get a Joke"
- When the user presses the button, an API call is made, and the joke setup appears on the DOM
- The button changes to "Get Punchline"
- When a user presses the button, both the joke setup and delivery are on the DOM
- The button changes to "Get Another Joke," and the app starts over
- The user can choose to get another joke if the first joke was not funny

## Code Snippet <!-- OPTIONAL, but doesn't hurt -->
Asyn/Await promise.
```
import axios from 'axios';

const endpoint = 'https://v2.jokeapi.dev/joke/Programming?safe-mode&type=twopart';

const getJoke = async () => {
  const jokeCall = await axios.get(endpoint);

  return jokeCall.data;
};

export default getJoke;
```
## Project Screenshots 
![joke-Generator](https://user-images.githubusercontent.com/83309084/144684099-ed4b09ea-a411-4102-bc2d-b65827f7a318.png)
