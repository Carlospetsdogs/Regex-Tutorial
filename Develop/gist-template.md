# Regex Tutorial Showcase!

The purpose of this assignment is to educate users on how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does.

## Summary

The following regex (  ^\d{4}-\d{2}-\d{2}$  ) effectively ensures that an entire string matches the YYYY-MM-DD date format, with exactly four digits for the year, two digits for the month, and two digits for the day, separated by hyphens and with no additional characters before or after the date.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Literals](#literals)
- [Boundaries](#boundaries)

## Regex Components

### Anchors

Anchors are used to match positions within a string. The regex `^` asserts the position at the start of a line, and `$` asserts the position at the end of a line.

### Quantifiers

Quantifiers specify the number of occurrences of a character or group. In this regex, `\d{4}` specifies exactly four digits, and `\d{2}` specifies exactly two digits.

### Character Classes

Character classes match any one of a set of characters. `\d` is a shorthand for the character class `[0-9]`, which matches any single digit.

### Literals

Literals match the exact characters specified. The hyphens (`-`) in the regex are literals that match the hyphen character.

### Boundaries

Boundaries ensure that the match occurs at the specified positions within the string. The `^` and `$` anchors are used to assert that the match must occur at the beginning and end of the string, respectively.

## Author
Carlos Ruiz - amateur developer, husband, dog dad, musician, gamer.
### Github profile
https://github.com/Carlospetsdogs
