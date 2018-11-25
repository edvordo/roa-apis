Endpoint: `https://(www|beta).avabur.com/api/users`

**Requires a list of usernames you want to show** passed as a query parameter `ids[]`

Contains info about clan under the `"clan"` key in the json response. 
`clan` will always have an `id` and `name`, but they can be `null` if the given user is not in a clan

Example endpoint: `https://www.avabur.com/api/users?ids[]=Vysn&ids[]=Reltorakii`

Example response

```json
[
    {
        "username": "Vysn",
        "fame": 41104,
        "levels": {
            "house": {
                "level": 37,
                "rank": 29
            },
            "character": {
                "level": 188,
                "rank": 132
            },
            "fishing": {
                "level": 705,
                "rank": 66
            },
            "woodcutting": {
                "level": 442,
                "rank": 207
            },
            "mining": {
                "level": 433,
                "rank": 205
            },
            "stonecutting": {
                "level": 483,
                "rank": 184
            },
            "crafting": {
                "level": 321,
                "rank": 22
            },
            "carving": {
                "level": 88,
                "rank": 135
            }
        },
        "battle": {
            "kills": {
                "value": 7500449,
                "rank": 121
            },
            "deaths": {
                "value": 11736,
                "rank": 1193
            }
        },
        "harvests": {
            "harvests": {
                "value": 595847,
                "rank": 770
            },
            "resources": {
                "value": 158233936.29865173,
                "rank": 314
            }
        },
        "profession": {
            "crafts": {
                "value": 1303375,
                "rank": 73
            },
            "carves": {
                "value": 88844,
                "rank": 234
            }
        },
        "misc": {
            "event_actions": {
                "value": 179136,
                "rank": 293
            },
            "experience_gained": {
                "value": 124670103960,
                "rank": 140
            },
            "gold_looted": {
                "value": 189672684840,
                "rank": 114
            },
            "fatigue_actions": {
                "value": 3781905,
                "rank": 87
            },
            "total_event_score": {
                "value": 383853,
                "rank": 231
            }
        },
        "quests": {
            "total": {
                "value": 1104,
                "rank": 177
            },
            "battle": {
                "value": 894
            },
            "harvest": {
                "value": 114
            },
            "profession": {
                "value": 96
            }
        },
        "stats": {
            "base": {
                "value": 156373,
                "rank": 106
            },
            "total": {
                "value": 222526,
                "rank": 120
            }
        },
        "skills": {
            "counter_attack": {
                "value": 115.22,
                "rank": 115
            },
            "healing": {
                "value": 114.16,
                "rank": 122
            },
            "unarmed_combat": {
                "value": 2.53,
                "rank": 535
            },
            "melee_weapons": {
                "value": 9.51,
                "rank": 1301
            },
            "ranged_weapons": {
                "value": 4.5,
                "rank": 1419
            },
            "magical_weapons": {
                "value": 112.64,
                "rank": 12
            },
            "evasion": {
                "value": 114.29,
                "rank": 119
            }
        },
        "training": {
            "base_damage": {
                "trains": 325,
                "value": 31320,
                "rank": 178
            },
            "base_armor": {
                "trains": 450,
                "value": 20475,
                "rank": 111
            },
            "multistrike_chance": {
                "trains": 2000,
                "value": "100.00%",
                "rank": 109
            },
            "critical_hit_chance": {
                "trains": 2250,
                "value": "180.00%",
                "rank": 118
            },
            "critical_hit_damage": {
                "trains": 1500,
                "value": "150.00%",
                "rank": 131
            },
            "toughness": {
                "trains": 500,
                "value": "10.00%",
                "rank": 278
            },
            "counter_attack_damage": {
                "trains": 250,
                "value": "5.00%",
                "rank": 266
            },
            "healing_boost": {
                "trains": 500,
                "value": "5.00%",
                "rank": 195
            },
            "fishing_boost": {
                "trains": 0,
                "value": "0.00%",
                "rank": 4652
            },
            "woodcutting_boost": {
                "trains": 0,
                "value": "0.00%",
                "rank": 4652
            },
            "mining_boost": {
                "trains": 0,
                "value": "0.00%",
                "rank": 4652
            },
            "stonecutting_boost": {
                "trains": 0,
                "value": "0.00%",
                "rank": 4652
            },
            "crafting_boost": {
                "trains": 3750,
                "value": "300.00%",
                "rank": 31
            },
            "carving_boost": {
                "trains": 1000,
                "value": "80.00%",
                "rank": 63
            }
        },
        "clan": {
            "id": 17, // will be null if the user is not in clan
            "name": "Example" // will be null if the user is not in clan
        }
    },
    {
        "username": "Reltorakii",
        "fame": 39223,
        "levels": {
            "house": {
                "level": 35,
                "rank": 64
            },
            "character": {
                "level": 212,
                "rank": 76
            },
            "fishing": {
                "level": 449,
                "rank": 181
            },
            "woodcutting": {
                "level": 429,
                "rank": 226
            },
            "mining": {
                "level": 428,
                "rank": 216
            },
            "stonecutting": {
                "level": 427,
                "rank": 232
            },
            "crafting": {
                "level": 13,
                "rank": 1392
            },
            "carving": {
                "level": 27,
                "rank": 410
            }
        },
        "battle": {
            "kills": {
                "value": 11971020,
                "rank": 23
            },
            "deaths": {
                "value": 145877,
                "rank": 45
            }
        },
        "harvests": {
            "harvests": {
                "value": 159004,
                "rank": 1639
            },
            "resources": {
                "value": 118992465.73592491,
                "rank": 368
            }
        },
        "profession": {
            "crafts": {
                "value": 6642,
                "rank": 1248
            },
            "carves": {
                "value": 5167,
                "rank": 614
            }
        },
        "misc": {
            "event_actions": {
                "value": 225056,
                "rank": 219
            },
            "experience_gained": {
                "value": 225272774768,
                "rank": 78
            },
            "gold_looted": {
                "value": 333736499763,
                "rank": 65
            },
            "fatigue_actions": {
                "value": 3441040,
                "rank": 161
            },
            "total_event_score": {
                "value": 514293,
                "rank": 145
            }
        },
        "quests": {
            "total": {
                "value": 1470,
                "rank": 42
            },
            "battle": {
                "value": 1461
            },
            "harvest": {
                "value": 9
            },
            "profession": {
                "value": 0
            }
        },
        "stats": {
            "base": {
                "value": 170432,
                "rank": 89
            },
            "total": {
                "value": 265684,
                "rank": 85
            }
        },
        "skills": {
            "counter_attack": {
                "value": 132.96,
                "rank": 73
            },
            "healing": {
                "value": 133.11,
                "rank": 72
            },
            "unarmed_combat": {
                "value": 2.2,
                "rank": 625
            },
            "melee_weapons": {
                "value": 0.2,
                "rank": 6036
            },
            "ranged_weapons": {
                "value": 132.78,
                "rank": 10
            },
            "magical_weapons": {
                "value": 2.51,
                "rank": 881
            },
            "evasion": {
                "value": 131.48,
                "rank": 76
            }
        },
        "training": {
            "base_damage": {
                "trains": 500,
                "value": 193199,
                "rank": 64
            },
            "base_armor": {
                "trains": 550,
                "value": 30525,
                "rank": 67
            },
            "multistrike_chance": {
                "trains": 2500,
                "value": "125.00%",
                "rank": 78
            },
            "critical_hit_chance": {
                "trains": 2350,
                "value": "188.00%",
                "rank": 109
            },
            "critical_hit_damage": {
                "trains": 1000,
                "value": "100.00%",
                "rank": 226
            },
            "toughness": {
                "trains": 2500,
                "value": "50.00%",
                "rank": 34
            },
            "counter_attack_damage": {
                "trains": 1800,
                "value": "36.00%",
                "rank": 25
            },
            "healing_boost": {
                "trains": 2200,
                "value": "22.00%",
                "rank": 28
            },
            "fishing_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 3087
            },
            "woodcutting_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 2830
            },
            "mining_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 2991
            },
            "stonecutting_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 2542
            },
            "crafting_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 1785
            },
            "carving_boost": {
                "trains": 1,
                "value": "0.08%",
                "rank": 1312
            }
        },
        "clan": {
            "id": 17, // will be null if the user is not in clan
            "name": "Heavy Metal Unicorns" // will be null if the user is not in clan
        }
    }
]
```
