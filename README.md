# Project Generator

## Introduction

This is a CLI (Command-Line Interface) generator for **At Least They Tried** coding projects. It provides a basic Node.js setup for our web projects.
At the moment there is only one selectable template which contains :

- an [express.js](https://expressjs.com/) web server
- the [p5.js](https://p5js.org/) library for creative coding
- our css graphical charter
- some basic html files

The generator code was based from Harriet Ryder's medium article [Creating a project generator with Node](https://medium.com/northcoders/creating-a-project-generator-with-node-29e13b3cd309).

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- Node.js (version 12 or later)

## Installation

### Cloning the Repository

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/atleasttheytried/project-generator.git
    ```

2. Navigate into the project-generator directory:

    ```bash
    cd project-generator
    ```

3. Install the required npm packages:

    ```bash
    npm install
    ```

### Installing Globally on Your Computer

To install the project generator globally and use the `generate` command from anywhere on your computer, run:

```bash
npm install -g
```

This command makes the generate command available globally. After installation, you can simply use generate to start a new project from any location on your computer using the following :

    ```bash
    generate
    ```

Follow the interactive prompts to select your project template and specify other project details.

### License

CC0-1.0 - No Rights Reserved (2024) - At Least They Tried
For more information on CC0 see the LICENSE file
<!-- and read our [License Statement](https://www.atleasttheytried.org/license) -->
