# Spacebrew + Temboo: Yahoo Weather
### A simple-ish example

## Setup
* install node modules
```
cd THIS FOLDER
npm install feedparser
npm install forever-monitor
npm install request
npm install ws
```
* download the [Temboo NodeJS SDK](https://www.temboo.com/support/getting-started/sdk/nodejs/2)
	* install it into your node_modules folder
* Create an application with Temboo and create an "auth_temboo.js" file in /auth
	* Base it off of the template_temboo.js file in that folder
	* Add your application name and Temboo key
* TO-DO: right now the lat and long are hard-coded to NYC. This is easy to change to another Temboo API call, I just was lazy... Sorry
* Run the app!
```
node app.js
```
	* It will output the current temp as a spacebrew range, the current conditions as a string, and the condition code (see Yahoo's API) as a range.
