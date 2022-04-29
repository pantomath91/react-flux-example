# Simple React + Flux example in ES6

I could not find a very basic example of how to use React with the Flux architecture.
After finally figuring them out I decided to create a simple example myself for future reference.
It is roughly based on this article: http://blog.andrewray.me/flux-for-stupid-people/.
This example does not make use of actions.

### Installation & Usage

You need to have [npm](https://nodejs.org/en/download/) installed.
Also [gulp](http://gulpjs.com/) needs to be installed globally:
`npm install -g gulp`

First install all the required node modules:
`npm install`

Then build the project:
`gulp`

Then open `./dist/index.html` in your browser

### Simple Flow

Components--->Actions--->Dispatcher(We have created a queued dispatcher over here which queue all dispatchers)---->Store---->Components get updated
