# Read 05: Design web pages with CSS

[What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

- CSS(Cascading Style sheets) specifies how documents are presented.

[How to add CSS](https://www.w3schools.com/css/css_howto.asp)

- 3 ways of inserting a style sheet: External CSS, Internal CSS, and Inline CSS
- External style sheet, you can use one file to change the entire look of a website, these are used by a link rel="stylesheet" href="mystyle.css"
- Internal style sheet can be used in a single HTML page with a unique style
style inside the head section
- Inline CSS can be used to apply a unique style for a single element. These are used with a style attribute
- Can also use multiple style sheets, but the declaration of them will effect how they are presented.
- CSS is a rule-based language. This means we define the rules by using groups of styles to be applied to elements on the web page.
- We open with a selector, such as h1 { make changes within here}

[CSS color](https://www.w3schools.com/cssref/pr_text_color.php)

- This just goes over basic color styling and how to apply it in different ways. Just refer back to page if needed.

Skim Sources

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)

- CSS reference has a massive amount of reference links on how to change hundreds of different attributes on elements.
- Myer Web open source looks like something I will be referring to constantly as we progress through CSS. Being able to set pages to defaults or reset, I think will help me get my bearing on CSS some.

## Class Notes

- select text then hit alt up or down arrow to move selected text around.
- CSS box model has 4 components that surround each element that can be manipulated (outer)margin, border, padding, image(inner)
- *{} selects EVERYTHING IN AN HTML FILE if being used internally
- float {} can be used to move an element into a position which will then cause the following elements to move up next to the moved element.
- you can grab certain elements by ids or classes to UNIQUELY IDENTIFY A SINGULAR OR GROUP OF ELEMENTS. id="uniqueNameHere" class="uniqueNameHere"
- you can grab by id by using #idName {} in CSS or .className {}
- Try to always use external sheet when applying CSS, otherwise internal and then inline will be applied AFTER the external and things can be overwritten
