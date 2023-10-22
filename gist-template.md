# Using Regex for Email Validation

In this tutorial, we will see how to use Regex to validate email addresses. Getting to understand Regex is very beneficial as it wil help you learn how to work with other types of data.

## Summary

We will focus on the specific pattern for validating email addresses such as the code snippet below.

* Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
* `/^ and $/` this is the start (^) and the end ($) of the string

### Quantifiers
* `2,6` this is identifying that the end of the string is between 2 and 6 characters long, things like ".com", ".net", etc.

### Grouping Constructs
* Grouping will allow you to group strings of information together such as numbers and letters so that it can check for multple expressions at the same time.

### Bracket Expressions
* `a-z0-9_\.-` this string is searching for characters from a-z, 0-9 and special characters. this is looking for lower case letters only, it can contain any number between 0-9, as well as any special character.

### Character Classes
* This is defining a set of characters such as a-z or 0-9 to find the match within the email that is being searched for.

### The OR Operator
* the OR operator would search for alphanumeric results which can also be found using ":" 

### Flags
* Flags will identify additional functionality AFTER the regex code. which have multiple typesof searches.

### Character Escapes
* This is the `\` found throughout the string that will take you to the next set or bit of information in the string.
 
## Author

This tutorial is by Devin Hill, a current Student learning Full Stack Web-Development. You can find more of my work on my Github Profile: https://github.com/Devinmarshill
