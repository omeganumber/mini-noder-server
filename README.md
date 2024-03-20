# mini-node-server

A minimalistic Node.js server with basic routing and static file serving capabilities, built with Express.

## Installation

To install `mini-node-server`, clone this repository and install its dependencies:

```bash
git clone <repository-url>
cd mini-node-server
npm install
```

## Usage

To start the server, run:

```bash
npm start
```

This will start the server on `http://localhost:3000`. The server serves static files from the `public` directory and
has a basic API endpoint at `/api`.

## Dependencies

- `express`: For handling HTTP requests and serving static files.
- `morgan`: For HTTP request logging.
