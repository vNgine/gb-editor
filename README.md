# gb-editor

# Installation and Usage
Clone or download this repo.    
Navigate to root directory of this repository and open the terminal:   

To start up the dev server:   
`cd react-client`   
`npm run dev` 

It should load on: http://localhost:3000/

### Dependencies: 
   - [electron](https://www.electronjs.org/docs/latest/tutorial/quick-start)

### DevDependencies:
   - electron-is-dev - used to check whether app in in dev or prod
   - concurrently and wait-on -  listen to the app and when it launches on the browser it will launch as an electron app instead

# Process
1. Create a React.js app using `create-react-app`.
2. Install and configure Electron into the application.