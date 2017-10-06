# Simplewiki

Simplewiki is a web server that presents a folder as a wiki page. The wiki page
supports viewing both markdown files and images.

![Screenshot](docs/screenshot.png)

## Usage

Go to the folder you want to look at, then run `simplewiki`.

For more options, run `simplewiki --help`.

## Features

- Easy deployment. Add the binary to your $PATH, and call anywhere.
- Auto refresh by using a web socket.
- Syntax highlighting.
- Auto generated table of contents.
- Highly insecure. Only run on localhost.

## Installation

```
cargo install --git https://github.com/sighol/simplewiki
```
