# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?
<!-- enter you answer in the space below -->
```
CRUD is an acronym that stands for: Create Read Update Delete
```
**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?
<!-- enter you answer in the space below -->
```
Create - Post /Read - Get / Update - Put / Delete - Delete
```
**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB
<!-- enter you answer in the space below -->
```
ORM stands for Object Relational Mapper. We use MONGOOSE!!!
```
**4.** Which two `HTTP` request types include a body?
<!-- enter you answer in the space below -->
```
The P's! Posts and Puts, they require a body! They take something "like a body" and put/post it in database.
```
**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.
<!-- enter you answer in the space below -->
```
Synchronous
Asynchronous 

```

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
<!-- enter you answer in the space below -->
```
Crazy as it sounds, one word is the answer for all the blanks. mongoose for all 3 answers, I left lowercase because that is how it is in code.
```
**7.** What is middleware?
<!-- enter you answer in the space below -->
```
A software that acts as a bridge between an operating system or database and applications, especially on a network. 
```
**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 
<!-- enter you answer in the space below -->
```
I have no clue. None of the readings or lectures hit on this. Google just want
```
**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.
<!-- enter you answer in the space below -->
```
?tag=winter
```