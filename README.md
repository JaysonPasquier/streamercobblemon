# StreamerCobblemon Mod

Mod curseforge pour Minecraft 1.21.1 qui exporte vos données Cobblemon (équipe, boîtes PC, Pokédex) vers une base de données cloud accessible via API.

## Installation

### Prérequis
- Minecraft 1.21.1
- Fabric Loader 0.16.9+
- Mod Cobblemon 1.7.1+

### Étapes

1. **Téléchargez** `streamercobblemon-1.1.0.jar `(https://github.com/JaysonPasquier/streamercobblemon/releases/download/1.0.0/streamercobblemon-1.1.0.jar)
2. **Copiez** le fichier dans votre dossier mods 
3. **Lancez** Minecraft avec curseforge
4. Vos données sont automatiquement synchronisées !

## API

### Accéder aux données

**URL de base :** `https://xfiucncvuawgdfexznwr.supabase.co/rest/v1/players`
**URL Player Spécifique :** `https://xfiucncvuawgdfexznwr.supabase.co/rest/v1/players?username=eq.PLAYERNAME`
**URL Exemple scorpio74890 :** `https://xfiucncvuawgdfexznwr.supabase.co/rest/v1/players?username=eq.scorpio74890`

**Clé API (anon key) :**
```
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InhmaXVjbmN2dWF3Z2RmZXh6bndyIiwicm9sZSI6ImFub24iLCJpYXQiOjE3Njg4NTQ2NTMsImV4cCI6MjA4NDQzMDY1M30.jEnjxTWAPYX9QPgQnqvOwN92kEcXMkXsLQSjX6phCCg
```
### Structure des données

```json
[
  {
    "id": "04b07f35-971d-4760-ad36-4f42577466da",
    "username": "scorpio74890",
    "party": [
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 2,
          "speed": 25,
          "attack": 23,
          "defence": 28,
          "special_attack": 30,
          "special_defence": 0
        },
        "form": "normal",
        "level": 29,
        "moves": [
          {
            "name": "stomp"
          },
          {
            "name": "bubblebeam"
          },
          {
            "name": "protect"
          },
          {
            "name": "mudshot"
          }
        ],
        "shiny": false,
        "gender": "MALE",
        "nature": "bold",
        "status": "healthy",
        "ability": "shellarmor",
        "species": "Krabby",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 98,
        "held_item": "minecraft:air",
        "current_hp": 56,
        "friendship": 54
      },
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 14,
          "speed": 12,
          "attack": 24,
          "defence": 18,
          "special_attack": 13,
          "special_defence": 18
        },
        "form": "normal",
        "level": 1,
        "moves": [
          {
            "name": "lifedew"
          },
          {
            "name": "psywave"
          },
          {
            "name": "laserfocus"
          },
          {
            "name": "mefirst"
          }
        ],
        "shiny": true,
        "gender": "GENDERLESS",
        "nature": "bashful",
        "status": "healthy",
        "ability": "pressure",
        "species": "Mewtwo",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 150,
        "held_item": "minecraft:air",
        "current_hp": 13,
        "friendship": 51
      },
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 15,
          "speed": 19,
          "attack": 2,
          "defence": 21,
          "special_attack": 31,
          "special_defence": 7
        },
        "form": "normal",
        "level": 1,
        "moves": [
          {
            "name": "lifedew"
          },
          {
            "name": "psywave"
          },
          {
            "name": "laserfocus"
          },
          {
            "name": "mefirst"
          }
        ],
        "shiny": true,
        "gender": "GENDERLESS",
        "nature": "quirky",
        "status": "healthy",
        "ability": "pressure",
        "species": "Mewtwo",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 150,
        "held_item": "minecraft:air",
        "current_hp": 13,
        "friendship": 51
      },
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 29,
          "speed": 26,
          "attack": 5,
          "defence": 12,
          "special_attack": 21,
          "special_defence": 21
        },
        "form": "normal",
        "level": 1,
        "moves": [
          {
            "name": "lifedew"
          },
          {
            "name": "psywave"
          },
          {
            "name": "laserfocus"
          },
          {
            "name": "mefirst"
          }
        ],
        "shiny": true,
        "gender": "GENDERLESS",
        "nature": "quiet",
        "status": "healthy",
        "ability": "pressure",
        "species": "Mewtwo",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 150,
        "held_item": "minecraft:air",
        "current_hp": 13,
        "friendship": 36
      },
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 11,
          "speed": 10,
          "attack": 1,
          "defence": 11,
          "special_attack": 21,
          "special_defence": 8
        },
        "form": "normal",
        "level": 1,
        "moves": [
          {
            "name": "lifedew"
          },
          {
            "name": "psywave"
          },
          {
            "name": "laserfocus"
          },
          {
            "name": "mefirst"
          }
        ],
        "shiny": true,
        "gender": "GENDERLESS",
        "nature": "bold",
        "status": "healthy",
        "ability": "pressure",
        "species": "Mewtwo",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 150,
        "held_item": "minecraft:air",
        "current_hp": 13,
        "friendship": 36
      },
      {
        "evs": {
          "hp": 0,
          "speed": 0,
          "attack": 0,
          "defence": 0,
          "special_attack": 0,
          "special_defence": 0
        },
        "ivs": {
          "hp": 17,
          "speed": 1,
          "attack": 11,
          "defence": 31,
          "special_attack": 26,
          "special_defence": 8
        },
        "form": "normal",
        "level": 1,
        "moves": [
          {
            "name": "lifedew"
          },
          {
            "name": "psywave"
          },
          {
            "name": "laserfocus"
          },
          {
            "name": "mefirst"
          }
        ],
        "shiny": true,
        "gender": "GENDERLESS",
        "nature": "quirky",
        "status": "healthy",
        "ability": "pressure",
        "species": "Mewtwo",
        "nickname": "",
        "pokeball": "cobblemon:master_ball",
        "dexNumber": 150,
        "held_item": "minecraft:air",
        "current_hp": 13,
        "friendship": 51
      }
    ],
    "boxes": [
      {
        "pokemon": [
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 10,
              "speed": 27,
              "attack": 21,
              "defence": 9,
              "special_attack": 14,
              "special_defence": 21
            },
            "form": "normal",
            "level": 1,
            "moves": [
              {
                "name": "lifedew"
              },
              {
                "name": "psywave"
              },
              {
                "name": "laserfocus"
              },
              {
                "name": "mefirst"
              }
            ],
            "shiny": true,
            "gender": "GENDERLESS",
            "nature": "mild",
            "status": "healthy",
            "ability": "pressure",
            "species": "Mewtwo",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 150,
            "held_item": "minecraft:air",
            "current_hp": 13,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 14,
              "speed": 23,
              "attack": 8,
              "defence": 27,
              "special_attack": 26,
              "special_defence": 18
            },
            "form": "normal",
            "level": 1,
            "moves": [
              {
                "name": "charm"
              },
              {
                "name": "nastyplot"
              },
              {
                "name": "sweetkiss"
              },
              {
                "name": "nuzzle"
              }
            ],
            "shiny": false,
            "gender": "FEMALE",
            "nature": "rash",
            "status": "healthy",
            "ability": "static",
            "species": "Pikachu",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 25,
            "held_item": "minecraft:air",
            "current_hp": 11,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 13,
              "speed": 3,
              "attack": 20,
              "defence": 23,
              "special_attack": 9,
              "special_defence": 20
            },
            "form": "normal",
            "level": 27,
            "moves": [
              {
                "name": "batonpass"
              },
              {
                "name": "cometpunch"
              },
              {
                "name": "roost"
              },
              {
                "name": "machpunch"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "bashful",
            "status": "healthy",
            "ability": "earlybird",
            "species": "Ledyba",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 165,
            "held_item": "minecraft:air",
            "current_hp": 62,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 3,
              "speed": 7,
              "attack": 20,
              "defence": 17,
              "special_attack": 8,
              "special_defence": 17
            },
            "form": "normal",
            "level": 4,
            "moves": [
              {
                "name": "watergun"
              },
              {
                "name": "growl"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "docile",
            "status": "healthy",
            "ability": "keeneye",
            "species": "Wingull",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 278,
            "held_item": "minecraft:air",
            "current_hp": 17,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 14,
              "speed": 16,
              "attack": 9,
              "defence": 12,
              "special_attack": 12,
              "special_defence": 24
            },
            "form": "normal",
            "level": 39,
            "moves": [
              {
                "name": "psychic"
              },
              {
                "name": "slackoff"
              },
              {
                "name": "surf"
              },
              {
                "name": "amnesia"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "docile",
            "status": "healthy",
            "ability": "owntempo",
            "species": "Slowbro",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 80,
            "held_item": "minecraft:air",
            "current_hp": 128,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 13,
              "speed": 29,
              "attack": 27,
              "defence": 22,
              "special_attack": 31,
              "special_defence": 16
            },
            "form": "normal",
            "level": 10,
            "moves": [
              {
                "name": "metalclaw"
              },
              {
                "name": "harden"
              },
              {
                "name": "watergun"
              },
              {
                "name": "leer"
              }
            ],
            "shiny": false,
            "gender": "FEMALE",
            "nature": "naive",
            "status": "healthy",
            "ability": "shellarmor",
            "species": "Krabby",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 98,
            "held_item": "minecraft:air",
            "current_hp": 27,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 7,
              "speed": 1,
              "attack": 5,
              "defence": 28,
              "special_attack": 7,
              "special_defence": 19
            },
            "form": "normal",
            "level": 33,
            "moves": [
              {
                "name": "flail"
              },
              {
                "name": "stomp"
              },
              {
                "name": "bubblebeam"
              },
              {
                "name": "protect"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "bold",
            "status": "healthy",
            "ability": "hypercutter",
            "species": "Kingler",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 99,
            "held_item": "minecraft:air",
            "current_hp": 81,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 12,
              "speed": 29,
              "attack": 28,
              "defence": 17,
              "special_attack": 2,
              "special_defence": 7
            },
            "form": "normal",
            "level": 10,
            "moves": [
              {
                "name": "yawn"
              },
              {
                "name": "watergun"
              },
              {
                "name": "growl"
              },
              {
                "name": "tackle"
              }
            ],
            "shiny": false,
            "gender": "FEMALE",
            "nature": "naive",
            "status": "healthy",
            "ability": "owntempo",
            "species": "Slowpoke",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 79,
            "held_item": "minecraft:air",
            "current_hp": 39,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 29,
              "speed": 26,
              "attack": 13,
              "defence": 10,
              "special_attack": 26,
              "special_defence": 7
            },
            "form": "normal",
            "level": 5,
            "moves": [
              {
                "name": "quickattack"
              },
              {
                "name": "watergun"
              },
              {
                "name": "growl"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "quiet",
            "status": "healthy",
            "ability": "keeneye",
            "species": "Wingull",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 278,
            "held_item": "minecraft:air",
            "current_hp": 20,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 8,
              "speed": 30,
              "attack": 2,
              "defence": 27,
              "special_attack": 22,
              "special_defence": 12
            },
            "form": "normal",
            "level": 13,
            "moves": [
              {
                "name": "bubblebeam"
              },
              {
                "name": "leer"
              },
              {
                "name": "rocksmash"
              },
              {
                "name": "visegrip"
              }
            ],
            "shiny": false,
            "gender": "FEMALE",
            "nature": "hardy",
            "status": "healthy",
            "ability": "hypercutter",
            "species": "Crabrawler",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 739,
            "held_item": "minecraft:air",
            "current_hp": 36,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 23,
              "speed": 17,
              "attack": 9,
              "defence": 16,
              "special_attack": 7,
              "special_defence": 26
            },
            "form": "normal",
            "level": 11,
            "moves": [
              {
                "name": "supersonic"
              },
              {
                "name": "quickattack"
              },
              {
                "name": "watergun"
              },
              {
                "name": "growl"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "docile",
            "status": "healthy",
            "ability": "keeneye",
            "species": "Wingull",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 278,
            "held_item": "minecraft:air",
            "current_hp": 32,
            "friendship": 51
          },
          {
            "evs": {
              "hp": 0,
              "speed": 0,
              "attack": 0,
              "defence": 0,
              "special_attack": 0,
              "special_defence": 0
            },
            "ivs": {
              "hp": 25,
              "speed": 15,
              "attack": 29,
              "defence": 13,
              "special_attack": 4,
              "special_defence": 0
            },
            "form": "normal",
            "level": 7,
            "moves": [
              {
                "name": "strugglebug"
              },
              {
                "name": "bugbite"
              },
              {
                "name": "gust"
              },
              {
                "name": "sweetscent"
              }
            ],
            "shiny": false,
            "gender": "MALE",
            "nature": "impish",
            "status": "healthy",
            "ability": "honeygather",
            "species": "Combee",
            "nickname": "",
            "pokeball": "cobblemon:master_ball",
            "dexNumber": 415,
            "held_item": "minecraft:air",
            "current_hp": 22,
            "friendship": 51
          }
        ],
        "boxNumber": 1
      }
    ],
    "pokedex": [
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[FEMALE]",
        "species": "cobblemon:pikachu",
        "dexNumber": 25,
        "knowledge": "CAUGHT",
        "speciesName": "pikachu"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE]",
        "species": "cobblemon:wingull",
        "dexNumber": 278,
        "knowledge": "CAUGHT",
        "speciesName": "wingull"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE]",
        "species": "cobblemon:slowbro",
        "dexNumber": 80,
        "knowledge": "CAUGHT",
        "speciesName": "slowbro"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE]",
        "species": "cobblemon:ledyba",
        "dexNumber": 165,
        "knowledge": "CAUGHT",
        "speciesName": "ledyba"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE]",
        "species": "cobblemon:kingler",
        "dexNumber": 99,
        "knowledge": "CAUGHT",
        "speciesName": "kingler"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[FEMALE]",
        "species": "cobblemon:crabrawler",
        "dexNumber": 739,
        "knowledge": "CAUGHT",
        "speciesName": "crabrawler"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[FEMALE]",
        "species": "cobblemon:slowpoke",
        "dexNumber": 79,
        "knowledge": "CAUGHT",
        "speciesName": "slowpoke"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE, FEMALE]",
        "species": "cobblemon:krabby",
        "dexNumber": 98,
        "knowledge": "CAUGHT",
        "speciesName": "krabby"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": true,
        "caught": true,
        "genders": "[GENDERLESS]",
        "species": "cobblemon:mewtwo",
        "dexNumber": 150,
        "knowledge": "CAUGHT",
        "speciesName": "mewtwo"
      },
      {
        "form": "normal",
        "seen": true,
        "shiny": false,
        "caught": true,
        "genders": "[MALE]",
        "species": "cobblemon:combee",
        "dexNumber": 415,
        "knowledge": "CAUGHT",
        "speciesName": "combee"
      }
    ],
    "created_at": "2026-01-20T18:13:26.658944+00:00",
    "updated_at": "2026-01-20T18:13:26.658944+00:00",
    "last_sync": "2026-01-20T18:13:26.658944+00:00"
  }
]
```

## Sécurité

- ✅ La clé API (anon key) permet SEULEMENT de **lire** les données
- ❌ Impossible de modifier ou supprimer les données avec cette clé
- 🔒 Seul le mod peut écrire dans la base de données

## Licence

MIT License
