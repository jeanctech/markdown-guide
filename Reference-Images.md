# Reference Images in Markdown

In Markdown, you can use reference links to insert images in a more organized and readable way, especially if you need to include multiple images in your document. The process of using reference links for images is similar to that of text reference links. Follow these steps:

1. Define reference links at the end of your document. Each referral link consists of an identifier, the image Url, and optionally a title. The syntax is as follows:

    ```markdown**
    [identifier]: Image_URL "Optional alt text"
    ```

    For example:

    ```markdown
    [image1]: https://www.example.com/imagen1.jpg "Description of image 1"
    [image2]: https://www.example.com/imagen2.jpg "Description of image 2"
    ```

2. Then, in the body of the document, use the identifier you created instead of the Url to link the image to the corresponding Url. The syntax is as follows:

    ```markdown
    ![Alt text][identifier]
    ```

    For example:

    ```markdown
    ![Image 1][image1]
    ![Image 2][image2]
    ```

This will create reference links for the images in your document. Markdown will automatically render the images with their alt texts and titles (if provided) in the final document.

Using reference links for images is especially useful when you need to keep your document clean and structured or when working with multiple images, as it centralizes information about the images at the end of the document.
