This is a prototype of an Angular application with an "invisible" GWT application in background that can be accessed via a JavaScript namespace.

# How to Run Locally

You need to have Maven and Node.js installed. Then, `cd` into your project folder.

## Run the Angular App

```
npm install
```

and

```
npm start
```

## Run the GWT App

```
mvn compile
```

```
mvn gwt:run
```

## Start the App

Visit [http://localhost:8000/app/](http://localhost:8000/app/)

![.](http://i.imgur.com/JLiI5Nx.gif)
