# Links in Markdown

Different ways to create links:

######  Wrapping a complete url inside < > will make it a link.

**Example:**

<https://www.google.com>

_Output:_

```
<https://www.google.com>
```

######  If you want to link some text to a link, then wrap the text in [ ] and put the link in ( ) immediately after the text.

**Example:**

```
[My GitHub account](https://gitbub.com./rahuldhangar)
```

_Output:_

[My GitHub account](https://gitbub.com./rahuldhangar)


###### We can also add Title tag to the link by wrapping it in " " after the link inside ( )

**Example:**

```
[My GitHub account](https://gitbub.com./rahuldhangar "This is Rahul's GitHub account link")
```

_Output:_
[My GitHub account](https://gitbub.com./rahuldhangar "This is Rahul's GitHub account link")


###### Using a token or key in place of link to make the para more readable

If you have really long URLs, it could be very disorienting to paste a URL right in the middle of a paragraph like this:

```
Make sure you check my [GitHub](https://github.com/rahuldhangar "My Github profile link") link and follow me on [Twitter](https://twitter.com/rahuldhangar).
```
(_Output:_)

Make sure you check my [GitHub](https://github.com/rahuldhangar "My Github profile link") link and follow me on [Twitter](https://twitter.com/rahuldhangar).

So instead of adding a parenthesis ( ) with full link inside a paragraph, we can put a token or a key and and add the key value in the bottom of document like this:

```
Make sure you check my [GitHub]([1] "My Github profile link") link and follow me on [Twitter][2].

Some other text
and lines

and paragraphs....

[1]: https://github.com/rahuldhangar
[2]: https://twitter.com/rahuldhangar
```

_Output:_


Make sure you check my [GitHub][1] link and follow me on [Twitter][2].

Some other text
and lines

and paragraphs....

[1]: https://github.com/rahuldhangar "My Github profile link"
[2]: https://twitter.com/rahuldhangar "This is Rahul's Twitter page"