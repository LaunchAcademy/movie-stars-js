1. I need a way to create a movie. Let's make a `createNewMovie` function to take care of this.

```js
let movie = createNewMovie("The Rock");
// then movie = { title: "The Rock" }
```

2. I also need a function to create an actor. This function should take in a `firstName` and `lastName`.

```js
let actor = createNewActor("Robin", "Williams");
// then actor = {firstName: "Robin", lastName: "Williams"}
```

3. An actor should have a `fullName` function which will return their first and last name combined.

```js
let actor = createNewActor("Robin", "Williams");
actor.firstName() = "Robin Williams"
```

4. A movie needs actors! Add a `cast` property to a movie which will allow it to hold a list of actors. There should also bee an `addCastMember` function which can add an actor to the `cast` list.

5. I want to see a list of all the cast members in a movie. Add a `listCastMembers` function that will log each cast members full name to the console.

6. With so many actors it's easy to lose track of who is in what movie. Let's add an `isStarring` function to a movie that will take in an `actor` as an argument and return true if they are in the movie and false otherwise.
