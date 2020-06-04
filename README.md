# JSDraw-Demo
testing React compatibility with JSDraw

-----------------------

## Project Tree
- orig (raw JSDraw examples)
    - Demo.html example of JSDraw molecule editor and modicule display only
- client (the frontend: ReactJS, etc)
    - Single Page App
    - build process:  webpack(babel(React+JSX)) => bundle.js
- server (the NodeJS backend: web services, etc.)
    - NodeJS serves up initial index.html + bundle.js
    - NodeJS provides the web API needed by frontend

-----------------------------

## Initial creation of the client directory
```
npx create-react-app client
cd client
npm start
```
