Endpoint: `https://(www|beta).avabur.com/api/clans`

Lists all currently active clans in the game.

There is no way to get the member list, that's nly available for a [specific clan](https://github.com/edvordo/roa-apis/blob/master/clan-specific.md)

Example response

```json
[
    {
        "id": 2,
        "name": "High Times",
        "description": "HIGH TIMES TM is an unregistered trademark of RARE \"four figure rants\" INC and used under licence.",
        "level": 158,
        "level_percent": 27.78042173763488,
        "experience": 21367160174,
        "level_cost": 76914455712,
        "buildings": 158,
        "maxbuildings": 158,
        "members": 30,
        "maxmembers": 30,
        "exptax": 10,
        "goldtax": 2,
        "restax": 5,
        "droptax": 0,
        "member_list": []
    },
    {
        "id": 144,
        "name": "No Mans Land",
        "description": "                                   -Noble Soul Forces-\nQuantum indeterminism or  quantum field theory is the question",
        "level": 154,
        "level_percent": 78.8921424208249,
        "experience": 53433435426,
        "level_cost": 67729730473,
        "buildings": 154,
        "maxbuildings": 154,
        "members": 30,
        "maxmembers": 30,
        "exptax": 15,
        "goldtax": 0,
        "restax": 10,
        "droptax": 15,
        "member_list": []
    },
    ...
]
```
