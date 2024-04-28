# HeartBeat

- API for getting information
- Syncs data between all Lamington instances connected to the same Redis server
- Use the information outside just your server (ie: Your website)

### Example Json Object:
```json
{
    "server": "server-01",
    "serverType": 1,
    "onlinePlayers": 0,
    "tps": 20.0,
    "mspt": 1.68,
    "startTime": 1714280347746,
    "lastHeartBeat": 1714280347746
}
```

### Server Types:
- Server types are an Enum and the value in redis is their id

```
    OTHER = 0
    LOBBY = 1
    SURVIVAL_ZONE = 2
    SURVIVAL_SPAWN = 3
    SKYBLOCK_ISLAND = 4
    SKYBLOCK_GENERIC = 5
```
