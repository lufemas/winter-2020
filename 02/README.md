# Week 2

## Elements

A full list of [HTML elements with linkable descriptions](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) can be found on the Mozilla Developer Network ("MDN") website

## W3C validation

You can validate your HTML with [the official w3c (World Wide Web Consordium) validator tool](https://validator.w3.org/nu/) to ensure you meet the basic standards for a "valid" web page.

## Urls and paths

When adding or linking to files or documents, your browser can be directed with *two* types of paths.

### Relative
The path references other files or folders starting from the folder where this current file exists. 

*However, it is important to note that starting a relative path with a `/` changes the path to begin relative to the file system that this project is contained within. So it can be relative to the domain or project folder (good), but can also be from your hard-drive's root folder if you are not careful about how you preview your pages (bad).*

### Absolute
Regardless of where you are linking from, the path is always the same because it starts with `http://` or `https://`


## Lab (First half)

1. Review the HTML elements types in the following *three* sections and include as many different element types as you can (don't worry about the document making sense - this is just for experimentation and learning):
    - [Content sectioning](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Content_sectioning)
    - [Text content](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Text_content)
    - [Inline text semantics](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#Inline_text_semantics)
2. Add an image to your document (use Photoshop to size the image if you wish; do not size the image using HTML)
3. Using your best guess, create a menu with 3-4 direct links to other (made up) pages on this site, using the HTML elements you think best represent the semantics and structure learned to date. (Because you don't have other pages yet, you will assign the `href` a value of `"#"` as a placeholder)

## Still to come today
- Review of your work
- Section linkin with `<a href="#">`
- Backgrounds