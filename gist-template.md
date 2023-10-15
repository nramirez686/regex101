# Regex 101

In this tutorial, we'll explore how to use regular expressions (regex) to match email addresses. Regular expressions are powerful tools for search pattern in a body of text.

## Tutorial Summary

In this tutorial, we will delve into a specific regular expression used for matching email addresses:
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
This regular expression ensures that user input is a valid email address. We will break down each component of this regex and explain its purpose.

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

Anchors match starting and ending points of a string or line.
A caret or ^ can be used to match the beginning of a string and the dollar sign $ can be used to match the end of the string.

<u>Example:</u>

`^abc` matches "abc" only if it appears at the begginig of a the line.
xyz$ matches "xyz" only if it appears at the end of the line.

### Quantifiers

Quantifiers allow the specification of how many characters or character classes should be matched. They allow control in the repetition of patterns.

`*` - this quanifier matches zero or more occurrences of whatever preceeding character or group.<br>
`+` - this quantifier matches one or more occurances of the proceding character or group.<br>
`?` - this quantifier matches zero or more occurances of the proceding character or group. <br><br>
`({m,})` - this quantifier is more specific and will match m to n occurances.
<u>Example:</u>
<br><br>
`a*` will match a, aa aaa and so on.<br>
`a+` will match a, aa, aaa and so on but not an empty string.<br>
`a?` will match a, or an empty string.<br>
`({2,4})` will match 2, 3, 4.

### OR Operator

Operator, also called alteration allows matching one of several patters. <br>
It is defined by using the ( | ) character.
<br><br>
<u>Examples:</u>
<br><br>
patter1 | pattern2

### Character Classes

Character classes distingush kinds of characters, like telling apart letters and digits.
A character class matches any of the characters enclosed in brackets, but if a hyphen (-) appears as the first or last character enclosed in the brackets, it will be taken as a litereal hyphen and it will be included in the character class.

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Nancy Ramirez - UTA Full stack coding bookcamp student
[GitHub Profile](https://github.com/nramirez686)
