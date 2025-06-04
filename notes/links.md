# Links in Markdown

You can create links in Markdown using the following syntax:

1. **Inline Links**: To link directly to a URL, use the following syntax:

    ```markdown
    [Link text](Url)
    ```

    Where "Link Text" is the text that will be displayed as the link and "Url" is the web address that the link points to. Here is an example:

    ``markdown
    [Example website](https://www.example.com)
    ``

2. **Reference Links**: You can also use reference links to keep your Markdown text cleaner. To do this, define a reference link at the end of the document and use it in the main text. The syntax is as follows:

    At the bottom of the document:

    ```markdown
    [Link text][identifier]

    [identifier]: Url "Optional Title"
    ```

    Then, in the body of the text:

    ```markdown
    [Link text][identifier]
    ```

    Where "Link text" is the text of the link, "id" is the identifier that links the link to its corresponding URL, and "URL" is the web address of the link. "Optional Title" is, as the name suggests, optional and is used to provide additional information about the link. Here is an example:

    At the end of the document:

    ```markdown
    [example site][example]

    [example]: https://www.example.com "Example home page"
    ```

    In the body of the text:

    ```markdown
    [example site][example]
    ```

Whether you use inline links or referral links, Markdown will create a hyperlink in the final document that will take the reader to the specified Url when they click the link text.
