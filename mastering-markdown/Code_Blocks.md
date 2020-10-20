We can highlight the code in two ways, one way is by indenting the lines of code and the other one is by using code blocks.

For creating a code block, we simply need to fence the lines of code with three backticks (`) followed by the name of language in which the code is written.

**Example:**

\`\`\`js<br>
var x = 100;<br>
const dog = 'snickers';<br>
\`\`\`

\`\`\`php<br>
$age = 18;<br>
$name = "Rahul";<br>
echo strtoupper($name);<br>
\`\`\`

_Output:_

```js
var x = 100;
const dog = 'snickers';
```

```php
$age = 18;
$name = "Rahul";
echo strtoupper($name);

```

We can also use it inline, i.e. inside a line. All we need to do is, wrap the text in backticks. For example:

Hi, did you try `var x = 100;`?

Another cool thing we can do is by highlighting what to remove and what to add by using diff, like this:

**Example:**

\`\`\`diff<br>
var x = 100;<br>
- var y = 200;<br>
+ var y = 300;<br>
\`\`\`

_Output:_

```diff
var x = 100;
- var y = 200;
+ var y = 300;
```