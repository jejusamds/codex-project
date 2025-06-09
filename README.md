# Codex Project

This project requires database credentials to be provided via environment variables.

## Required Environment Variables

- `DB_HOST` - Database host
- `DB_USER` - Database user name
- `DB_PASSWORD` - Database user password
- `DB_NAME` - Database name to connect to

These variables are used by `lib/Db.class.php` when establishing a database connection.
The file `lib/settings.ini.php` provides an example configuration referencing these variables.
