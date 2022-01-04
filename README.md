# mern-stack-example
Mern Stack code for the [Mern Tutorial](https://www.mongodb.com/languages/mern-stack-tutorial)

Check Atlas: https://cloud.mongodb.com/v2/61d393338715794838fcb520#metrics/replicaSet/61d39410d30da15f0f1b6d16/explorer/myFirstDatabase/records/find

## Read more

1. https://mongodb.github.io/node-mongodb-native/3.4/tutorials/crud/
2. https://nextjs.org/examples
3. https://reactjs.org/docs/create-a-new-react-app.html

## How To Run
Create an Atlas URI connection parameter in `mern/server/config.env` with your Atlas URI:
```
ATLAS_URI=mongodb+srv://<username>:<password>@sandbox.jadwj.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
PORT=4000
```

Start server:
```
cd mern/server
npm install
npm start
```

Start Web server
```
cd mern/client
npm install
npm start
```

## Disclaimer

Use at your own risk; not a supported MongoDB product
