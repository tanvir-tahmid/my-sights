# my-sights
### A site to share you thoughts on sights you have been to around the world

# View Demo:
https://firstfirebase-24e8d.web.app/

# Some Features Include:
* Image and File Upload
* Authentication and Authorization
* Login and Register accounts
* Create, edit, and delete sights

# To Run:

In your terminal, on both the backend and the frontend folder, run:

```
npm install
```

To connect to Mongo Database and use Google's Map API, create a .env file in your backend folder and add the following:
```
DB_USER=<user>
DB_PASSWORD=<pass>
DB_NAME=<name>
GOOGLE_API_KEY=<key>
JWT_KEY=<secret>
```

In your frontend folder, create a .env file and add the following:
```
REACT_APP_GOOGLE_API_KEY=<key>
REACT_APP_BACKEND_URL=<url>
REACT_APP_ASSET_URL=<url>
```
In your terminal, on both the backend and frontend folder, run:

```
npm start
```

Open your browser and head to localhost:3000

You are now on MySights

