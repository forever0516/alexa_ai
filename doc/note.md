### Intent Schema

```
{
  "intents": [
    {
      "intent": "GetWeatherByTime",
      "slots": [
        {
          "name": "time",
          "type": "AMAZON.DATE"
        }
      ]
    },
    {
      "intent": "GetAirQuality",
      "slots": [
        {
          "name": "country",
          "type": "AMAZON.Country"
        }
      ]
    },
    {
      "intent": "SingSong"
    },
    {
      "intent": "BallGame",
      "slots": [
        {
          "name": "sportType",
          "type": "AMAZON.Sport"
        }
      ]
    },
    {
      "intent": "GetLuckyNumbers",
      "slots": [
        {
          "name": "UpperLimit",
          "type": "AMAZON.NUMBER"
        }
      ]
    }
  ]
}
```


Sample Utterances

```


GetAirQuality what's the air quality in {country}
GetAirQuality is the air bad
GetAirQuality It stinks

SingSong can you sing a song
SingSong I want to listen songs
SingSong give me a song
SingSong quiet

BallGame what is the {sportType} 
BallGame search {sportType}
BallGame google {sportType}
BallGame what's the {sportType}

GetLuckyNumbers what are my lucky numbers
GetLuckyNumbers tell me my lucky numbers
GetLuckyNumbers what are my lucky numbers lower than {UpperLimit}
GetLuckyNumbers tell me my lucky numbers lower than {UpperLimit}

GetWeatherByTime what's the weather {time}
```


