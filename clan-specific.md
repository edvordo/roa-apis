Endpoint: `https://(www|beta).avabur.com/api/clans/{clan_id}`

Shows infor for a specific clan, denoted by the clan `id`.

Has a query parameter *?members=true* that includes members of the clans.

Example response

```json
[
    {
        "id": 17,
        "name": "Heavy Metal Unicorns",
        "description": "No Unicorn Left Behind!",
        "level": 78,
        "level_percent": 97.90512579265763,
        "experience": 3803994146,
        "level_cost": 3885388140,
        "buildings": 63,
        "maxbuildings": 78,
        "members": 21,
        "maxmembers": 22,
        "exptax": 10,
        "goldtax": 0,
        "restax": 5,
        "droptax": 0,
        "member_list": [
            {
                "username": "Reltorakii",
                "fame": 39223,
                "levels": {
                    "house": {
                        "level": 35,
                        "rank": 66
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
                        "value": 11971614,
                        "rank": 23
                    },
                    "deaths": {
                        "value": 145904,
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
                        "value": 225355418798,
                        "rank": 78
                    },
                    "gold_looted": {
                        "value": 333850970925,
                        "rank": 64
                    },
                    "fatigue_actions": {
                        "value": 3441081,
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
                        "value": 170451,
                        "rank": 89
                    },
                    "total": {
                        "value": 265711,
                        "rank": 85
                    }
                },
                "skills": {
                    "counter_attack": {
                        "value": 132.97,
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
                        "value": 131.5,
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
                }
            },
            {
                "username": "Zintaus",
                "fame": 42319,
                "levels": {
                    "house": {
                        "level": 35,
                        "rank": 83
                    },
                    "character": {
                        "level": 90,
                        "rank": 758
                    },
                    "fishing": {
                        "level": 950,
                        "rank": 41
                    },
                    "woodcutting": {
                        "level": 950,
                        "rank": 47
                    },
                    "mining": {
                        "level": 950,
                        "rank": 43
                    },
                    "stonecutting": {
                        "level": 950,
                        "rank": 51
                    },
                    "crafting": {
                        "level": 150,
                        "rank": 99
                    },
                    "carving": {
                        "level": 111,
                        "rank": 66
                    }
                },
                "battle": {
                    "kills": {
                        "value": 2055596,
                        "rank": 681
                    },
                    "deaths": {
                        "value": 8022,
                        "rank": 1475
                    }
                },
                "harvests": {
                    "harvests": {
                        "value": 7783822,
                        "rank": 11
                    },
                    "resources": {
                        "value": 1191480578.6652222,
                        "rank": 68
                    }
                },
                "profession": {
                    "crafts": {
                        "value": 568708,
                        "rank": 167
                    },
                    "carves": {
                        "value": 302850,
                        "rank": 111
                    }
                },
                "misc": {
                    "event_actions": {
                        "value": 308628,
                        "rank": 116
                    },
                    "experience_gained": {
                        "value": 23611848664,
                        "rank": 436
                    },
                    "gold_looted": {
                        "value": 37337708659,
                        "rank": 356
                    },
                    "fatigue_actions": {
                        "value": 2903906,
                        "rank": 281
                    },
                    "total_event_score": {
                        "value": 490403,
                        "rank": 163
                    }
                },
                "quests": {
                    "total": {
                        "value": 1356,
                        "rank": 71
                    },
                    "battle": {
                        "value": 257
                    },
                    "harvest": {
                        "value": 1046
                    },
                    "profession": {
                        "value": 53
                    }
                },
                "stats": {
                    "base": {
                        "value": 125993,
                        "rank": 178
                    },
                    "total": {
                        "value": 165855,
                        "rank": 200
                    }
                },
                "skills": {
                    "counter_attack": {
                        "value": 57.35,
                        "rank": 423
                    },
                    "healing": {
                        "value": 56.52,
                        "rank": 428
                    },
                    "unarmed_combat": {
                        "value": 2.37,
                        "rank": 581
                    },
                    "melee_weapons": {
                        "value": 7.67,
                        "rank": 1485
                    },
                    "ranged_weapons": {
                        "value": 55.94,
                        "rank": 74
                    },
                    "magical_weapons": {
                        "value": 1.22,
                        "rank": 1346
                    },
                    "evasion": {
                        "value": 56.07,
                        "rank": 432
                    }
                },
                "training": {
                    "base_damage": {
                        "trains": 200,
                        "value": 34224,
                        "rank": 336
                    },
                    "base_armor": {
                        "trains": 200,
                        "value": 4100,
                        "rank": 315
                    },
                    "multistrike_chance": {
                        "trains": 2000,
                        "value": "100.00%",
                        "rank": 109
                    },
                    "critical_hit_chance": {
                        "trains": 1250,
                        "value": "100.00%",
                        "rank": 208
                    },
                    "critical_hit_damage": {
                        "trains": 1000,
                        "value": "100.00%",
                        "rank": 226
                    },
                    "toughness": {
                        "trains": 400,
                        "value": "8.00%",
                        "rank": 339
                    },
                    "counter_attack_damage": {
                        "trains": 400,
                        "value": "8.00%",
                        "rank": 186
                    },
                    "healing_boost": {
                        "trains": 200,
                        "value": "2.00%",
                        "rank": 401
                    },
                    "fishing_boost": {
                        "trains": 2500,
                        "value": "200.00%",
                        "rank": 19
                    },
                    "woodcutting_boost": {
                        "trains": 2500,
                        "value": "200.00%",
                        "rank": 16
                    },
                    "mining_boost": {
                        "trains": 2500,
                        "value": "200.00%",
                        "rank": 16
                    },
                    "stonecutting_boost": {
                        "trains": 2500,
                        "value": "200.00%",
                        "rank": 16
                    },
                    "crafting_boost": {
                        "trains": 1250,
                        "value": "100.00%",
                        "rank": 113
                    },
                    "carving_boost": {
                        "trains": 1250,
                        "value": "100.00%",
                        "rank": 47
                    }
                }
            },
            ...
        ]
    }
]
```
