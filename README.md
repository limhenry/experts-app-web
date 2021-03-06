![App Screenshot](http://s32.postimg.org/x11aap2px/rsz_experts_at_io_compressed.jpg)
Google Experts tracking app
===========================
###### built with <3 by the GE Tracking App Team
[![Preview](https://s3.postimg.org/cqz89z2mb/gde_front.png)](https://postimg.org/image/6da56pxq7/)

The GDE App aims to help Google Experts track their activities and give Googlers a way to analyze the impact of the program and it's members. It's a progressive web app built with Polymer 1.0 toolbox, please refer to [oficial documentation](https://www.polymer-project.org/1.0/docs/) if you require more information.

## Requirements

All requirements were done in a collaboration between Googlers and volunteers from the [Google Experts](https://developers.google.com/experts/) program.

[Version 2.0.0 Requirements](https://docs.google.com/document/d/1bZIIR9yUOMI8dZzmPRyIGVPUO9Ov85Xq31FWbpRHnHQ/edit)

### Setup

##### Prerequisites

You need NodeJS and NPM installed.

https://nodejs.org/en/download/

Run the following commands from you console.

    npm install -g polymer-cli
    bower install

##### New to Polymer progressive web apps?

This software uses the [Polymer App Toolbox](https://www.polymer-project.org/1.0/toolbox/) introduced in Google I/O 2016.

This tutorial  will familiarize you with the core frontend technology on this project.

https://www.polymer-project.org/1.0/start/toolbox/set-up

### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve

### Build for production

This command performs HTML, CSS, and JS minification on the application dependencies, and generates a service-worker.js file with code to pre-cache the dependencies based on the entrypoint and fragments specified in `polymer.json`.

    polymer build

### Deploy for staging

Before deploying to production, changes must be tested in our staging server hosted on firebase. Once you have built your changes for production, deploy using to firebase using:

    firebase deploy
    
You can request staging deployment to @reicek .

Production deployment can only be done by @patt0 .
