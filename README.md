Simple PHP Web Server for Mac
=======================

A convenient droplet app to quickly serve a PHP web server on Mac OS X.

## Introduction

While working on web projects, it's often convenient to be able to quickly serve up a site directory on your Mac using a PHP web server for development or testing. This little app does just that: give it a directory and it fires up a PHP web server to serve it from your Mac.

## Requirements

This "App" is a really thin wrapper around Mac OS X functionality to start a PHP web server module, which comes with most recent versions of Mac OS X.

## Usage

There are two ways to run the Simple PHP Web Server:

1. Launch the app, then choose a directory using the dialog.
2. Drag & Drop a directory on top of the app's icon.

## Limitations

This app relies heavily on the inbuild PHP web server module, which is, pretty simple. Don't expect high performance or many features.

The app supports only one server instance at a time. If you need more, use something more advanced or use the terminal to start the PHP web server module from there.

Start it with **php -S localhost:8080** to serve the current directory as server, or **php -S localhost:8080 -t local_path_to_server** to serve another directory, e.g. **php -S localhost:8080 -t ~/Sites** for the Sites directory in your home directory.