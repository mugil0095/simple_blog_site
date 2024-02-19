# Simple Blog Site

This is a basic blog website built using Flask, where users can create, edit, and delete blog posts.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
simple_blog_site
&ensp;app<br>
&emsp;init.py<br>
&emsp;models.py<br>
&emsp;routes.py<br>
&emsp;templates<br>
&emsp;&emsp;base.html<br>
&emsp;&emsp;create_post.html<br>
&emsp;&emsp;edit_post.html<br>
&emsp;&emsp;index.html<br>
&emsp;&emsp;show_post.html<br>
&ensp;db<br>
&emsp;blog.db<br>
&ensp;static<br>
&emsp;style.css<br>
&ensp;README.md<br>
&ensp;run.py<br>


## Installation
1. Clone the repository:
    ```
    git clone https://github.com/mugil0095/simple_blog_site.git
    ```
2. Install the required dependencies:
    ```
    pip install Flask Flask-SQLAlchemy
    ```
3. Create the database:
    - Navigate to the project directory.
    - Open SQLite shell:
        ```
        sqlite3 db/blog.db
        ```
    - Create the `post` table:
        ```
        CREATE TABLE post (
            id INTEGER PRIMARY KEY,
            title VARCHAR(100) NOT NULL,
            content TEXT NOT NULL
        );
        ```
    - Exit SQLite shell:
        ```
        .exit
        ```

## Usage
1. Run the application:
    ```
    python run.py
    ```
2. Visit `http://localhost:5000` in your web browser.
3. Follow the navigation links to view recent posts, create new posts, and manage existing posts.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
