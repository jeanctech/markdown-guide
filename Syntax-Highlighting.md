# Syntax Highlighting in Markdown

To highlight code syntax in Markdown, you can use code blocks and specify the programming language. This allows proper syntax highlighting to be applied. Syntax highlighting is especially useful when you want to share code in your Markdown document. Here's how to do it:

1. Use triple backticks (```) on separate lines before and after the code block. Also, specify the programming language you want to highlight after the first triple backtick. For example, to highlight code in JavaScript:

    ```javascript
    function greet() {
      console.log("Hello, world");
    }
    ```


    Markdown will automatically highlight code syntax based on the specified language:

    ```javascript
    function greet() {
      console.log("Hello, world");
    }
    ```

2. If you don't specify a language, Markdown will still display the code block, but it will not apply syntax highlighting. Here is an example without language specification:

    ```
    function greet() {
      console.log("Hello, world");
    }
    ```

    This will be displayed as a block of code without syntax highlighting:

    ```
    function greet() {
      console.log("Hello, world");
    }
    ```

Use this technique to share and highlight the code in your Markdown document in a clear and readable way.