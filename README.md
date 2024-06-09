# HTML Structure for Authentication Form

This HTML document creates a sign-up form within a styled card layout.

- **Meta Tags**: Set character encoding, viewport settings, and IE compatibility.
- **External Resources**: Links to a CSS stylesheet and a JavaScript file.
- **Content**:
  - **Form Container**: Uses a clearfix for layout control.
  - **Form Card**: Contains the sign-up form with fields for first name, last name, email, and password.
  - **Message Placeholder**: An empty `div` for displaying messages.
  - **Sign-Up Button**: Submits the form.

# CSS Styling for Authentication Form

This CSS code provides a cohesive design for an authentication form, ensuring a user-friendly and visually appealing interface.

- **Global Settings**: 
  - Applies `box-sizing: border-box` to all elements for consistent sizing.
  - Sets base font size and family for the body with a light blue background.

- **Element Styling**:
  - **h2**: Large font size with specific margins.
  - **Button**: Dark blue background, rounded corners, white text, and transition effects.
  - **Input Groups**: Margins for top and bottom spacing.
  - **Labels**: Dark grey color.
  - **Inputs**: Light grey background, rounded corners, transition effects.

- **Card Container**:
  - Light yellow background, border, shadow, padding, and specified width.
  - Floats are cleared to ensure proper layout.

- **Clearfix**:
  - Utilizes pseudo-elements to clear floats for proper container management.

# JavaScript Form Submission and Local Storage

This JavaScript code snippet handles form submission and stores user input in local storage as JSON.

- **Element Selection**:
  - Retrieves input elements by their IDs for first name, last name, email, and password.
  - Selects the sign-up button.

- **Event Handling**:
  - Adds a click event listener to the sign-up button.
  - Prevents the default form submission behavior using `event.preventDefault()`.

- **Form Submission**:
  - Creates a user object with trimmed input values.
  - Stores the user object in local storage using `localStorage.setItem()` after converting it to JSON format with `JSON.stringify()`.

* What is JSON? How is it useful for sending and storing data?

JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa).

