# URL Shortener Service

A simple URL shortening service built with Node.js, Express, MongoDB, and EJS. This application allows users to shorten long URLs and redirect to the original URLs using a short, unique code.

## Features

- Shorten long URLs
- Redirect from short URLs to original URLs
- View all shortened URLs

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (installed and running locally)

### Installation
This application allows users to shorten long URLs for easier sharing. Built with Node.js and Express for the backend, it uses MongoDB to store and manage URL mappings. EJS (Embedded JavaScript) is employed for server-side rendering of the user interface.

- Node.js: Provides the runtime environment for the server-side logic.
- Express: Handles HTTP requests and responses, routing, and middleware.
- MongoDB: Stores original and shortened URLs, using a collection to manage data.
- EJS: Renders dynamic HTML pages on the server side, allowing users to interact with the URL shortening service through a web interface.

### Users can enter a long URL, and the service will generate a short, unique URL. When accessed, the short URL redirects to the original long URL.
