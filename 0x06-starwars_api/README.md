# 0x06. Star Wars API

### Project Details

- **Project Start Date**: Aug 5, 2024, 6:00 AM
- **Project End Date**: Aug 9, 2024, 6:00 AM
- **Checker Release Date**: Aug 6, 2024, 6:00 AM
- **Auto Review**: At the deadline

## Project Overview

The "0. Star Wars Characters" project requires you to interact with the Star Wars API to fetch and display information about Star Wars characters based on the provided movie ID. This project will test your ability to work with external APIs, manage asynchronous operations, and handle command-line arguments in Node.js.

## Concepts Needed

1. **HTTP Requests in JavaScript**
   - Understand how to make HTTP requests using the `request` module or alternatives like `fetch` in Node.js.
   - [A Complete Guide to Making HTTP Requests in Node.js](https://www.example.com)

2. **Working with APIs**
   - Basics of RESTful APIs and how to interact with them.
   - Parsing JSON data returned by APIs.
   - [Working with APIs in JavaScript](https://www.example.com)

3. **Asynchronous Programming**
   - Manage asynchronous operations with callbacks, promises, and `async/await` syntax.
   - Handle API response data asynchronously.
   - [Asynchronous Programming in JavaScript](https://www.example.com)

4. **Command Line Arguments in Node.js**
   - Use `process.argv` to access command-line arguments passed to a Node.js script.
   - [How to Parse Command Line Arguments in Node.js](https://www.example.com)

5. **Array Manipulation and Iteration**
   - Iterate over arrays and manipulate data structures to format and display character names.
   - [JavaScript Array Methods](https://www.example.com)

## Installation and Setup

1. **Install Node.js 10**

   ```bash
   $ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
   $ sudo apt-get install -y nodejs
   ```

2. **Install semi-standard**

   ```bash
   $ sudo npm install semistandard --global
   ```

3. **Install `request` module**

   ```bash
   $ sudo npm install request --global
   $ export NODE_PATH=/usr/lib/node_modules
   ```

## Tasks

### 0. Star Wars Characters

**Mandatory**

- **Objective**: Write a script that prints all characters of a Star Wars movie.
- **Usage**: The first positional argument passed is the Movie ID. For example, `3` = “Return of the Jedi”.
- **Output**: Display one character name per line in the same order as the “characters” list in the `/films/` endpoint.
- **Requirements**:
  - Use the Star Wars API.
  - Use the `request` module.

**Example Usage**:

```bash
alexa@ubuntu:~/0x06$ ./0-starwars_characters.js 3
Luke Skywalker
C-3PO
R2-D2
Darth Vader
Leia Organa
Obi-Wan Kenobi
Chewbacca
Han Solo
Jabba Desilijic Tiure
Wedge Antilles
Yoda
Palpatine
Boba Fett
Lando Calrissian
Ackbar
Mon Mothma
Arvel Crynyd
Wicket Systri Warrick
Nien Nunb
Bib Fortuna
alexa@ubuntu:~/0x06$
```
