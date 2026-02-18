# Recipe Database (MongoDB)

This container runs a local MongoDB instance for the Culinary Companion app.

## Startup
Use the provided script:
```bash
./startup.sh
```

It will:
- Start MongoDB on port 5000
- Create admin user `appuser` and an application user `appuser`
- Save a connection string to `db_connection.txt`
- Export env vars to `db_visualizer/mongodb.env`

## Environment variables used by the backend
- `MONGODB_URL`
- `MONGODB_DB`

These are already present in the backend container `.env` in this environment.
"""
