# Node.js Basic
## What is Node.js?
Node.js is an open source server environment <br />
Node.js is free <br />
Node.js runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.) <br />
Node.js uses JavaScript on the server <br />

## Download
Download Node.js from the official Node.js web site: https://nodejs.org

## How to Run?
Run program from CLI: Node ProgramName.js



## Why Node.js?
Node.js uses asynchronous programming! <br />

A common task for a web server can be to open a file on the server and return the content to the client. <br />

### Here is how PHP or ASP handles a file request: 
Sends the task to the computer's file system. <br />
Waits while the file system opens and reads the file. <br />
Returns the content to the client. <br />
Ready to handle the next request. <br />

### Here is how Node.js handles a file request:
Sends the task to the computer's file system. <br />
Ready to handle the next request. <br />
When the file system has opened and read the file, the server returns the content to the client. <br />
Node.js eliminates the waiting, and simply continues with the next request. <br />

## Node.js runs single-threaded, non-blocking, asynchronously programming, which is very memory efficient.

## What Can Node.js Do? 
Node.js can generate dynamic page content
Node.js can create, open, read, write, delete, and close files on the server
Node.js can collect form data
Node.js can add, delete, modify data in your database

## What is a Node.js File?
Node.js files contain tasks that will be executed on certain events
A typical event is someone trying to access a port on the server
Node.js files must be initiated on the server before having any effect
Node.js files have extension ".js"

