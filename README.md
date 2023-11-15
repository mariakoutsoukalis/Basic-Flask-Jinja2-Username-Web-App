# Flask Web Application with Dynamic Username Rendering

This Flask application demonstrates basic routing and dynamic content rendering using Jinja2 templating. It provides different routes to render a webpage with a customizable username.

## Features

- Dynamic username rendering in HTML using Jinja2 templating.

## Installation

1. Ensure you have Python installed on your system.
2. Clone this repository or download the source code.
3. Navigate to the application directory and install dependencies:

```bash
pipenv install flask jinja2
```

4. Activate the virtual environment:

```bash
pipenv shell
```

## Usage

Run the application using:

```bash
python3 app.py
```

### Accessing the Application:

- Open a web browser and visit `http://localhost:5000` to view the default greeting.
- Visit `http://localhost:5000/hello` for a custom greeting with a default username.
- Visit `http://localhost:5000/hello/[username]` by replacing `[username]` with any name of your choice for a personalized greeting.

## Customization

To customize, edit the `index.html` file in the templates directory. You can modify the HTML to change the appearance or content of the webpage.