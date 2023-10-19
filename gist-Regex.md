# Regex Tutorial
Regex, or regular expression, is a method for matching data patterns such as emails or phone numbers. It involves searching for specific patterns within the text.


## Summary
Today, I'd like to delve into the world of regular expressions used for validating email addresses. Email addresses are incredibly common, and understanding how to work with them using regular expressions can be quite valuable. One such regular expression for validating email addresses is as follows.
^(([^<>()[]\.,;:\s@"]+(.[^<>()[]\.,;:\s@"]+)*)|.(".+"))@(([[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}.[0-9]{1,3}])|(([a-zA-Z-0-9]+.)+[a-zA-Z]{2,}))$

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
\b/
Word Boundary Anchor - It matches the position where a word begins or ends. For example, \bword\b will match "word" but not "subword" or "wordy."
### Quantifiers

### OR Operator
The OR operator in regular expressions (regex), represented as |, is a metacharacter that allows you to specify multiple alternative patterns within a single regex pattern. It matches any one of the defined alternatives in the input text.
### Character Classes
Regex Character Classes are a way to match a single character from a set of characters. They are enclosed in square brackets, like [abc], and match any character within the brackets.
### Flags

Regex flags are modifiers that you can add to a regular expression pattern to change how the pattern is matched. They control aspects like case sensitivity, global matching, and more.
### Grouping and Capturing
Grouping: Parentheses are used to group parts of a regular expression. This is useful when you want to apply a quantifier (such as *, +, ?, {n}, etc.) to a specific sub-pattern. For example, (abc)+ matches one or more occurrences of "abc" as a single unit.

Capturing: When you use parentheses to create a group, you can also capture the text that matches that group for later use. Each captured group is assigned a number, starting from 1. You can refer to these captured groups by their number or name in your regular expression or in the code that uses the regex.
### Bracket Expressions
[\w\.-]+@[\w\.-]+
### Greedy and Lazy Match
 bracket expressions are used to define a set of characters or character ranges that you want to match within a text. They are enclosed in square brackets and allow you to specify which characters you're looking for in a particular position.
### Boundaries
Regex boundaries are special characters or assertions used to define the limits or positions within a string where a match should occur. They help specify the start, end, or word boundaries within a text for more precise pattern matching.
### Back-references
Regex back-references are placeholders that refer to previously captured groups in a regular expression pattern. They allow you to match the same text that was previously captured, enhancing the ability to find repeated patterns in the text.
### Look-ahead and Look-behind
Regex look-ahead and look-behind are assertions that allow you to check for the presence or absence of certain patterns before or after the main matching pattern, without including them in the match itself. Look-ahead checks what follows, while look-behind checks what precedes the main pattern, helping you to create more complex matching conditions in regular expressions.
## Author
https://github.com/jonschlinkert/author-regex
