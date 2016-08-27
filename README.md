# Angular-2
Learning Angular 2 (RC5)
Credits: https://github.com/angular/angular-cli#prerequisites


Angular-CLI

Build Status Dependency Status devDependency Status npm

Prototype of a CLI for Angular 2 applications based on the ember-cli project.

Note

This project is very much still a work in progress.

The current instructions on this file reflect usage for the webpack version.

Prerequisites

The generated project has dependencies that require Node 4.x.x and NPM 3.x.x.

Installation
Usage
Generating a New Project
Generating Components, Directives, Pipes and Services
Generating a Route
Creating a Build
Build Targets and Environment Files
Base tag handling in index.html
Adding extra files to the build
Running Unit Tests
Running End-to-End Tests
Deploying the App via GitHub Pages
Linting and formatting code
Support for offline applications
Commands autocompletion
Global styles
CSS preprocessor integration
3rd Party Library Installation
Global Library Installation
Updating angular-cli
Known Issues
Development Hints for hacking on angular-cli


Installation

BEFORE YOU INSTALL: please read the prerequisites

npm install -g angular-cli
Usage

ng --help
Generating and serving an Angular2 project via a development server

ng new PROJECT_NAME
cd PROJECT_NAME
ng serve
Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

You can configure the default HTTP port and the one used by the LiveReload server with two command-line options :

ng serve --port 4201 --live-reload-port 49153
