# Netflix Rebuild in React
A clone of Netflix built in React. The rebuild is not complete in the sense that not all features is included. 
Included features: sign in and sign out with Firebase connectivity, video player, video browser, search bar.

*******


<p align="center">
  <img src="/images/readme/browser.png"
</p>


Sign in            |  Sign up
:-----------------------------:|:------------------------------:
![](/images/readme/signin.png) |  ![](/images/readme/signup.png) 
Choose user            |  Video slider and selector
|||
![](/images/readme/chooseuser.png) |  ![](/images/readme/videoslider.png)


----

# Firebase Connectivity

In order to authenticate the user I use Firebase as the backend which can be set up [here](https://firebase.google.com/). 
The resulting Firebase configuration looks something like the (incomplete) example below in which `config` is to be included in 
`/src/index.js`.

```javascript
// Your web app's Firebase configuration
const config = {
  apiKey: 'AIzaSyDAU60M2FDHNsYt9uGMs',
  authDomain: 'netflix.firebaseapp.com',
  databaseURL: 'https://netflix.firebaseio.com',
  projectId: 'netflix',
  storageBucket: 'netflix.appspot.com',
  messagingSenderId: '59057580',
  appId: '1:59057581:web:f809092b6cd5530',
};
// Initialize Firebase
  firebase.initializeApp(firebaseConfig);
```


-------------------------------------------------------


# Local Development



* Clone the repo: `git clone https://github.com/VebjornG/Netflix-rebuild-react.git`
* Install the npm package : `npm i`
* Start client using webpack dev server: `npm run start` and visit localhost in your browser `http://localhost:8080`

