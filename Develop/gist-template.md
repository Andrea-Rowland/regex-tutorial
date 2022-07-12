# Title (replace with your title)

Regex Tutorial for Matching an Email

## Summary

This tutorial explains how to use a regular expression (a.k.a. regex) to match emails. This is helpful for when you need to validate whether an email matches. The regex code being explained is: 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

The ^ symbol designates the beginning of the the string, while the $ symbol shows where the string ends.

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

The parentheses () separate the expression into smaller groups. 
    ([a-z0-9_\.-]+) matches the username 
    ([\da-z\.-]+) matches the email server
    ([a-z\.]{2,6}) will match the domain name of the email (for example, .com or .edu)

### Bracket Expressions

The [] symbols in this expression group items and indicate what will be allowed to appear in that specific section. Here is an explanation of the first bracket section in the expression: [a-z0-9_\.-] matches any character a-z, 0-9 and matches "_", ".", and "-". The second bracket section, [\da-z\.-] matches any character a-z, ".", and "-". The third bracket, [a-z\.] matches any character a-z and ".".

### Greedy and Lazy Match

### Boundaries

The forward slash (/) character is used to denote the boundaries of the regular expression

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
