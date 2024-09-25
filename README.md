# WebViewer - Integrating server side search

[WebViewer](https://docs.apryse.com/documentation/web/) is a powerful JavaScript-based PDF Library that is part of the [Apryse SDK](https://apryse.com/). It allows you to view and annotate PDF files on your web app with a fully customizable UI.

![WebViewer UI](https://pdftron.s3.amazonaws.com/downloads/pl/webviewer-ui.png)

This sample shows how to build Node.js based server side search and how you can override default search functionality in WebViewer client.

## Initial setup
  
Before you begin, make sure your development environment includes [Node.js](https://nodejs.org/en/).

This example was built using Node.js version v12.18, but should work with newer versions as well.

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

## How to use

- Click search button on top right and execute any search.
- In the developer console notice the search is sent to backend.

## Documentation

[WebViewer](https://docs.apryse.com/documentation/web/).

[Node.js API](https://docs.apryse.com/documentation/core/guides/?language=nodejs).

## License

For licensing, refer to [License](LICENSE).