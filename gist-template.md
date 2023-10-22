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
* `/^` this is the start of the string

### Quantifiers
* `([a-z0-9_\.-]+)` this is the username of the email address. this string consists of uppercase, lowercase and special characters such as underscores, hypens, etc.

### Grouping Constructs
*`+@` this will be the @ symbol which separates the username from the domain name.

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
