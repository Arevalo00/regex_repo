# Regex Info Page 

Regex, or regular expression, is a way you can match data like emails or phone numbers. Its done by being able to look for patterns in the expressions. 

## Summary


 /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)|.(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/


Today I would like to explore emails as regex, I feel that this is a very useful. Emails are super commen so I feel it could be intresting to look into this further. 

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

/^J/.test(str)

The anchors in regex are the start and end points, which help define what the rexgex is going to match with. That way its able to match the correct infomation. 

### Quantifiers

/10*/g; whole number

Quantifiers are important to regex b/c they set the number of characters that will be tracked and matched. This is so helpful b/c you can set diffenet qauntifiers many to catch different kinds of data. 

### OR Operator

With the OR operator, you can find either or options that you set with your regex. You can do this with the pipe |, this can be helpful with complex data. 

### Character Classes

Character classes, are helpful in making sure the right data is being matched. This can be seen with back slashes which can be good to specifiy the data.


### Flags

Flags are a way of looking for certin data, with ?i, one thing you can look for is upper or lower case. With this you could look for certin kinds of names or usernames. 

### Grouping and Capturing

 /^(([^<>()[\]\\.,;:\s@"]+(\.[^<>()[\]\\.,;:\s@"]+)*)

Grouping can be done with (), this will group all the regex that you need to match your expresstion. It also helps with readablity, and helps separate diffient groups. 

### Bracket Expressions

[^<>()[\]

Bracket expressions are used in regex groups to help separet different parts of the regex. Like in this part of the email regex, its a small part but 


### Greedy and Lazy Match

There differnt kinds of matches a greedy match looks for all the matches that it can possibly make. However a lazy match looks for the frist one that matches and stops looking after that. 

### Boundaries


### Back-references

### Look-ahead and Look-behind



