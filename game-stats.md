Endpoint: `https://(www|beta).avabur.com/api/game/stats`

Shows various statistics in-game. Seems to update always, not just when the `"next"` counter ticks.

Example response

```json
{
    "next": "42 seconds",
    "TodaySignups": 1,
    "TodayGoldLooted": 251595272077,
    "TodayKills": 2639894,
    "TodayHarvests": 479312,
    "TodayResources": 463668575,
    "TodayClans": 0,
    "TodayCrafts": 315287,
    "TodayCarves": 123526,
    "AllTimeSignups": 17635,
    "AllTimeGoldLooted": 84041185831550,
    "AllTimeKills": 4904968032,
    "AllTimeHarvests": 1993706406,
    "AllTimeResources": 395702366435,
    "AllTimeItemsFound": 82268379,
    "AllTimeQuestsCompleted": 1475436,
    "AllTimeCurrentGold": 6737648930456,
    "AllTimeCurrentPlat": 1010935901,
    "AllTimeCrafts": 394490281,
    "AllTimeCarves": 140409198,
    "AllTimeCurrentMats": 1070727361,
    "AllTimeCurrentFrags": 940165129,
    "AllTimeCurrentRes": 88816233623,
    "AllTimeOnline": 907,
    "NowOnline": 854,
    "TodayActive": 980,
    "AllTimeClans": 299
}
```
