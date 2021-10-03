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

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
