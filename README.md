<h1 align="center">SoccerBoard App</h1>
<p align="center">Soccer scoreboard App made using Flutter and API-FOOTBALL</p>
<p align="center">
  <img src="docs/1.png" height="600em"/>
</p>

## Getting Started

- API website: https://api-sports.io/

- API-FOOTBAL Documentation: https://api-sports.io/documentation/football/v3

Register here to get a new API Key: [API-SPORTS](https://dashboard.api-football.com/)

Access your API key: https://dashboard.api-football.com/profile?access

Then put your API Key in lib/services/soccer.dart:

``` dart
  static const headers = {
    'x-rapidapi-host': "v3.football.api-sports.io",
    'x-rapidapi-key': "YOUR_API_KEY"
  };
```
