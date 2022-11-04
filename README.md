# Computer Science for JavaScript Challenge: Regex Tutorial
## Regular Expression Tutorial
This tutorial is meant to be a foundational reference guide for anyone learning regular expressions. We'll be referencing one specific regex throughout this tutorial that can be used to search for an email address such as "bob@gmail.com" and return a match if the structure of that email matches the criteria specified in the regex. We'll break down each component of our email regex and learning about the functionality of each part. By the end of this tutorial you will know what a regular expression is, when to use them and how to utilize each component.


### Summary
A regular expression or "regex" is a statement that describes a specific pattern of characters that can be searched for in a file or directory, matched and then returned to be utilized by a user or program to serve various use cases. The goal of each regex is to return a match for a continuous series of characters. The type of characters, number characters and order of characters can all be specified and modified inside the regex statement.

#### Table of Contents
* Regular Expression Tutorial
* Summary
* Table of Contents
* Regex for an email address
* Regex Components
+ Anchors
+ Quantifiers
+ Character Classes
+ Grouping and Capturing
##### Regex for an email address
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
*Structure of an email address:
The structure of a basic email address is split up into 3 main parts: the "user-name" and "domain-name" separated by an @ "At sign", then a . "dot" followed by the "domain-extension". The final address structure will look like this: (user-name)@(domain-name).(domain-extension) We'll reference these 3 parts throughout this tutorial.

