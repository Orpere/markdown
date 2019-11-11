# what I learn about markdown

This tutorial is based on https://guides.github.com/features/mastering-markdown/

Markdown is a way to format documentation on the web on an easy and collaborative way. the one we use on this document is GitHub flavor.

- How the markdown format makes styled collaborative editing easy
  - Markdown is the standard to create documents on the web (GitHub) and style.

- How Markdown differs from traditional formatting approach
  - markdown is rendered and display on the most variety of web platforms as GitHub and don't need more than a basic text editor for be written

- How to use Markdown to format test
  - You can use the standard symbols defined for markdown to format your heathers, bold, italic, lists, etc ... as the examples below

- How to leverage GitHub's automatic Markdown rendering
  - Git hub already have two build in  markdown formats **.md** and **.markdown** and will render automatic those extensions what are large used to create README's and other documents, example: README.md

- How to apply GitHub's unique Markdown extensions
  - create a file with the extension you pretend, as the most evident example you can see the mandatory README which file is README.md, you can also use it on the comments and Pull Requests or create Gists documents

## Examples

### TEXT

```markdown
It's very easy to make some words **bold** and other words *italic* with

 Markdown. You can even [link to Google!](http://google.com)
```

It's very easy to make some words **bold** and other words *italic* with 

Markdown. You can even [link to Google!](http://google.com)

____

### LISTS

**- Unsorted**

``` markdown 
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b

**- Ordered**

```markdown
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

**- Alternatively**

```markdown
- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
```

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

**- Task Lists**

``` markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
____

### IMAGES

``` markdown
![image](GitHub.png) # from the root directory
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

![image](GitHub.png)
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
____

### HEATHERS

headers start line  `#` for the biggest heather and go trough `########` to the smaller heather  

```markdown
third
### HEADER

fourth
#### HEADER
```

third
### HEADER

fourth
#### HEADER
____

### QUOTES

for scape special chars we can use the quotes **`**

```markdown
`?` or `#` 
or _test_ != `_`test`_`
```

`?` or `#`
or _test_ != `_`test`_`

____

### CODE

To add block of codes we abb it between   ``` 
and use the name of the language for syntax highlighting as the example:

```
```java
block{}

```

```java
/* This is a simple Java program. 
   FileName : "HelloWorld.java". */
class HelloWorld 
{ 
    // Your program begins with a call to main(). 
    // Prints "Hello, World" to the terminal window. 
    public static void main(String args[]) 
    { 
        System.out.println("Hello, World"); 
    } 
} 
```

**NOTE:** other wise the result is quite bad as bellow:

/* This is a simple Java program. 
   FileName : "HelloWorld.java". */
class HelloWorld
{
    // Your program begins with a call to main(). 
    // Prints "Hello, World" to the terminal window. 
    public static void main(String args[]) 
    {
        System.out.println("Hello, World"); 
    }
}
____

### TABLES

you can create tables by dividing rows with hyphens `-` and using pipes `|` for columns:

```markdown
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

you can also convert a csv on the [website](https://jakebathman.github.io/Markdown-Table-Generator/)
____

#### SHA REFERENCES

On Git hub any reference to SHA-1 hash is automatic converted into a link

```markdown
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```

____

### ISSUE REFERENCES WITHIN A REPOSITORY
Any number referent to an issue or PR will be converted in link 

#1
mojombo#1
mojombo/github-flavored-markdown#1
____

## USERNAME @MENTIONS
For mention a user of yopur team or notify him you should use on your comments an `@` like `@user`
or use `@team` if you pretend notify a specific team on your organization.
____

### LINKS
for add a link or url you must add the full link url and the markup will convert the URL format into a link example: htttp://example.com
If you want to add a link to some text you must follow the syntax:

```markdown
[text link ](http://example.com)
```

____

### STRIKETHROUGH

Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

```markdown
~~some text~~
```

~~some text~~
____

### EMOJ

Git hub uses [emoJs](https://www.webfx.com/tools/emoji-cheat-sheet/)  as bellow:

```markdown
this is a emoJ :scream:
```

this is a emoJ :scream: