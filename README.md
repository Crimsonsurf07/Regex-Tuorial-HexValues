# Regex-Tuorial-HexValues



Regex Expressions have a multitidue of use cases including `parsing strings` by converting data to alternate formats and the ability to utilize `web scraping`.



## Summary

Regex or Regexp are very useful for extracting information from `any text` by searching for matching criteria or a specified search pattern being implemented

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

Anchors such as `^` and `$` 
`^` doesn't match a particular character but rather `matches the beginning` of the text in a string. The position changes with `$`  as this actuallly matches the end of the text in a string

### Quantifiers

`*``+``?``{n}``{n,}``{n,m}`
Quantifiers such as  are used to identify how frequent either a character, a group, or even a character class `must` be present in a string for a match to be found.

`*` match 0 or more times
`+` Match one or more times.
`?` Match zero or one time.
`{ n }` Match exactly n times.
`{ n ,}` Match at least n times.
`{ n , m }` Match from n to m times.


### Character Classes

This is used to determine 1 character type from another such as the +	Match one or more times.
?	Match zero or one time.
{ n }	Match exactly n times.
{ n ,}	Match at least n times.
{ n , m }	Match from n to m times.between letters and numbers.

### Flags

`i``g``s``m``y``u`
A `flag` is an optional parameter to a regex that modifies its behavior of searching. `Flags` can be identified by a single alphabetic character.

`i` = Ignore casing: is for an making an expression search case insensitively
`g` = Global: includes all occurances
`s` = Dot All: . is considered a wild card which matches newlines 
`m` = Multiline: makes the `^` and `$` match the beginning and end of each line rather than just the beginning and the end of a String.
`y` = Sticky: starts the search from the index inidicated in its `lastIndex` property.
`u` = Unicode: able to match 32-bit characters


### Bracket Expressions
`[]`

Bracket Expressions are used to match a set of characters. These can be both aplhabetical and/or numerical

### Greedy and Lazy Match

`Greedy Matches` try matching an element as many times as it possibly can while `Lazy Matches` do the opposite.

### Boundaries

`\b`
Whenever a Regexp locates a `\b`in a String, it checks the position to see if that position in a String is a word boundary

### Back-references
`\1` is an example which would match an exact same text matched by the first capturing group
Used to match the same text as previously matched by a caputuring group.

### Look-ahead and Look-behind

Also known or referred to as "lookaround". Used when you want to find only the matches for a pattern that are followed OR preceded by another pattern.

## Author

My names Tony, and i'm an aspiring web development student looking for a new career path.
