# baseball gamesheet tool # 

***data structure***
```
team = {
  teamId: 1,
  name: Mavericks,
  roster: [
    {
      playerId: 1,
      number: 0,
      name: 0,
      positions: [1, 2, 5]
    }
  ],
  games: [
    {
      gameId: 1,
      date: iso8601
      innings: [
        {
          inning: 1,
          1: playerId
          2: playerId
        }
      ]
    }
  ]
}
```
***functions:***
```
team.create()
team.read(teamId)
team.update(teamId)
team.delete(teamId)

player.create()
player.read(playerId)
player.update(playerId)
player.delete(playerId)

game.create()
game.read(gameId)
game.update(gameId)
game.delete(gameId)
```
