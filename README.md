# dict

This program lets you search your Unix dictionary with a regex (PCRE).

Want to see words that have more than two vowels in a row? Try this:
```
$ dict -S '[aeiou]{3,}'
```

`-S` gets rid of the default behavior of matching a pattern from start. In regex terms, `-S` removes an implicit `^` anchor.

`-f` makes `dict` match the pattern at the end of the word.

`-i` turns on case-insensitivity.
