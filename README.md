# Golang Server Test

![GoLang Icon](https://golang.org/doc/gopher/gophercolor.png)

The project is a simple web server implemented in GoLang. It serves a static HTML page (index.html) along with associated CSS (styles.css) and image (001.gif) files from a static directory. This server demonstrates basic routing and static file serving capabilities using Go's built-in HTTP server functionalities.


## Installation

Make sure you have Go installed. You can download it from [golang.org](https://golang.org/).

Clone the repository:

```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject
```

## Usage

To run the server:

```bash
go run main.go
```

This will start the server on `localhost:8080`.

## Project Structure

```
projeto/
├── main.go
└── static/
    ├── index.html
    ├── styles.css
    └── 001.gif
```

- `main.go`: Main Go file containing the server code.
- `static/`: Folder containing static files served by the server.
  - `index.html`: Main HTML file served at the root endpoint.
  - `styles.css`: CSS file for styling.
  - `001.gif`: Sample image file.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
