# Markdown Images

Images in Markdown are pretty much exactly the same as links, just few things to know are:

**Format:**
```
![alt_text](url)
![A random 500x500 pic from Unsplash](http://unsplash.it/500/500?random "This is the tooltip")
```
_Output:_

![A random 500x500 pic from Unsplash](http://unsplash.it/500/500?random "This is the tooltip")

###### Another way to show images:

**Format:**
```
![A cute puppy][puppy]

Some text.

[puppy]: http://unsplash.it/500/500?image=1012
```
_Output:_

![A cute puppy][puppy]

Some text.

[puppy]: http://unsplash.it/500/500?image=1012

###### When you want to make a link to larger version of image, you can do something like this:

**Format:**
```
[![](http://unsplash.it/50/50/?image=1000)](http://unsplash.it/500/500/?image=1000)

```
_Output:_

[![](http://unsplash.it/50/50/?image=1000)](http://unsplash.it/500/500/?image=1000)
