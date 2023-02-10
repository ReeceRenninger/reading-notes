# Notes

[Using Images In HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
[Common Image Types](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types)
[Choosing Image Formats](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format)

1. If you inputted your file for your image incorrectly the alt text information would be displayed instead which will easily allow you to be notified of your mistake. Alt text can also be beneficial for visually impaired that are using a screen reader.
2. Adding alt text can be one way to make images more accessible. Use meaningful file names for screen readers to read for the visually impaired. We can also add a title attribute which will add more context and give a mouseover effect.
3. Figure is primarily used for an image, diagram, code snippet or something else of that nature.  They are beneficial because they can be moved to a different part of the document and not affect the flow of the document.  They can also have a caption added inside using figcaption.
4. Both SVG(Scalable Vector Graphics) and GIF(Graphics Interchange Format) represent pictures, animated pictures or short videos.  GIFs do not look good as you try to make them larger or smaller on your screen where SVGs look good even when making the image larger or smaller.
5. I would use an SVG because if the image needs to be scaled up or down, it will retain its crisp resolution.

[Using Color in CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
[Styling HTML Text Elements](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)

1. The foreground color in CSS changes the content, such as the text color in an HTML element. While the background color changes the color BEHIND the content or text. So foreground would represent the black text while background is the white behind it.
2. I could use color to make the texts have varying colors to make them pop off the page or add text decorations to the words to make them more unique looking in varying sections.  We could also change the background color of sections to color coordinate ideas or thoughts.
3. Accessibility and readability.  You do not want to have a wonky text that is difficult for people to read or even unable to read for people with poor eyesight.
4. Font-size adjusts the font size of the selected element.  Font-weight can make the text look bolder or lighter depending on the weight given as the value.  While font-style can change the font to be italics, normal, oblique.
5. We can use letter-spacing or word-spacing to provide spacing between letters or words within a selected text.  

## Class Notes

### CSS Notes

Absolute

Absolute Units are the same size regardless of the parent element or window size.

Absolute units are not recommended for responsive sites!

    PX - by far the most commonly used absolute unit

Relative

Relative Units are used for styling responsive sites. They scale relative to the parent element or to the window size.
% - percentages

    Percentages are always relative to some other value.
    Sometimes it's a value from the parent and other times it's a value from the element itself.
    width: 50% - half the width of the parent
    line-height: 50% - half the font-size of the element itself
    Usually more appropriate for layout-related properties.

em

    font-size: 1em - equals the font-size of the parent
    font-size: 2em - twice the font-size of the parent, etc
    With other properties, 1em is equal to the computed font-size of the element itself... like with line-height.

```js
  h1 {
     font-size: 20px;
     /* using em here the line height would be half of the element itself */     
     line-height: 50%;
   }
```

    Defining font-size using em can cause problems when you have nested elements which all define font-size using em. This is because the inherited font-size is calculated from parent elements font-size value and passed down to child elements. Nested elements could have ever decreasing font-sizes.

rem - root em

    Relative to the root <html> element's font size. Often easier to work with.
    Browsers generally set the root font size at 16 pixels
        If the root font size is 16px, 1 rem is 16px, 2rem is 32px, etc.

vw & vh - view height & view width

    1vw is 1% of the width of the viewport(area of the window in which web content can be seen)
    1vh is 1% of the height of the viewport
    height: 100vh - would make that element take up the full height on the screen
    Because you never know what screen size will access your code, this unit allows you to set exactly how much of the screen will be occupied by a given element.

## Things I want to know
