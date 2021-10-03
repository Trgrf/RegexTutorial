# Regex Tutorial

This Tutorial will explain the regex that is used to match emails. The expression for this regex is  /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This is useful when validating emails for applications that use Node(inqurier) or MongoDB.

## Summary

A regular expression is a sequence of characters that defines a search pattern. This is commonly used to find patterns within a string, find/replace characters within a string or validate an input. This tutortial will go walk through the components of a regex that is used for matching an email.

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

The anchors within this regex expression are the ^ and $ symbols, ^ refers to the beginning of the string while the dollar sign refers to the strings ending. The (m) known as the multiline is not enabled within this regex expression so the expression ends at the dollar sign.

### Quantifiers

Quantifiers in this regex includes the + operator, which connects the users email name + email service + .com. Another quantifier for this regex includes {2,6}, which will allow a match range between 2-6 characters for the character set of [a-z\.].

### Grouping Constructs

There are three groups within this expression. Group #1 is ([a-z0-9_\.-]+) which is responsible for beginning of an email adress such as adam. Group #2 is ([\da-z\.-]+) is responsible for the email service a user is using such as gmail. Finally we have Group #3 ([a-z\.]{2,6}) which is responsible for the .com. By using the + operator the expression would turn out as adam@gmail.com

### Character Classes

The character class in this expression is \d, which matches a single digit that is a digit from 0-9. But it will only match a single digit such as "7", but not "77".

### Bracket Expressions

Bracket expressios for email validation in this regex have 3 groups as well. The first bracket set is [a-z0-9_\.-], which is matching any letter from a to z and is case senstive. It also matches any number between 0-9 and finally will match the symbols "_" , "-" , and ".". The second bracket set is [\da-z\.-], which matches a single digit from 0-9, any letter from a to z (case senstive), and the symbols "." and "-". The thrid bracket set is [a-z\.] matches any letter from a to z(case senstive) and the symbol ".".

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
