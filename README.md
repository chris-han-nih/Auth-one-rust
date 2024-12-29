# Auth-one-rust

## Project Description and Purpose

Auth-one-rust is an authentication server built using the Actix web framework in Rust. The purpose of this project is to provide a robust and efficient authentication server that can be easily integrated into various applications.

## Setup Instructions

### Dependencies

To set up the project, you need to have the following dependencies installed:

- Rust (https://www.rust-lang.org/tools/install)
- Cargo (comes with Rust installation)

### Running the Server

1. Clone the repository:
   ```sh
   git clone https://github.com/chris-han-nih/Auth-one-rust.git
   cd Auth-one-rust
   ```

2. Build the project:
   ```sh
   cargo build
   ```

3. Run the server:
   ```sh
   cargo run
   ```

The server will start on `127.0.0.1:8080`.

## Usage Instructions

### Example Request

To test the server, you can use `curl` or any HTTP client to make a request to the server:

```sh
curl http://127.0.0.1:8080/
```

You should receive a response with the text "Hello, world!".
