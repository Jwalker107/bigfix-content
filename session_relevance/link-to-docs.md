

## Types:

### Type with Link:

- `( it, ("https://developer.bigfix.com/relevance/reference/" & it & ".html") of (concatenations "-" of substrings separated by " " of it) ) of (it as string as trimmed string) whose("" != it) of types`

### Property & Type

- `(concatenations "-" of it whose(it as trimmed string != "") of substrings separated by "," of substrings separated by "(" of substrings separated by ")" of substrings separated by ":" of substrings separated by ">" of substrings separated by "<" of substrings separated by " " of it) of (it as string as trimmed string) whose("" != it) of properties`
- `( concatenations "-" of it whose(it as trimmed string != "") of substrings separated by "," of substrings separated by "(" of substrings separated by ")" of substrings separated by ":" of substrings separated by ">" of substrings separated by "<" of substrings separated by " " of following texts of firsts ": " of it, (concatenations "-" of it whose(it as trimmed string != "") of substrings separated by "," of substrings separated by "(" of substrings separated by ")" of substrings separated by ":" of substrings separated by ">" of substrings separated by "<" of substrings separated by " " of it ) ) of (it as string as trimmed string) whose("" != it) of properties`
- `("https://developer.bigfix.com/relevance/reference/" & item 0 of it & ".html#" & item 1 of it) of ( concatenations "-" of it whose(it as trimmed string != "") of substrings separated by "," of substrings separated by "(" of substrings separated by ")" of substrings separated by ":" of substrings separated by ">" of substrings separated by "<" of substrings separated by " " of following texts of firsts ": " of it, (concatenations "-" of it whose(it as trimmed string != "") of substrings separated by "," of substrings separated by "(" of substrings separated by ")" of substrings separated by ":" of substrings separated by ">" of substrings separated by "<" of substrings separated by " " of it ) ) of (it as string as trimmed string) whose("" != it) of properties`