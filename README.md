# mahalla_backend

1. First clone or Fork the repository
2. Install dependencies
```
# NPM
npm install
```
3. create env file (.env.development.local, .env.production.local, .env.test.local)
```# PORT
PORT = 3000

# DATABASE
DB_HOST = localhost
DB_PORT = 5432
DB_USER = postgres
DB_PASSWORD = password
DB_DATABASE = dev

# TOKEN
SECRET_KEY = secretKey

# LOG
LOG_FORMAT = dev
LOG_DIR = ../logs

# CORS
ORIGIN = *
CREDENTIALS = true
```
4. Run in dev mode
```
# NPM
npm run dev
```
