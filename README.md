# Node.js OAuth 2.0 Quickstart

A quickstart app for integrators looking to use HubSpot's OAuth 2.0. Written in Node.js.

_**Note:** This app does not store any data in a persistent way, so restarting the app will clear the retrieved access tokens._

   
## Prerequisites

Before running the quickstart app, make sure you have:

1. The tools required to run using the method of your choice:
   - Option 1: Running locally using Node.js: [Node.js (>=6)](https://nodejs.org) and [yarn](https://yarnpkg.com/en/docs/install)

_**Note:** You must be a super-admin for the account that you want to install the app in._

## Running locally using Node.js

1. Clone the repository:
   ```bash
   $ git clone git@github.com:HubSpot/oauth-quickstart-nodejs.git
   ```
2. From the root of the repository, run:
   ```bash
   $ yarn install
   $ yarn start
   ```
3. Open your browser to `http://localhost:3000/install` to kick off the OAuth 2.0 flow
