# Markdown code

To format text as code in Markdown, you can use backticks (`) or backticks (backticks), which are found on the same key as the tilde (~) on most keyboards. This is used to highlight code or commands within a paragraph of text. You can apply code inline or create code blocks.

### Online code

To highlight text as inline code, surround the relevant part with a backtick (`) or a pair of backticks. Here is an example:

Syntax with a grave accent:

```markdown
`This is inline code`
```

Syntax with a couple of grave accents:

```markdown
This is inline code
```

This will look like this:

`This is inline code`

### Code blocks

To create a code block, surround the code with three backticks on a separate line before and after the code block. You can specify the programming language after the three initial grave accents so that the code is highlighted properly. Here is an example:

Code block syntax without specifying the language:

```markdown
This is a block of code
Here you can put multiple lines of code.
```

Code block syntax with language specification (for example, JavaScript):

```javascript
function greet() {
   console.log("Hello, world");
}
```

This will look like this:

```markdown
This is a block of code
Here you can put multiple lines of code.
```

```javascript
function greet() {
   console.log("Hello, world");
}
```

You can adjust the language of the code block according to your needs, and Markdown will highlight the syntax of the code accordingly.
