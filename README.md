# grid_ex_1

The exercise I provided is written in plain text with some structural cues that resemble Markdown, but it's not in strict Markdown format. If you want it in Markdown format, I can easily modify it for you. Here's the exercise in proper Markdown:

---

## Bootstrap Grid System Exercise: Login Form inside a Card

### Objective:
Practice using the Bootstrap grid system by creating a responsive login form inside a Bootstrap card. 

### Requirements:
- Familiarity with HTML and Bootstrap.
- A working environment to write and test HTML (e.g., code editor and browser).
- Access to Bootstrap's CDN or a local Bootstrap installation.

### Instructions:

1. **Set Up Your HTML Document:**
   - Start with a basic HTML5 template.
   - Link the Bootstrap CSS at the head of your document. You can use the Bootstrap CDN for this.

2. **Create the Bootstrap Container:**
   - Within the body of your HTML, create a `<div>` with the class `container`.

3. **Introduce the Bootstrap Grid System:**
   - Inside the `container`, create a `<div>` with the class `row`.
   - Inside the `row`, create a `<div>` with the classes `col-12 col-md-6 col-lg-4`.

4. **Insert a Bootstrap Card:**
   - Within the `col-*` div, create a card using the `card` class.

5. **Build the Card's Body and Login Form:**
   - Inside the card, create a card body using the `card-body` class.
   - Within the card body:
     - Add a heading with the class `card-title` labeled "Login".
     - Create a form element.
       1. For the username:
          - Create a `form-group` div.
          - Add a label for the username input and set its `for` attribute to `username`.
          - Create an input field with the classes `form-control` and an `id` of `username`.
       2. Repeat for the password (use `password` as the input type).
       3. Add a submit button with the classes `btn btn-primary`.

6. **Style and Test:**
   - Add styles or utility classes if desired.
   - Test in a browser and adjust window sizes to see the responsiveness.

### Expected Outcome:
A centered card on medium and large screens, with a full-width card on smaller screens. The login form should contain fields for the username and password and a submit button.

