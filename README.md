When it comes to Regular Expressions and JavaScript, MDN is boss...you really don't need anything else.
  regexr and regexone are good resources too.















Sometimes RegEx is just what you need! (sometimes hard to read, leave comments)














I hear sometimes RegEx is slow.....don't worry about that until it that's a real problem for you.















Learning how to speak RegEx out loud is fantastic practice for precise technical speaking.
  imo most of doing well with RegEx is knowing what you're actually trying to do.















RegEx in JavaScript is somewhat unique (and there are multiple implementations of it elsewhere...even multiple kinds in Unix)















Use RegExp in JavaScript with String's `match` `replace` `split`, and RegExp's `exec` and `test`
















`/pattern/flags`
`new RegExp("pattern"+ x + "more", "flags")`


You can use an expression literal, e.g.: /this will match just what you expect/

Or you can use the constructor function: new RegExp("this will match just what you expect");
  The constructor is great for passing variables in.















RegExp uses the backslash (\) to indicate that an otherwise normal character is special and to indicate that an otherwise special character should be considered normal:

/w\wwwwww/
thixs
thi2s
thiss

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



this and that and more

^ (beginning of the line)
$ (end of the line)

* {0,}
+ {1,}
? {0,1}
{3,6}

/a{3,6}/


[xyz] [a-z] [a.d] < --- special characters are not special inside []

x|y

(x) capture parens
(?:x) non-capturing parenthesis
x(?=y) positive lookahead matches x only if followed by y
x(?!y) negative lookahead















Learn how to rapidly iterate on your RegEx (e.g. with nodemon -q or regexr)











