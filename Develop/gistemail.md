# Week 17 Regex for matching emails 

## Summary

Matching an Email with a Regular Expression - Learn the power of regular expressions by exploring how to match email addresses. We'll also dissect key regex components."

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
Anchors, like the caret (^) and dollar sign ($), specify the start or end of a string. They help define word boundaries. Keep in mind that regex can vary between programming languages, so it's essential to refer to language-specific documentation. Quantifiers, such as *, +, and {3}, determine repetition
### Quantifiers
"Quantifiers in regex, such as ?, *, +, and {}, determine how many times something occurs. They can be eager or reluctant, depending on character placement. You can hover over parts of an expression to understand their purpose. For more details, W3Schools provides descriptions starting with 'matches any string with' or 'matches any string that' for quantifiers.
### OR Operator
 Alternation in regex uses the '|' symbol as a simple 'OR'. For example, to find 'a1,' 'b2,' or 'c3,' use 'a1|b2|c3
### Character Classes
Character classes, like A-Z or a-z, match any character within a specified range, such as all letters from A to Z or a to z, and it can apply to numbers too.
### Flags
Regular expressions come with six optional flags that help with tasks like searching everywhere in a text. These flags can be used alone or together, and they are part of the special code used for these searches.
### Grouping and Capturing
In this code,([a-z0-9_.-]+) captures the user's email name, the second part ([\da-z.-]+) captures the email service, and the ([a-z.]{2,6}) captures the .com part.
### Bracket Expressions
    [a-z0-9_.-]: Matching any case-sensitive letter from a to z, any digit from 0 to 9, and the characters "_", "-", and ".".

    [\da-z.-]: Matching a single digit from 0 to 9, any case-sensitive letter from a to z, and the characters "." and "-".

    [a-z.]: Matching any case-sensitive letter from a to z and the character ".".
### Greedy and Lazy Match
This regex utilizes greedy matching. The "+" quantifier ensures it matches as extensively as possible, providing back as required. Additionally, the "{}" quantifier in {2,6} for the final capture group is another example of greedy quantification.

## Author
Corey Obiri
Github: Github.com/Coreyish
2023