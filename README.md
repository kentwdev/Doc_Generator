Live DEMO: [Document_Denerator](https://relaxed-albattani-bbdaa4.netlify.app/).


## Project local Setup 

## Having trouble setiting up read:
https://microsoft.github.io/react-native-windows/docs/getting-started

# Installation:
1. Create a new directory
```mkdir DocGenerator```

2. Move to the project folder, ```using cd DocGenerator```, so we can install React into it.

3. Create a new React App with ```create-react-app client``` and then move into newly created directory and install dependencies ```cd client && npm i -S axios file-saver```

4. Create an Express server with ```mkdir server && cd server && touch index.js && npm init``` hit enter a couple of times to initialize package.json and 

5. then run ```npm i -S express body-parser cors html-pdf ``` to save all the necessary dependencies.

6. Add proxy inside of client/package.json, above the dependencies, simply add ```“proxy”: “http://localhost:6000/"```, so you can call the localhost from the client.

7. Open two different terminals:
First one: go into the client directory and ```run npm start```
Second one: go into the server directory and ```run nodemon index.js```



## Credits:
[Create React App](https://github.com/facebook/create-react-app).
