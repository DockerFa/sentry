# sentry
dockerised sentry self hosted

# How to run sentry?
1. update environments in `docker-compose.yml`:
   - SENTRY_SECRET_KEY = this is an random string
   - SENTRY_SERVER_EMAIL = from email
   - SENTRY_EMAIL_HOST = smtp server address
   - SENTRY_EMAIL_PORT = 587
   - SENTRY_EMAIL_USER = email user
   - SENTRY_EMAIL_PASSWORD = email password
2. make executable `init.sh` with command `chmod +x init.sh`
3. run `./init.sh`
4. now you can access to sentry web with `127.0.0.1:9000`
