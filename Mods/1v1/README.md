## Note

> The 1v1 map requires a [**modified Erbium fork**](https://github.com/gavbowersdomain/Erbium/tree/1v1-Map) to allow players to join in progress.
>
> Sometimes you cannot damage other players, to fix this just **leave and rejoin the server**.

---

## *New* Barrier Material Changer

### How to use

* Press the **Insert** key to cycle through different barrier materials.

<img src="barriertest.gif" width="700" height="400" controls></img>

> This feature is **client-sided**, so barrier changes will **not** be visible to other players.
---
## Arena Widget
Change playlist to ```L"/Game/Gav/Levels/GM_1v1/Playlist_Arena_DefaultSolo_Respawn.Playlist_Arena_DefaultSolo_Respawn";```

## Disable Fall Damage
Add this to DefaultGame.ini
```
[AssetHotfix]
+DataTable=/Game/Characters/Player/DataTables/CharacterAttributesPlayer;RowUpdate;PlayerLoadout_AthenaPlayer;FallingDamageTable;None
```
## Erbium Fork
[https://github.com/gavbowersdomain/Erbium/tree/1v1-Map](https://github.com/gavbowersdomain/Erbium/tree/1v1-Map)