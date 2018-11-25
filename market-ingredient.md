Endpoint: `https://(www|beta).avabur.com/api/market/ingredient`

Lists up to 10 market entries for each of games ingredients:

`Aberration Mind Source`, `Animal Eye`, `Animal Tongue`, `Animal Tooth`, `Animal Wing`,

`Beast Fur`, `Beast Limb`, `Beast Tooth`, `Beast Wing`, `Bird Nest`, `Bone Shard`,

`Chunk of Coal`, `Chunk of Graphite`, `Construct Power`, `Copper Ore`, `Crafting Material`,

`Crystal`, `Dragon Eye`, `Dragon Scale`, `Dragon Tail`, `Ectoplasmic Residue`, `Elemental Energy`,

`Fish Fin`, `Food`, `Gem Fragment`, `Golden Apple`, `Honeycomb`, `Humanoid Bone`, `Humanoid Flesh`,

`Humanoid Limb`, `Iron`, `Lucky Coin`, `Magical Stone`, `Octopus Ink`, `Ooze Gel`, `Plant Branch`,

`Plant Leaf`, `Plant Root`, `Plant Vine`, `Platinum`, `Protection Stone`, `Rainbow Shard`,

`Rune Stone`, `Serpent Eye`, `Serpent Tail`, `Serpent Tongue`, `Shadow Stone`, `Squid Tentacle`,

`Stone`, `Turtle Shell`, `Vermin Eye`, `Vermin Tooth`, `Vial of Dust`, `Wood`, `Yellow Pollen`

**In case a currency would not have any listing on the market, it wil NOT be present in the response**

Example response

```json
{
    "Aberration Mind Source": [
        {
            "price": 347999,
            "amount": 1,
            "seller": "hohmono"
        },
        {
            "price": 348000,
            "amount": 57,
            "seller": "sexysquid"
        },
        {
            "price": 349000,
            "amount": 755,
            "seller": "DragonKlaw"
        },
        {
            "price": 350000,
            "amount": 24,
            "seller": "ttypomastre"
        },
        {
            "price": 373000,
            "amount": 49,
            "seller": "ScoobySnax"
        },
        {
            "price": 375000,
            "amount": 4,
            "seller": "Garthok"
        },
        {
            "price": 399999,
            "amount": 31,
            "seller": "tubbins"
        },
        {
            "price": 400000,
            "amount": 33,
            "seller": "redegl"
        },
        {
            "price": 550000,
            "amount": 41,
            "seller": "LawofJohn"
        },
        {
            "price": 599999,
            "amount": 17,
            "seller": "Ryuutsuu"
        }
    ],
    "Animal Eye": [
        {
            "price": 699999,
            "amount": 9,
            "seller": "hohmono"
        },
        {
            "price": 700000,
            "amount": 9,
            "seller": "DamBuster"
        },
        {
            "price": 700000,
            "amount": 41,
            "seller": "legenddairy"
        },
        {
            "price": 777777,
            "amount": 1,
            "seller": "sinexus"
        },
        {
            "price": 888888,
            "amount": 12,
            "seller": "PeteBull"
        },
        {
            "price": 999999,
            "amount": 168,
            "seller": "Barqs"
        },
        {
            "price": 1000000,
            "amount": 2,
            "seller": "Raudacious"
        },
        {
            "price": 1100000,
            "amount": 4,
            "seller": "ttypomastre"
        },
        {
            "price": 1230000,
            "amount": 78,
            "seller": "Fukuyama"
        },
        {
            "price": 1250000,
            "amount": 2,
            "seller": "Grafor"
        }
    ],
    "Animal Tongue": [
        {
            "price": 324998,
            "amount": 103,
            "seller": "sexysquid"
        },
        {
            "price": 324999,
            "amount": 5,
            "seller": "hohmono"
        },
        {
            "price": 325000,
            "amount": 66,
            "seller": "tubbins"
        },
        {
            "price": 325000,
            "amount": 2,
            "seller": "Bloopy"
        },
        {
            "price": 325000,
            "amount": 6,
            "seller": "DamBuster"
        },
        {
            "price": 388887,
            "amount": 2,
            "seller": "sinexus"
        },
        {
            "price": 388888,
            "amount": 12,
            "seller": "PeteBull"
        },
        {
            "price": 414999,
            "amount": 15,
            "seller": "DragonKlaw"
        },
        {
            "price": 415000,
            "amount": 4,
            "seller": "ttypomastre"
        },
        {
            "price": 439000,
            "amount": 29,
            "seller": "Ruhtarded"
        }
    ],
    ...
}
```
