# To build project

```
python -m SimpleHTTPServer # for python 2.
python -m http.server # for python 3.
http://localhost:8000/ # for running
```

# To sync PouchDB local database

## Install PouchDB server and run

```
npm install -g pouchdb-server
pouchdb-server -p 3000
```

## To see the local PouchDB "todos" of the app

```
http://127.0.0.1:3000/_utils/ # for visualization
http://127.0.0.1:3000/todos/ # for direct data
```
