# Simple Rust HTTP Server

This project is a basic HTTP server written in Rust. It listens for incoming HTTP requests on port `9999` and serves an `index.html` file from the root directory. If the file is not found, it responds with a 404 Not Found error. This server is intended for educational purposes to demonstrate basic Rust programming concepts and network communication.

## Prerequisites

- [Rust programming language](https://www.rust-lang.org/tools/install) (including Cargo, Rust's package manager and build tool).

## Getting Started

To get a local copy up and running, follow these simple steps.

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://your-repo-link-here
```

2. Navigate to the project directory:

```bash
cd simple-rust-http-server
```

### Running the Server

1. Build and run the server with Cargo:

```bash
cargo run
```

2. Once the server is running, it will listen for HTTP requests on `localhost:9999`.

3. To test the server, open a web browser and navigate to `http://localhost:9999`. You should see the contents of the `index.html` file displayed. If `index.html` does not exist, the server will respond with a 404 Not Found error.

### Adding `index.html`

Create an `index.html` file in the root directory of the project with the following content for testing:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Rust HTTP Server</title>
</head>
<body>
    <h1>Hello from Rust HTTP Server!</h1>
</body>
</html>
```

## Note

This server is a basic example for educational purposes and lacks many features and security measures required for a production environment. For real-world applications, consider using robust web frameworks and servers like [Actix-web](https://actix.rs/), [Rocket](https://rocket.rs/), or [Hyper](https://hyper.rs/).

---
