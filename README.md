# Integrating server side search to WebViewer Sample

This sample shows how to build Node.js based server side search and how you can override default search functionality in WebViewer client.

## Initial setup
  
Before you begin, make sure your development environment includes [Node.js](https://nodejs.org/en/). Example was built using Node.js version v12.18, but should work with newer versions as well.

## Install

```
git clone https://github.com/PDFTron/webviewer-server-side-search.git
cd webviewer-server-side-search
npm install
```

## Run

```
npm start
```

This will start web-server that you can access WebViewer client http://localhost:8080/. On the same server we run our search REST API and it is available http://localhost:8080/api/search using GET http method.

To access search, click search button on top right and execute any search. You can see from developer console that search is sent to backend.

## Documentation

[WebViewer documentation](https://www.pdftron.com/documentation/web/).

[Node.js API documentation](https://www.pdftron.com/documentation/nodejs/).
