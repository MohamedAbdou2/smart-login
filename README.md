
Sure, here's how you can structure your README.md file using Markdown:

markdown
Copy code
# Smart Login System

This is a simple login system consisting of three pages: Sign In, Sign Up, and Welcome Page. It allows users to sign up, sign in, and displays a welcome message upon successful login. The system utilizes HTML, CSS, Bootstrap, JavaScript, local storage, and regular expressions for input validation.

## Pages

### 1. Sign Up Page

The Sign Up page allows users to create a new account by providing their name, email, and password. The inputs are validated using regular expressions to ensure correct formatting. Once the user submits the form, the information is stored locally.

### 2. Sign In Page

The Sign In page prompts users to enter their email and password. Upon submission, the system checks if the credentials match those stored in local storage. If the login is successful, the user is redirected to the Welcome Page.

### 3. Welcome Page

The Welcome Page displays a personalized welcome message to the logged-in user. It retrieves the user's name from local storage and dynamically updates the greeting.

## Technologies Used

- **HTML**: Markup language for structuring the pages.
- **CSS**: Stylesheets for enhancing the visual presentation.
- **Bootstrap**: Front-end framework for responsive design and components.
- **JavaScript**: Programming language for client-side interactivity and form validation.
- **Local Storage**: Browser storage mechanism for storing user data locally.
- **Regular Expressions**: Used for input validation to ensure correct formatting of user data.

## Files

- **index.html**: Sign In Page
- **signup.html**: Sign Up Page
- **welcome.html**: Welcome Page
- **style.css**: Stylesheet for styling the pages
- **index.js**: JavaScript file for client-side validation and logic
- **README.md**: Documentation file (you're reading it right now)

## How to Run

1. Clone this repository to your local machine.
2. Open the desired page (Sign In, Sign Up, or Welcome) in your web browser.
3. Interact with the respective page as per your needs (e.g., sign up, sign in).
4. Enjoy using the Smart Login System!
