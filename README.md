# TaskFlow New

## Installation
1. Run `npm install --prefix apps/backend` to install dependencies.
2. Copy the generated `.env.example` file to `.env` and fill in the required values.

## Migration
Run the following command to set up the database:
```bash
npm run migrate --prefix apps/backend
```

## Running the Application
To start the application in development mode, use:
```bash
npm run dev --prefix apps/backend
```

## Build Commands
To build the application, run:
```bash
npm run build --prefix apps/backend
```

## Verification Commands
To verify the installation and setup, run:
```bash
npm install --prefix apps/backend
npm run migrate --prefix apps/backend
node --check apps/backend/src/index.js
npm run build --prefix apps/backend
```