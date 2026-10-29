# Render Keepalive Test

A minimal Python HTTP service for testing Render deployment.

- `/` returns JSON status.
- `/health` returns JSON status.
- Uses Render's `PORT` environment variable.
- No trading logic, credentials, or database.
