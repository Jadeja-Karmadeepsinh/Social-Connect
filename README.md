### Setup .env file

```js
MONGO_URI=...
PORT=...
JWT_SECRET=...
NODE_ENV=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

### Run this app locally
 
### Install Backend Dependencies

```shell
npm install
```

### Install Frontend Dependencies

```shell
cd frontend
npm install
```

### Start Backend Server
From the root directory:

```shell
npm start
```

Starts backend server

Runs on http://localhost:5000

Uses environment variables from .env

### Start Frontend Development Server
From the frontend directory:

```shell
npm run dev
```

Starts frontend in development mode

Hot reload enabled

Usually runs on http://localhost:3000 or http://localhost:5173


### Notes

Backend and frontend run separately in development

Always run backend before frontend

Ensure API keys are valid