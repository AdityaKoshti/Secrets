# Secrets

# Live Demo
It's an Amazing Video Conferencing Web Application build over WebRTC and Socket.io<br>
Try Live Demo on below URL.<br>
https://secrets-zvij.onrender.com
```
https://secrets-zvij.onrender.com
```

## Table of content
  - [Features](#features)
  - [TechStack](#techstack)
  - [Development](#development)
  
## Features
* This is an authentication Interfaces with ****5 Levels of Security**** where you can store your secrets safely.
* It uses modern concepts such as _hashing, salting, DataBase Encryption_.
* In addition it uses _cookies and sessions_.
* It uses **Passport.js** for cookies and hashing.
* For saving the data it uses ****MongoDB**** database.
<br></br>
1. Front End / Client Side
   - EJS Templetes - App state management

2. BackEnd Server:
    - For Backend
      - Heroku NodeJs environment - deployment.
      - MongoDB Atlas
    - For Google OAuth2.0
      - PassportJS
    - Encryption and Decryption of Database
      - Passport-encryption
      - bcrypt
      - md5
    - Cookie-Sessions
      - express-sessions

3. Data Management (Databases): 
    - MongoDB- To Store User and Data Management


# Preview

## Here are some Key features of project:
### Some Glimpse of Web Application
#### Login/Register Interface:
![Starting Page](https://drive.google.com/uc?export=view&id=1rZrnodwKfzUEf8K0cIuy9av3630Q0R4S)

#### Login Page:
![Login Page](https://drive.google.com/uc?export=view&id=1OcUf5AR8jWnfZuwIB0z0IMGR7IEUKhcp)

#### Secret Page:
![Secrets Page](https://drive.google.com/uc?export=view&id=1TTzTC2rIWUDTD0S4JwXBbaPcc8xmiX9M)




  
## Development

## Instructions

### Open Terminal
1. Clone the Repo
````
git clone https://github.com/AdityaKoshti/Secrets.git secrets
```` 
2. Change the directory

```
cd ./secrets
```

3. Install node dependencies 
```
npm install
```

4. Replace MondoDB mongo URL for cloud hosting API keys with your configurations
5. Change the google client-id and secret in app.js

8. Run the command
```
node ./bin/www
```
7. The app is now running at http://localhost:3000 


## One More Point
```
if(like the repo) {
  star_the_repo()
}
```


#### Author: Aditya
