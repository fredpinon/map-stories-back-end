# Map Stories Backend

## Description
Map Stories is a location based storytelling app. Editors can create map based stories and place markers on the map. Each marker is associated with an event, which has information and attachments.

## Motivation
People have a difficult time understanding stories that take place on an unfamiliar map. By locating the narrative key points of a story on a map, Map Stories help story makers orient their viewers.

## Dependencies

- Node
- MongoDB

## Installation

- Clone this repo and cd into it
- Run `npm install`
- Run `cd server`
- Run `npm run dev`
- Clone the [front-end](https://github.com/fredpinon/map-stories-front-end) repository and follow installation instructions.

## Usage with Postman
Download the [Map Stories Collection](https://documenter.getpostman.com/view/2573635/map-story-localhost/71FXBMv).
In Postman: Manage Environments > Globals
Under Key, set a property, Token and input a dummy token to test authenticated routes.  

## Tech Stack
- Koa
- MongoDB
- Mongoose
- Mocha, Chai and Sinon
