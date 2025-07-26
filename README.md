## Setup

# LaneNet Lane Detection Project

## Virtual Environment Setup (`lanenet-env`)

This project uses a Python virtual environment named `lanenet-env` to manage dependencies and isolate the project environment from your system Python installation.

### Why use `lanenet-env`?

- Keeps project dependencies separate from other Python projects.
- Prevents version conflicts between packages.
- Makes it easier to reproduce the environment on different machines.

### Important Notes

- The `lanenet-env` folder is excluded from version control (Git) because it contains environment-specific files that are usually large and machine-dependent.
- Instead, all dependencies should be listed in `requirements.txt` for easy setup on other systems.

### Creating and Activating `lanenet-env`

1. Create the virtual environment:

Install required packages:

2. Activate the virtual environment:

- On Windows:
  ```
  .\lanenet-env\Scripts\activate
  ```

- On macOS/Linux:
  ```
  source lanenet-env/bin/activate
  ```

3. Install required packages:
