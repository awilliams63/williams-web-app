# williams-web-app

## To Run This Application

1. Clone this repository to your local computer

2. Create a new virtual environment

Windows:
`python -m venv .venv`

Mac:
`python3 -m venv .venv`

3. Activate the virtual environment

Windows PowerShell:
`.\.venv\Scripts\Activate.ps1`

Mac:
`source .venv/bin/activate`

4. Install dependencies

`pip install -r requirements.txt`

5. Run the application

`python app.py`

Alternative Flask command:
`flask --app app run`

To use a different port:
`flask --app app run --port 8080`

To listen on all public IP addresses:
`flask --app app run --host 0.0.0.0`

To run in debug mode:
`flask --app app run --debug`

Example:
`flask --app app run --port 8080 --debug`