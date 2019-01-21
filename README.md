# Giphy API Activity
This is my first project using a third party API. Between me and my group of three, we created an app where users can search the Giphy API, select a category for giphy results and favorite gifs.

## Setup

1. Create a `.env` file and add your API key.

    `GIPHY_API_KEY=YOUR_KEY_GOES_HERE`

2. Spin up your app:

    - `npm install`
    - `npm run server`
    - `npm run client`

## Task List

- [x] Make a `GET` request to Giphy from the `/random` router on your **server**, send the response from Giphy back to the client
- [x] Make a `GET` request from your **client** to your `/random` route, save the response data in Redux
- [x] Display the random gif on the page, spend some time looking through the response! Some of the properties returned look like image paths but aren't.
- [x] Add a button that allows the user to refresh the results by making another `GET` request to `/random`

