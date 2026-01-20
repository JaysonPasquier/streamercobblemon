# StreamerCobblemon Mod

Mod curseforge pour Minecraft 1.21.1 qui exporte vos données Cobblemon (équipe, boîtes PC, Pokédex) vers une base de données cloud accessible via API.

## Installation

### Prérequis
- Minecraft 1.21.1
- Fabric Loader 0.16.9+
- Mod Cobblemon 1.7.1+

### Étapes

1. **Téléchargez** `streamercobblemon-1.0.0.jar` depuis les releases
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
{
    "id": "ac05ab2a-0545-4e7c-bb28-a1d703b73fba",
    "username": "scorpio74890",
    "party": [
      {
        "form": "Normal",
        "level": 28,
        "shiny": false,
        "species": "Krabby",
        "dexNumber": 98
      },
      {
        "form": "Normal",
        "level": 1,
        "shiny": true,
        "species": "Mewtwo",
        "dexNumber": 150
      },
      {
        "form": "Normal",
        "level": 1,
        "shiny": true,
        "species": "Mewtwo",
        "dexNumber": 150
      },
      {
        "form": "Normal",
        "level": 1,
        "shiny": true,
        "species": "Mewtwo",
        "dexNumber": 150
      },
      {
        "form": "Normal",
        "level": 1,
        "shiny": true,
        "species": "Mewtwo",
        "dexNumber": 150
      },
      {
        "form": "Normal",
        "level": 1,
        "shiny": true,
        "species": "Mewtwo",
        "dexNumber": 150
      }
    ],
    "boxes": [
      {
        "pokemon": [
          {
            "form": "Normal",
            "level": 1,
            "shiny": true,
            "species": "Mewtwo",
            "dexNumber": 150
          },
          {
            "form": "Normal",
            "level": 1,
            "shiny": false,
            "species": "Pikachu",
            "dexNumber": 25
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
        "genders": "[MALE]",
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
        "caught": false,
        "genders": "[MALE]",
        "species": "cobblemon:wingull",
        "dexNumber": 278,
        "knowledge": "ENCOUNTERED",
        "speciesName": "wingull"
      },
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
      }
    ],
    "created_at": "2026-01-20T00:49:00.519148+00:00",
    "updated_at": "2026-01-20T02:30:39.585794+00:00",
    "last_sync": "2026-01-20T00:49:00.519148+00:00"
  }
```

## Sécurité

- ✅ La clé API (anon key) permet SEULEMENT de **lire** les données
- ❌ Impossible de modifier ou supprimer les données avec cette clé
- 🔒 Seul le mod peut écrire dans la base de données

## Licence

MIT License
