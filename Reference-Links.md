# Reference Links in Markdown

In Markdown, reference links are a useful way to keep text clean and readable, especially when you have long or numerous links. To create referral links, follow these steps:

1. Define reference links at the end of your document. Each referral link consists of an identifier, the URL of the link and, optionally, a title. The syntax is as follows:

    ```markdown
    [identifier]: Url "Optional Title"
    ```

    For example:

    ```markdown
    [example]: https://www.example.com "Example website"
    [google]: https://www.google.com "Google Search Engine"
    ```

2. In the body of the document, use the identifier you created instead of the URL to link the text to the URL. The syntax is as follows:

    ```markdown
    [Link text][identifier]
    ```

    For example:

    ```markdown
    [Visit example site][example]
    [Search Google][google]
    ```

This will create reference links in your document. When the final document is rendered, the "Link Text" will be converted to a hyperlink that will take the reader to the corresponding URL. Additionally, if you provided optional titles, they will appear as a tooltip when the reader hovers the mouse pointer over the link.

Reference links are especially useful when you have multiple links in your document, as they help keep the text cleaner and more readable, and allow you to modify the URLs in one place (in the reference links section) if necessary.