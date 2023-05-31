# Regex-Tutorial

## Summary
This tutorial will able to go show you guys and able to make you guys understadn the components of a regex (Regular Expression) and how it could be applied to matching an email. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors
'^' is the anchor used in this regex expression. This anchor means that it's beginning of the string. 
'$' is a meanning of ending of the string. '(m)' or knows as mulitline is not enable in this regex with means that all regex will end with '$'.

### Quantifiers
'+' is the operator for quantifiers. This will allow to connect any emails name/email service/.com/etc/ For example it could be email name + email service + '.com'. Also other methods could be used is {_,_}. For example if we put {2,6}, this allow the match range to be 2-6 and we could also input charcters instead of numbers. 

### Character Classes
'/d' is the charcter c;ass that is used. It allows to match a single charcters that could be any numbers between 0-9. Also it only allows to match single digit numbers so any double digit number would not work. 

### Grouping and Capturing
To group this expression, '([a-z0-9_\.-]+)' will allow us to match the user email name, second group is '([da-z\.-]+)' allow us to match the email service, and lastely the third group will "([a-z\.]{2-6})' to add the '.com'.

### Greedy and Lazy Match
For email regex, we have greedy matches. This allows us to use '+' Quantifiers, it will allow us to match many times as possible. Another Quantifiers we can use is '{}; when we are matching the numbers for the last group. 

### Bracket Expressions
So if we have '([a-z0-9_\.-]-)', this shows matching any letter a-z and us case senstive. It also allows to match charcters from 0-9 and charcters "-","-",".";


## Author

This Regex was created by Robert Lee. All of my other works could be seen [here](http://github.com/rlee7029)
