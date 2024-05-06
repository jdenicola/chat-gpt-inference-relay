# ChatGPT Inference Relay

Created by Juan Ignacio De Nicola

This project is intended to handle sanitization and authentication to any OpenAPI server you choose.

## Usage

- Rename/copy `.flaskenv.example` to `.flaskenv`
- Set database connection (MySQL is the current dialect) in `.flaskenv`
- Run with `python3 -m flask run`

### Database initialization

You can add to your code `db.create_all()` or use any migration tool.
