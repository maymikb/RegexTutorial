# takes-a-village
(RegexTutorial)
# Tutorial for matching an email

  ## Introdution
As a student, I have really come to appreciate the tech community as a whole. I have learned a lot from tutorials (in text and video form) from others that are just starting out like myself. I also learn a lot from people with more experience, people who have seen developments  over time, and both are helpful because there are constant advances in technology.
  Although there are many platforms for tech tutorials, which have also shown me the creative side of the community, the motivation for this Regex tutorial is to contribute, while also growing as a student. Different platforms allow for different points of view, and often it is helpful to get another perspective (someone’s explanation may be easier to grasp for some than others, or it may be useful to find someone who is using the same operating system), especially since there are usually a number of ways to write and debug code.  
   This is a tutorial for matching an email, and each part of the expression is broken down with explanations. 

## Summary
This is a tutorial for matching an email, and each part of the expression is broken down with explanations. The Regex is essentially translated into English that speakers can interpret, not just coders. The verification code is broken down into sections, which are then further broken down and defined, and easily accessible via the table of contents.


Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/i. Replace this text with your summary.

## Table of Contents

- [Introduction](#introduction)
- [Summary](#summary)
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
- [Author](#author)


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

The author of this tutorial is a polyglot and former elementary school teacher who is now a current coding student seeking future opportunities in Software development. As a Silicon Valley resident, Maymi Sarr is eager to continue learning and is looking forward to keeping up with updates and new developments in technology.
