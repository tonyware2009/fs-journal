# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
create, read, update and delete.

```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
post
get
put/patch
delete

```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
Object Relational Mapping ORM refers to the mapping of persisted data, traditionally stored in an RDBMS, to objects used by the application. MongoDB's document-oriented architecture lends itself very well to ORM as the documents that it stores are essentially objects themselves
Mongoose is a Node. js library that helps in attaining goal of interacting with MongoDB through JavaScript. It is a ORM library of MongoDB for Node

```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
``` 
post
put

```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
synchronized 

asyncronized
```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
import schema from models

let schema = new schema

```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
Middleware is software that enables one or more kinds of communication or connectivity between two or more applications or application
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
<!-- NOTE im not sure what this question is refering to please help me understand -->
continous intigration

continous delivery

```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
<!-- NOTE i dont understand whaty this asking i understand the property tag but im not sure what kind of syntax can i please have an understanding what this is asking i wrote down what i think is was. -->

.get('api/winter')
```