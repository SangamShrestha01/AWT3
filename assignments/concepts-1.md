# HTTP MEthods
The different types of request that the client can make to the server is called HTTP methods.The different HTTP methods are GET, POST, PUT, DELETE, etc.
**********
1.**GET**

The GET method is used to retrieve data from a specified server/source.For example: `/users`fetch an array of users data.

2.POST

The POST method is used submit data to the server (e.g., form submission or creating a resource).

3.PUT

PUT method is used to 	update or replace a resource entirely.

4.DELETE

DELETE method is used to delete a resource/data from the server. DELETE:`/users` or can have additional data as `/$user-id`
*******
## HTTP Status code
These indicate the result of the HTTP request.

### 1. 2xx:Success

Used when the request was successfull.

200 OK: Request succeeded.

201 Created: New resource created.

204 No Content: Success, but no content returned.
### 2. 4xx:Client Error
Used when there is something error in the client side.

400 Bad Request: Invalid request syntax.

401 Unauthorized: Authentication required or failed.

403 Forbidden: Authenticated but no permission.

404 Not Found: Resource not found.


### 3. 5xx:Server Error

used when the error is on the server side.

501 Not Implemented: Method not supported by server.

502 Bad Gateway: Invalid response from upstream server.

503 Service Unavailable: Server is down or overloaded.
*******
## CSS Selectors

Used to add styles to the specific parts.

## 1. Universal selector

Selects all elements.
`* {
  margin: 0;
  padding: 0;
}
`
## 2. Type selector 

Targets all elements of a specific type.
`p {
  font-size: 16px;
  color: gray;
}
`
## 3. Class selector

Targets elements with a specific class.

Symbol(. classname)

`.box {
  border: 1px solid black;
  padding: 10px;
}
`
## 4. ID selector
Targets a specific element with a unique ID.

Symbol(# id)

`#title {
  color: blue;
  text-align: center;
}
`
********
## Git Basics

### 1.init

Start a new Git repository

`git init`
### 2.add

used to add changed files.

`git add filename`
### 3.commit

Save changes with a message. It lets know what is changed and when.

`git commit -m "message"`
### 4.push

Upload local commits to remote repo

`git push `
### 5.pull

Download changes from remote repo

`git pull`
### 6.clone

used to copy an existing repository.

`git clone repository url`
### 7.branch

Branch are in simple word the copies of project where multiple people can work without disturbing another.

`git branch branch-name`
******

## Callback Fucntions
`A function that is passed to another function to be executed later.`

## High Order functions
`A function that takes another function as a parameter or returns a function.`

*****
## Array Methods
filter() – Creates a new array with items that pass a condition.

map() – Creates a new array by transforming each item.

forEach() – Runs a function on each item (no return).

push() – Adds an item to the end of the array.

pop() – Removes the last item from the array.



