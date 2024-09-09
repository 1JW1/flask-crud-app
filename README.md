# Task Master

Task Master is a simple and efficient task management web application built with Flask. It allows users to create, view, update, and delete tasks in a user-friendly interface.

## Features

- Add new tasks
- View all tasks in a tabular format
- Update existing tasks
- Delete tasks
- Clean and responsive design

## Technologies Used

- Flask (Python web framework)
- HTML
- Jinja2 templating engine

## Getting Started

1. Install `virtualenv`:
```
$ pip install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
$ .\env\scripts\activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python3 app.py
```

This server will start on port 5000 by default. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
```

## Usage

- To add a task, enter the task description in the input field at the bottom of the page and click "Add Task"
- To update a task, click the "Update" link next to the task you want to modify
- To delete a task, click the "Delete" link next to the task you want to remove

## Project Structure

- `app.py`: Main Flask application file (not shown in the provided context)
- `templates/`: Directory containing HTML templates
  - `base.html`: Base template with common structure (not shown in the provided context)
  - `index.html`: Main page template for displaying and adding tasks

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[MIT License](LICENSE)
