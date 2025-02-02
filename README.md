# Learn HTML Forms by Building a Registration Form

You can use HTML forms to collect information from people who visit your webpage.

In this course, you'll learn HTML forms by building a signup page. You'll learn how to control what types of data people can type into your form, and some new CSS tools for styling your page.

**Step 1**

Welcome to the Registration Form project! Start by adding the !DOCTYPE html declaration at the top of the document so the browser knows what type of document it's reading.

**Step 2**

Below the DOCTYPE, add an html element with a lang attribute set to en, so that you have a place to start putting some code.

**Step 3**

Next, add opening and closing head and body tags within the html element.

**Step 4**

Add a title and meta element inside the head element. Give your project a title of Registration Form, and add the charset attribute with a value of utf-8 to your meta element.

**Step 5**

Nest a self-closing link element within the head element. Give it a rel attribute with value of stylesheet and an href attribute with a value of styles.css.

**Step 6**

Within the body, provide a heading context for the content, by adding an h1 with the text Registration Form.

**Step 7**

Below the heading, use the following text within a paragraph element to encourage users to register:

Example Code

```please
Please fill out this form with the required information
```

**Step 8**

The vh unit stands for viewport height, and is equal to 1% of the height of the viewport. This makes it relative to the viewport height.

It is time to spruce the project up with some CSS. Begin by giving the body a width of 100%, and a height of 100vh.

**Step 9**

Now, get rid of the horizontal scroll-bar, by setting the body default margin added by some browsers to 0.

**Step 10**

That is better. Now, make the background easy on the eyes, by changing the body background-color to #1b1b32. Then, to see the text, change the color to #f5f6f7.

**Step 11**

As suggested by the title, you are creating a form. So, after the p element, insert a form with an action attribute targeting https://register-demo.freecodecamp.org.

**Step 12**

The method attribute specifies how to send form-data to the URL specified in the action attribute. The form-data can be sent via a GET request as URL parameters (with method="get") or via a POST request as data in the request body (with method="post").

Set the method attribute to send your form data via a POST request.

**Step 13**

As the form will have three distinct sections, add three fieldset elements within the form element.

**Step 14**

The first fieldset will hold name, email, and password fields. Start by adding four label elements to the first fieldset.

**Step 15**

Add the following text to the label elements:

- Enter Your First Name:
- Enter Your Last Name:
- Enter Your Email:
- Create a New Password:

**Step 16**

The rem unit stands for root em, and is relative to the font size of the html element.

As label elements are inline by default, they are all displayed side by side on the same line, making their text hard to read. To make them appear on separate lines, add display: block to the label element, and add a margin of 0.5rem 0, to separate them from each other.

**Step 17**

Nest an input element within each label. Be sure to add each input after the label text, and include a space after the colon.

**Step 18**

Following accessibility best practices, link the input elements and the label elements together using the for attribute.

Use first-name, last-name, email, and new-password as values for the respective id attributes.

**Step 19**

Specifying the type attribute of a form element is important for the browser to know what kind of data it should expect. If the type is not specified, the browser will default to text.

Give the first two input elements a type attribute of text, the third a type attribute of email, and the fourth a type attribute of password.

The email type only allows emails with a @ and a . in the domain. The password type obscures the input, and warns if the site does not use HTTPS.

**Step 20**

The first input element with a type of submit is automatically set to submit its nearest parent form element.

To handle the form submission, after the last fieldset element add an input element with the type attribute set to submit and the value attribute set to Submit.