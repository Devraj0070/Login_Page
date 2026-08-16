# 🔐 Login & Sign-Up Page

A simple, clean, and responsive **Login and Sign-Up page UI** built using only **HTML5 and CSS3**.

The project uses a minimal **white and pink color combination** to create a clean, modern, and user-friendly interface.

> **Note:** This is currently a frontend-only project. No JavaScript, backend, database, or real authentication system has been implemented.

---

## 📸 Project Overview

This project contains two connected pages:

* 🔐 **Login Page** — For existing users
* 📝 **Sign-Up Page** — For new users

Users can navigate between the two pages using the provided links.

### Page Navigation

```text
                ┌─────────────────┐
                │   Login Page    │
                │   index.html    │
                └────────┬────────┘
                         │
                      Sign Up
                         ↓
                ┌─────────────────┐
                │   Sign-Up Page  │
                │   signup.html   │
                └────────┬────────┘
                         │
                       Login
                         ↓
                ┌─────────────────┐
                │   Login Page    │
                └─────────────────┘
```

---

## ✨ Features

### 🔐 Login Page

* Username input
* Password input
* Remember Me checkbox
* Forgot Password link
* Login button
* Sign-Up link
* Input focus effects
* Button hover effect
* Responsive layout

### 📝 Sign-Up Page

* Full Name input
* Username input
* Email input
* Password input
* Confirm Password input
* Terms & Conditions checkbox
* Create Account button
* Login link
* Input focus effects
* Button hover effect
* Responsive layout

---

## 🛠️ Technologies Used

| Technology | Purpose                                     |
| ---------- | ------------------------------------------- |
| **HTML5**  | Creates the structure of the pages          |
| **CSS3**   | Handles styling, layout, and responsiveness |

### No JavaScript or frameworks

This project intentionally uses only:

```text
HTML + CSS
```

No JavaScript, Bootstrap, React, Tailwind CSS, or other frameworks are currently used.

---

## 📁 Project Structure

```text
Login_Page/
│
├── index.html          # Login page
├── signup.html         # Sign-up page
│
├── style.css           # Login page styling
├── signup.css          # Sign-up page styling
│
└── README.md           # Project documentation
```

---

# 🚀 Step-by-Step Development

## 1. Create the Project Folder

Create a folder named:

```text
Login_Page
```

Open the folder in **Visual Studio Code**.

---

## 2. Create the Login Page

Create:

```text
index.html
```

This file contains the structure of the login page.

The login page contains:

* Username
* Password
* Remember Me
* Forgot Password
* Login button
* Sign-Up link

---

## 3. Create Login Page Styling

Create:

```text
style.css
```

This file controls the appearance of the login page.

The CSS handles:

* Background color
* Login card
* Input fields
* Buttons
* Text
* Spacing
* Shadows
* Hover effects
* Focus effects
* Layout

---

## 4. Create the Sign-Up Page

Create:

```text
signup.html
```

The sign-up page allows new users to create an account.

It contains:

* Full Name
* Username
* Email
* Password
* Confirm Password
* Terms & Conditions
* Create Account button
* Login link

---

## 5. Create Sign-Up Page Styling

Create:

```text
signup.css
```

This file contains all the styling specifically for the sign-up page.

It maintains the same visual style as the login page.

---

# 🔗 Connecting Both Pages

The Login page contains a **Sign Up** link:

```html
<a href="signup.html">Sign Up</a>
```

When the user clicks it, they are taken to:

```text
signup.html
```

The Sign-Up page contains a **Login** link:

```html
<a href="index.html">Login</a>
```

This takes the user back to the login page.

---

# 🎨 Design

The project follows a simple **white and pink** design.

### Color Palette

| Element         | Color     |
| --------------- | --------- |
| Page Background | `#fff0f5` |
| Card Background | `#ffffff` |
| Primary Pink    | `#e75480` |
| Button Hover    | `#d9436f` |
| Main Text       | `#333333` |
| Secondary Text  | `#777777` |
| Input Border    | `#dddddd` |

The light pink background combined with the white cards gives the interface a clean and minimal appearance.

---

# 📱 Responsive Design

Both pages include responsive styling so that the interface can adapt to smaller screens.

The pages can be viewed on:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📟 Tablet

A CSS media query is used to adjust the signup card on smaller screens.

Example:

```css
@media (max-width: 450px) {
    .signup-box {
        width: 100%;
        padding: 30px 25px;
    }
}
```

---

# ▶️ How to Run

## Method 1 — Open Directly

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The Login page will open in your browser.

From there, click **Sign Up** to open the registration page.

---

## Method 2 — Using VS Code Live Server

1. Open the project in VS Code.
2. Install the **Live Server** extension.
3. Open `index.html`.
4. Right-click the file.
5. Select **Open with Live Server**.

The Login page will open in your browser.

---

# 📚 What I Learned

This project helped practice the following concepts:

### HTML

* HTML document structure
* Forms
* Input elements
* Labels
* Buttons
* Checkboxes
* Links
* Form validation using HTML attributes
* Connecting multiple HTML pages

### CSS

* CSS selectors
* Flexbox
* Box model
* Padding and margins
* Width and height
* Colors
* Borders
* Border radius
* Box shadows
* Hover effects
* Focus effects
* Media queries
* Responsive design

### Git & GitHub

* Creating a GitHub repository
* Initializing Git
* Adding files
* Creating commits
* Connecting a local project to GitHub
* Pushing code to GitHub

---

# 🔮 Future Improvements

The current project is focused on frontend design. The following features can be added in future versions:

* [ ] JavaScript form validation
* [ ] Password show/hide button
* [ ] Password strength indicator
* [ ] Confirm password validation
* [ ] Functional Forgot Password page
* [ ] Functional user registration
* [ ] Backend authentication
* [ ] Database integration
* [ ] User dashboard
* [ ] Logout functionality
* [ ] Dark mode
* [ ] Social media login
* [ ] Email verification
* [ ] Error and success messages

---

# ⚠️ Current Limitations

This project is currently a **frontend-only UI**.

The following features are not functional yet:

* Login authentication
* Account creation
* Password recovery
* Remember Me functionality
* Database storage
* User verification

The forms currently demonstrate the **design and structure** of an authentication system.

---

# 📌 Project Status

**Status:** 🚧 Frontend Completed

The Login and Sign-Up interfaces are complete using HTML and CSS.

Future updates will add functionality using JavaScript and backend technologies.

---

# 👨‍💻 Author

**Devraj Jha**

B.Tech Computer Science Engineering — Data Science

---

# 📄 License

This project was created for **learning and educational purposes**.

Feel free to modify and improve the project for your own learning and development.
