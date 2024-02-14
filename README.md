# takes-a-village
(RegexTutorial)
# Tutorial for matching an email

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/i. Replace this text with your summary.

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
- ^ (This mathces the begining of the string)
- $ (This mathces the end of the string)

### Quantifiers
- `+` (Matches one or more of preceeding token) 
- {2,6} (Matches between 2 and 6 of preceding token)

### OR Operator
N/A

### Character Classes
- a-z (matches character in rqnge a-z, case sensitive)
- 0-9 (matches character in rqnge 0-9)
- /d (matches character in rqnge 0-9)

### Flags
- i (case insensitive)

### Grouping and Capturing
- ([a-z0-9_\.-]+) (Matches one or more characters a-z, 0-9,_, .or-)
- ([\da-z\.-]+) (Matches one or more characters 0-9, a-z, ., or -)
- [a-z\.]{2,6}) (Matches between 2  or 6 characters a-z or .)

### Bracket Expressions
- [a-z0-9_\.-] (Matches characters a-z, 0-9,_, .or-)
- [\da-z\.-] (Matches characters 0-9, a-z, ., or -)
- [a-z\.] (Matches characters a-z or .)

### Greedy and Lazy Match
N/A

### Boundaries
N/A

### Back-references
N/A

### Look-ahead and Look-behind
N/A

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)