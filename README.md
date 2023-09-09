# Bharat-Intern-Tasks

## Task - 1
Content Management Tool - Headless CMS with Contentful and Next.js

## Features

- Integration with Contentful's Headless CMS.
- Dynamic content retrieval and rendering with Next.js.
  
* 1. Install Dependencies:
```javascript
      npm install
```
* 2. Configuration:

    Set up your Contentful space and API access.
    Add your Contentful credentials to the project.
  
* 3.Run the Development Server:
```javascript
     npm run dev
```

## Task - 3 
Video conferencing website

* 1 - Create an account on agora.io and create an app to generate an APP ID
* 2 - Create a config.js file and enter your APP_ID in an object
```javascript
const config = {
  APP_ID : ' YOUR-APP-ID '
}
```
* 3 - In your javascript file , declare variables that point to your APP_ID in the config file 
```javascript
const app_id = config.APP_ID;
```
* 4 - Create a .gitignore file and enter file names that you want git NOT to track/commit/push.
In this case you would enter,
```javascript
config.js
```
