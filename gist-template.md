# HyperScan
This is a multiple regex matching library. It follows standard regex but Hyperscan is a standalone. Hyperscan is a part of intel. 

## Summary

Hyperscan allows you to simulatenously match large numbers of regular expression. There is hscheck section that allows to check whether Hyperscan supports a group of patterns. 

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
Hyperscan is a software regex matching engine that has two components compliation & scanning. 
### Anchors
There are two types of anchors, first is a caret ^ and the second is a $
### Quantifiers

### Grouping Constructs
Hyperscan can handle many constructs. For example: 
/[Aa][Bb][Cc]/
/[A|a][B|b][C|c]/
/(?i)abc(?-i)/
/abc/i
### Bracket Expressions

### Character Classes

### The OR Operator

### Flags
- Dot all mode
- Single match flag
- Start of match flag
- Approximate matching

### Character Escapes

## Author
https://github.com/intel/hyperscan

