# Cloudflare Downloader Proxy

This is a simple and efficient tool to download files from the internet using Cloudflare Workers as a proxy.

## How to Use

To download a file, use the `/download/` endpoint with the file URL. 

For example: 

/download/https://example.com/file.zip


This will initiate the file download from the specified URL through the Cloudflare Workers.

## Setup and Run

Follow these steps to set up and run the downloader proxy:

1. Install the necessary dependencies:

```
npm install
```

Start the development server:
```
npm run dev
```

Deploy the application to Cloudflare Workers:
```
npm run deploy
```

