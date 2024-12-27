# PROJECT 1 - Personal Portfolio Website 

This is a personal portfolio website built to be responsive across all screen sizes. 
The user should be able to:

- see the hover states of the elements in the navigation bar and the contact me icons just above the footer.
- click on the provided links of the listed projects to see the live site.
- quickly navigate to a desired section of the website by clicking the required menu element on the navigation bar.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Mobile-first workflow
- Published on GitHub

### Challenges

1. The navbar was built with Bootstrap. I tried using different other methods at first and it was not working.
2. I encountered issues with the layout while trying to position the first image on the right when viewing the website on a large screen.

### Future Improvements
Given more time, I will like to:

1. add an email link to the email icon on the contact section so that users will be able to write and send me a mail by clicking on the button.

### Error and Warning Log

This documents all the errors and warnings encountered during the development of this project. I used the [W3C-Validator](https://validator.w3.org/nu/) to scan for structural and syntax errors and found some errors in my html code. I found no errors in my css code after running it in the css code validator. The image below shows the error found in the html code.


![error image](<Images/Error image.png>)

Looking at the errors in the image above, it was a quick fix for me. 

In the first warning, I removed the trailing slash at the end of the link.
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
    integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg=="
    crossorigin="anonymous" referrerpolicy="no-referrer">
```

In the second and third errors, I removed the "px" in the "height" attribute of the "img" elements as it expects only numbers.

```html
<img class="project-img" src="Images/order-summary-component.jpg" alt="order-summary-component" height="210">
```

```html
<img class="project-img" src="Images/Sign-up-form.jpg" alt="sign-up-form" height="210">
```

In the last error, at the footer, I terminated the character reference with a semicolon.

```html
<footer>&copy; Chinenye Ibenyenwa 2024</footer>
```

### Useful Resources

- [W3Schools](https://www.w3schools.com/)

- [Stackoverflow](https://stackoverflow.com/)

- [MDNDocs](https://developer.mozilla.org/en-US/)

- [YouTube](https://www.youtube.com/)

- [W3C-Validator](https://validator.w3.org/nu/)