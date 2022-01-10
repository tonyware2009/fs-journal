# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
Synchronous basically means that you can only execute one thing at a time. Asynchronous means that you can execute multiple things at a time and you don't have to finish executing the current thing in order to move on to next one
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Open closed Principle.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A callback function is a function that is passed as an argument to another function, to be “called back” at a later time. A function that accepts other functions as arguments is called a higher-order function, which contains the logic for when the callback function gets executed


A higher-order function is a function that takes another function(s) as an argument(s) and/or returns a function to its callers. A callback function is a function that is passed to another function with the expectation that the other function will call it.

```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```Promise means that a program calls a function in the anticipation that it will do some useful thing and return the result which calling program can use. The result or promise is the outcome of calling the function which can be a success or a failure, and the data associated with it

the executor automatically catches the error and turns it into rejected promise. This happens not only in the executor function, but in its handlers as well. If we throw inside a . then handler, that means a rejected promise, so the control jumps to the nearest error handler.

```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
What are the 3 main parts of an HTTP request?
An HTTP request is divided into three parts: Request line, header and body. An HTTP response is also divided into three parts: Status line, header and body.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
controller.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Encapsulation allows you to hide specific information and control access to the internal state of the object. 
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
Successful responses ( 200 – 299 )

```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
Internal Server Error
```