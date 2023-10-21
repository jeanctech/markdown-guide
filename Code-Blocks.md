# Code Blocks in Markdown

To create code blocks in Markdown, you can use triple backticks (```) on separate lines before and after the code block. You can optionally specify the programming language so that the code is highlighted properly. Here's how to do it:

#### Code blocks without specifying the language:

If you don't want to specify the programming language, simply use triple backticks on separate lines before and after the code block. Here is an example:

``markdown
This is a block of code in Markdown.
You can include multiple lines of code here.
```

This will look like this:

``markdown
This is a block of code in Markdown.
You can include multiple lines of code here.
```

#### Code blocks with language specification:

If you want to highlight the syntax of code in a specific programming language, you can specify the language after the first triple backtick. Here is an example using JavaScript:

```javascript
function greet() {
   console.log("Hello, world");
}
```

This will look like this, with syntax highlighting for JavaScript:

```javascript
function greet() {
   console.log("Hello, world");
}
```

Code blocks are useful for displaying code snippets in your Markdown document. You can specify the appropriate language for syntax highlighting depending on the programming language you are using.
