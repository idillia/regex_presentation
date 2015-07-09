When it comes to Regular Expressions and JavaScript, MDN is boss...you really don't need anything else.
  regexr and regexone are good resources too.

Sometimes RegEx is just what you need!

I hear sometimes RegEx is slow.....don't worry about that until it is real.

Learning how to speak RegEx out loud is fantastic practice for precise technical speaking.

RegEx in JavaScript is somewhat unique (and there are multiple implementations of it elsewhere...even multiple kinds in Unix)

You can use an expression literal, e.g.: /this will match just what you expect/

Or you can use the constructor function: new RegExp("this will match just what you expect");
  The constructor is great for passing variables in.

RegExp uses the backslash (\) to indicate that an otherwise normal character is special and to indicate that an otherwise special character should be considered normal:

SPECIAL CHARACTERS:
\
. (any single character)
\w (any word character: a-zA-Z0-9 and the underscore)
\W (any non \w character)
\b (word boundary i.e. the position where a word character is not followed by another or not preceded by another)
\B
\d (numeric characters)
\D
\s (whitespace)
\S

^ (beginning of the line)
$ (end of the line)

* {0,}
+ {1,}
? {0,1}

[xyz] [a-b] [a.d] < --- special characters are not special inside []

x|y

(x) capture parens
(?:x) non-capturing parenthesis
x(?=y) positive lookahead matches x only if followed by y
x(?!y) negative lookahead
