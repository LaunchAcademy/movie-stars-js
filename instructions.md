# instructions

1. I need a way to create a movie. Let's make a `createNewMovie` function to take care of this. It should take in a single argument of a movies `title` and return an object with a `title` property. This should exist in it's own `createNewMovie.js` file.

```js
// main.js
let movie = createNewMovie("The Rock")
// then movie = { title: "The Rock" }
```

2. I also need a function to create an actor. This function should take in a `firstName` and `lastName`. It should also exist in it's own file.

```js
// main.js
let actor = createNewActor("Robin", "Williams")
// then actor = {firstName: "Robin", lastName: "Williams"}
```

3. An actor should have a `fullName` method which will return their first and last name combined.

```js
let actor = createNewActor("Robin", "Williams")
actor.firstName() = "Robin Williams"
```

4. A movie needs actors! Add a `cast` property to a movie which will allow it to hold a list of actors. This should initialize as an empty array. There should also be an `addCastMember` method which can add an actor to the `cast` list.

5. I want to see a list of all the cast members in a movie. Add a `listCastMembers` method to the `createNewMovie` object that will log each cast members full name to the console.

6. With so many actors it's easy to lose track of who is in what movie. Let's add an `isStarring` method to a movie that will take in an `actor` as an argument and return true if they are in the movie and false otherwise. 
