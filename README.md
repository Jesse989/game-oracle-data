# Game Oracle
## About
Predict the success of a game before investing time on development.

Predictions are created using Machine Learning models trained on data gathered from various sources.

Success is based on the metacritic score as there is no reliable way to find the monetery success of most of the games.

## Features
Which features are strong indicators as to whether or not a game will be succesful.

| Feature | Type | Description | Source |
|---------|------|-------------|--------|
| Name    | String | Original Title | RAWG API |
| RawgID | Integer | RAWG unique ID | RAWG API |
| SteamURL | String | Steam URL | Steam |
| Metacritic | Integer | Games metacritic rating | RAWG API |
| Genres | String Array | List of genres associated with game | Steam |
| Indie | Boolean | Whether or not the game was created by indie developers | Steam |
| Presence | Integer | Number of posts on social media sights e.g. Reddit | RAWG API |
| MonetizationModel | String | How the game is setup to generate revenue | Steam |
| Platform | String Array | Which platforms the game was built to run on | RAWG API |
| Graphics | String | Required GPU for running the game | RAWG API
| Storage | Integer | How much storage space is required to download the game | RAWG API |
| RatingsBreakdown | Object | Percent of ratings that were good, medium, or bad | RAWG API |
| ReleaseDate | String | When the game was released | RAWG API |
| Soundtrack | Boolean | Whether or not the game has been tagged for a notable soundtrack | Steam |
| Franchise | Boolean | Is the game part of a larger franchise | Steam |
| OriginalCost | Float | How much in USD the game cost at release | Steam |
| DiscountedCost | Float | How much the game costs currently in USD | Steam |
| Players | String | Single-player, multi-player, split-screen, etc | Steam |
| Controller | Boolean | Whether or not the game can be played with a controller | Steam |
| Languages | String Array | Which languages are available in-game | Steam |
| ESRB | String | Recommended appropriate age and type of inappropriate content | Steam |
| Achievements | Integer | How many achievements can be earned in game | RAWG API |
| Publisher | String Array | Companies responsible for publishing the game | RAWG API |
| Description | String | How the game developer describes the game | RAWG API |
