# Lab Instructions: Create and style a webpage

In this exercise you will you will practice building your webpage using HTML and CSS.<br><br>

> ### **Tips: Before you Begin**
>
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
>
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column.
> - Great work! You can now see instructions and code at the same time.
>   <br><br>

<br>

## Task 1: Create the HTML file.

Objectives

- Add photo.jpg to the webpage.
- Add your name as a heading to the webpage.
- Add an unordered list of your five favorite music artists.
- Add an ordered list of your top five favorite films.
- Add a hyperlink to an inspirational person.

Follow the Step by Step instructions below:

1. Open the `index.html` file and set up the following basic HTML document structure:

   ```HTML
   <!DOCTYPE html>
   <html>
   <head>
   </head>
   <body>
   </body>
   </html>
   ```

2. Set the title of the HTML document to your name:

   ```HTML
   <!DOCTYPE html>
   <html>
   <head>
       <title>your name</title>
   </head>
   <body>
   </body>
   </html>
   ```

3. Link to `styles.css` in the `head` element.

4. Add five divider elements to the `body` element.

5. Add a heading 1 to the first divider element that displays your name.

6. Add `photo.jpg` using an image element in the second divider element..

7. Add an ID attribute with the value `photo` on the image element.

8. Add a heading 2 for `Favorite Music Artists` in the third divider element. In the same divider add an unordered list with your top 5 favorite artists.

9. Add a heading 2 for `Favorite Films` in the fourth divider element. In the same divider add an ordered list with your top 5 favorite films.

10. Add a hyperlink to the Wikipedia page of a person you find inspirational / admirable in the last divider element. Alternatively. As a last step, add that person's name to the descriptive text of the `<a>` tag.

<br>

## Task 2: Style the webpage using CSS.

Objectives

- Style the webpage using CSS.

Follow the Step by Step instructions below:

1. Open the `styles.css ` file.

2. Add a CSS rule for your image that sets the `border` property to `2` pixels wide with a `solid blue` color.

3. Add a CSS rule for heading 1 containing your name and set its color to `blue`.

4. Add a CSS rule for all `<h2>` headings and set their color to `grey`.

5. Add a CSS rule that applies a `margin` of `4` pixels to the divider elements.

<br>

## Final Step: Let's submit your code!

Nice work! To submit:

- Make sure your on the development branch
- Make a commit with the commit message `feat: Complete HTML/CSS Warmup`
- Push your code and make a pull request
