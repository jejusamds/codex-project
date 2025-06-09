# Codex Project

This project requires database credentials to be provided via environment variables.

## Required Environment Variables

- `DB_HOST` - Database host
- `DB_USER` - Database user name
- `DB_PASSWORD` - Database user password
- `DB_NAME` - Database name to connect to

These variables are used by `lib/Db.class.php` when establishing a database connection.
The file `lib/settings.ini.php` provides an example configuration referencing these variables.

## Setting environment variables

Create a `.env` file or export the variables before running the project:

```bash
DB_HOST=your.database.host
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=your_database
```

Load them into your shell:

```bash
export $(cat .env | xargs)
```

Alternatively, export them directly:

```bash
export DB_HOST=your.database.host
export DB_USER=your_username
export DB_PASSWORD=your_password
export DB_NAME=your_database
```
