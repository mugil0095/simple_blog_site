# Simple Blog Site

This is a basic blog website built using Python and the Flask framework, where users can create, edit, and delete blog posts.

## Project Structure

simple_blog_site/
│
├── app/
│ ├── init.py
│ ├── models.py
│ ├── routes.py
│ └── templates/
│ ├── base.html
│ ├── blog_post.html
│ ├── create_post.html
│ ├── edit_post.html
│ └── index.html
│
├── migrations/
│ └── ...
│
├── config.py
├── run.py
└── README.md

markdown
Copy code

## Usage

1. Clone this repository.
2. Set up a virtual environment and activate it.
3. Install the required dependencies from `requirements.txt`.
4. Set up the database by running database migrations.
5. Run the Flask application using `run.py`.

## Features

- Create, edit, and delete blog posts.
- View a list of all blog posts on the homepage.
- View individual blog posts with their details.

## Technologies Used

- Python
- Flask
- SQLAlchemy (for database management)
- HTML/CSS (for front-end templates)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for d