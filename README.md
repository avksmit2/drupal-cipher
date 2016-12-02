# Cipher

###_A website that receives a phrase from the user and encrypts it._ {December 2, 2016}

### By _**Angela Smith**_

## Description

_A drupal site with a module including a form for a user to input a shift and direction value, and a phrase to encrypt based on the values entered for shift and direction._

## Specification

| Behavior          | Input    | Output |
| ----------------- | -------- | ------ |
| the result will be in all lower case | "A" "left" 1 | "z" |
| spaces, punctuation and numbers will be ignored | "a1_/" "left" 1 | "z1_/" |
| a letter will be returned based on the shift and direction value | "a" "left" 1 | "z" |
| if the end of the alphabet is reached, it will go back to the beginning | "a" "left" 1 | "z" |

## Prerequisites

You will need MAMP/WAMP properly installed on your computer.

## Installation

* `git clone <repository-url>` this repository
* Import the `cipher.sql.zip` file into MySQL
* Create a database account (`cipher`, password: `cipher`) in MySQL and grant it full access to the database
* Set MAMP/WAMP's webserver directory to the project folder
* Navigate to localhost:8888 (or whatever local server settings you have for MAMP/WAMP)
* Site maintenance user: `cipher`, password: `cipher`

## Technologies used

_CSS,
PHP,
MySQL,
Drupal

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2016 _**Angela Smith**_
