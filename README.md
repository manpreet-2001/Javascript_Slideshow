# JavaScript Slideshow

A simple slideshow built using vanilla JavaScript.

## Building It from Scratch

Creating a JavaScript slideshow involves breaking the larger goal into manageable steps. Begin by downloading the `index.html`, `styles.css`, and `slideshow.js` files. Follow each step carefully—test and complete one before moving on to the next.

1. Use CSS to stack all images on top of one another, rather than placing them vertically.

2. Make only the first image visible. Use CSS to hide the others.

3. In `slideshow.js`, create a `current` variable to track the current image index. Initialize it to `0`. This variable will cycle from `0` to `3`, and then back to `0` (since there are four images).

4. Create a `total` variable and set it to `4` to represent the total number of images.

5. Add a click event listener to the "Next" button. For now, use `console.log("next")` to ensure the button is working.

6. Inside the "Next" button's event handler, increment the `current` variable by 1. Use `console.log()` to confirm it’s updating.

7. Add a conditional check to reset `current` back to `0` when it exceeds the total number of images.

8. Within the same event handler, hide all images and display only the one that corresponds to the `current` index.

9. Repeat steps 5 through 8 for the "Previous" button.

10. Use JavaScript's `setInterval()` function to automatically switch images every five seconds.

> [!NOTE]
> Sample code files are available for steps 1 through 6. Try to complete each step on your own before referencing them.

---

## Useful Resources

- [Visual Studio Code](https://code.visualstudio.com/)

<br>
<a href="https://codeadam.ca">
  <img src="https://cdn.codeadam.ca/images@1.0.0/codeadam-logo-coloured-horizontal.png" width="200">
</a>
