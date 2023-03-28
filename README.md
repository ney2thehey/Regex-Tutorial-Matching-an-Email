# Regex-Tutorial-Matching-an-Email

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Summary

In this challenge we are going to identify the different components that make up a regex for matching an email. 

Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
The anchors used in this regex expression is the "^", which is used to start the string, and "$", which is used to finish the string.

### Quantifiers

In this regex the quantifiers include the + operator as well as the {2,6}. These numbers show min and max range of characters allowed for sections of the string.


### Character Classes
In the context of regular expressions, a character class is a set of characters enclosed within square brackets. It specifies the characters that will successfully match a single character from a given input string.
For example, in this case, the \d means a range of digits (0-9).


### Grouping and Capturing
A total of three groups are being captured in this Regex for matching an email.The first is [a-z0-9_\.-] which is the username of the email. The second is [\da-z\.-] which is matching the type of email service . The third group being captured is [a-z\.]{2,6} which is the domain for example .com

### Bracket Expressions

There are also 3 bracket expressions in this regex. Whatever is inside the [] is what will be looked to be matched. 
The first expression is [a-z0-9_\.-] which includes all the characters from a-z, numbers 0-9, "_", ".", and "-".

The second expression is [\da-z\.-] which includes any digit 0-9, case sensitive characters  a-z, "." and "-".

The third expression is [a-z\.] which includes again characters from a-z (case sensitive) and ".".

### Greedy and Lazy Match

Greedy means match longest possible string. Lazy means match shortest possible string.
In thie case we have greedy quantifiers such as + and {}, which means it will match as many times as possible with no limit. 



### Back-references

### Look-ahead and Look-behind

## Author

  * Github: [ney2thehey](https://github.com/ney2thehey)