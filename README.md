# fullstack-chat-app

A template for a fullstack javascript application, inspired by [this](https://github.com/atulmy/fullstack-javascript-architecture) repo. The folder structure is experimental and quite opinionated, but serves well for my purposes.

### Stack of application:
* **Node.js** for the backend server
* **React** for the web application 
* **React Native** for Android and iOS app

### Folder Structure:
     fullstack-js-app
      ├── backend
      │   ├── api
      │   │   > NodeJS
      │   │   > PORT 8000
      │   │   > api.example.com
      │
      ├── frontend
      │   ├── mobile
      │   │   > React Native
      │   │   > iOS (Apple App Store)
      │   │   > Android (Google Play Store)
      |   |
      │   ├── mobile
      │   │   > React 
      │   │   > Single page application
      │
      └── README.md 
      
### Note
* This repo nests three git repos inside it, although the idea is to perform version control centrally from root folder, it does seem intutive to let each project have thier own .gitignore files.
* I was not able to create react application using facebook's ```create-react-app``` command. For some reason git was interpreting the folder as a submodule, and it didn't know where to fetch the submodule. So I had to manually configure webpack, babel and npm's package.json script. 
