# 1234-golf
Code golfing contest: print "1234".

# Rules
- Any language is allowed.
- The rules may be changed at any moment to patch loophole abusers. >:P
- The program must print the exact string "1234". No other non-whitespace characters are allowed. Everything must be on the same line, with no whitespace between the digits.
- Single and double quotes (' and ") are banned in the source code.
- Digits (0, 1, 2, 3, 4, 5, 6, 7, 8, 9) are banned as well in the source code.
- The smaller the character count in the program, the better. Whitespace characters are not counted, including newlines.
- Characters in comments aren't counted, either. Comment your code all you like.
- Any program that does not follow the following strict rules will go into the "troll" category.

## Strict rules
- The program must suffice to itself. No arguments, external files (unless generated by the program), etc.
- The program's execution must be deterministic.
- The program should not require any user input besides starting it.

## Exotic languages
"Exotic" (and esoteric) languages will go into the `exotic` directory.

## Per-language rules
### C, C++
- Everything must be printed to `stdout`.
- No extenal libs are allowed; `<stdio.h>` and consorts are allowed, but any custom lib violates the "suffice to itself" rule.
- The code should run it [Coliru](http://coliru.stacked-crooked.com/) with the following command: `g++ -std=c++17 main.cpp && ./a.out`. Other options allowed at the judges' discretion.

### JavaScript
- Everything must be printed through `console.log`.
- Backticks (\`) are explicitly allowed.
- Currently we're allowing any context. If it works in some browser (without extensions) or Node, it should be accepted. This may change.


# Submissions

Open an issue and submit your code. We'll see in which category it goes, if it complies with the rules, and if we need to change them (again :^) ).

PRs are fine, too.


# License

You're allowed to freely re-use these bits of code. You probably shouldn't, though.
