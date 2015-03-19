# OAuth2 PostMessage Flow

Implementation of a postMessage-based secure channel for cross-domain communication for OAuth2. Written in Javascript.

See README file for more information, including a file overview and licensing information.

## This repo purpose

* Mirror of dying [Google Code repo](https://code.google.com/p/oauth2-postmessage-profile/)
* Examples changed to consume Google+ API instead of dead Google Buzz
 
## Usage 

* Serve folder at some domain and port
* [Create project and obtain client id](https://developers.google.com/+/web/signin/) using those port and domain as Javascript origins and full URI of `examples/app/app.html` file as redirect URIs 
* Insert client id into `examples/app/app_config.js`
* Check if it works

