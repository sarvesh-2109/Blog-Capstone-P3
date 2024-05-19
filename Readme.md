# Blog Post Application

Welcome to the **Blog Post Application** repository! This application is built with Flask and allows users to create, edit, delete, and view blog posts. Additionally, users can contact the blog owner via a contact form, which sends an email using SMTP.

## Features

- 📝 **Create Blog Posts**: Add new blog posts with a title, subtitle, author name, image URL, and content using CKEditor.
- 🔍 **View All Posts**: Display all blog posts on the home page.
- 🖊️ **Edit Posts**: Edit existing blog posts.
- ❌ **Delete Posts**: Delete blog posts.
- 📧 **Contact Form**: Send a message to the blog owner via email.

## Technologies Used

- **Flask**: Web framework for creating the application.
- **Flask-Bootstrap**: Bootstrap integration for styling the application.
- **Flask-SQLAlchemy**: SQLAlchemy integration for database management.
- **Flask-WTF**: Integration of WTForms for form handling and validation.
- **Flask-CKEditor**: Integration of CKEditor for rich text editing.
- **SQLite**: Database for storing blog posts.
- **SMTP**: For sending emails from the contact form.

## Installation

1. **Clone the repository**:
   ```sh
   git https://github.com/sarvesh-2109/Blog-Capstone-P3.git
   cd Blog-Capstone-P3
   ```

2. **Create a virtual environment**:
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```sh
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   Create a `.env` file in the root directory and add your email credentials:
   ```env
   EMAIL_USERNAME=your_email@gmail.com
   EMAIL_PASSWORD=your_email_password
   ```

5. **Run the application**:
   ```sh
   flask run
   ```

## Usage

### Creating a Blog Post

1. Navigate to `/new-post`.
2. Fill out the form with the title, subtitle, author, image URL, and content.
3. Click "Submit Post".

### Viewing All Posts

- The home page (`/`) displays all the blog posts.

### Editing a Post

1. Navigate to `/edit-post/<post_id>`.
2. Edit the desired fields.
3. Click "Submit Post".

### Deleting a Post

- Click the "Delete" button next to the post you wish to delete on the home page.

### Contacting via Form

1. Navigate to `/contact`.
2. Fill out the form with your name, email, phone number, and message.
3. Click "Send".


## Contributing

Feel free to submit issues, fork the repository, and make a pull request. Contributions are welcome!



Thank you for checking out my Blog Post Application! If you have any questions or feedback, feel free to reach out. 😊

**Happy Coding!** 👨‍💻👩‍💻

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-blue)](https://www.linkedin.com/in/sarvesh-mhatre-475859242/)