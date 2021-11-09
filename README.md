# About
This is simple Blog application build using React Native.
It uses json-server package for running local API which also acts as database.
It allows you to **view**, **edit** and **delete**  your blog posts.

## Setup
1. Run React Native application with **"expo r -c"**.
2. Start json-server with **"npm run db"**
3. Start ngrok service to serve localhost API in web with **"npm run tunnel"**
	** allows to make requests from mobile device to API)
4. Copy current ngrok forwarding link and paste it to jsonServer.js
	** update link every 2 hrs