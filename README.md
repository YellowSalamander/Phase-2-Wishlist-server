#JSON Server for Wishlist Application
This repository contains a simple JSON server that serves as a backend for a Wishlist application. It provides endpoints to manage favorite games and user data for the Wishlist tracker 
project.

##Getting Started

To run the server locally, follow these steps:

1. Clone this repository to your local machine:
    //git clone <repository-url>

2. Install the required dependencies:
    //npm install

3. Start the JSON server:
    //npm run start

#Example Data
Here is an example of the initial data structure in db.json:

{
  "FavGames": [
    {
      "gameID": "202278",
      "gameTitle": "Baldur's Gate 3",
      "thumb": "https://cdn.cloudflare.steamstatic.com/steam/apps/1086940/capsule_sm_120.jpg?t=1695393586",
      "id": 202278
    },
    // Add more favorite games here
  ],
  "user": [
    {
      "id": "193006",
      "gameID": "193006",
      "gameTitle": "PROTEST"
    }
  ]
}

Usage
You can use the provided endpoints to manage your favorite games and user data in your Wishlist application. Feel free to extend and customize this JSON server to suit your project's requirements.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

