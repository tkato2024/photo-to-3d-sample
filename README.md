# Three-Legged Authentication sample

[![Node.js](https://img.shields.io/badge/Node.js-8.11.1-blue.svg)](https://nodejs.org/)
[![npm](https://img.shields.io/badge/npm-6.1.0-blue.svg)](https://www.npmjs.com/)
![Platforms](https://img.shields.io/badge/platform-windows%20%7C%20osx%20%7C%20linux-lightgray.svg)
[![License](http://img.shields.io/:license-mit-blue.svg)](http://opensource.org/licenses/MIT)

[![oAuth2](https://img.shields.io/badge/oAuth2-v1-green.svg)](http://developer.autodesk.com/)

# Description

This sample is part of the [3-Legged Authentication Walkthrough](https://forge.autodesk.com/developer/learn/threelegged-auth).

This sample illustrates how to use three-legged authentication.

## Thumbnail

![thumbnail](/thumbnail.png)

# Setup

## Prerequisites

1. A Forge account: [Getting Started with Forge](https://forge.autodesk.com/developer/getting-started)
2. A text editor of your choice. (For example Brackets or Visual Studio Code are good choices.)
3. A basic knowledge of :
   - HTML and CSS
   - JavaScript ES6
   - Command-line programs
     - Node.js Command Line (for Windows users)
     - Terminal (for Mac/Linux/Unix users)

## Running locally

Install [NodeJS](https://nodejs.org/) (version 8 or newer).

Clone this project or download it. It's recommended to install [GitHub desktop](https://desktop.github.com/).

To run it, install the required packages, set up your environment variables, and finally start it. Via command line, navigate to the folder where this repository was cloned and use the following:

```bash
npm install
```

Create a `.env.local` file in the root directory with your Forge credentials:

```
FORGE_CLIENT_ID=<<YOUR CLIENT ID FROM DEVELOPER PORTAL>>
FORGE_CLIENT_SECRET=<<YOUR CLIENT SECRET>>
```

Or you can copy `.env.example` to `.env.local` and edit it:

```bash
cp .env.example .env.local
```

Then start the server:

```bash
npm start
```

Open a browser and navigate to http://localhost:5000.

Click on the `Authorize me` link.

# License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

# Support

forge.help@autodesk.com
