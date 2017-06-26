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
      positionsOrderVals: [
        1: 1,
        2: 0.5,
        3: 0,
        4: 0,
        5: 0.333,
        6: 0,
        7: 0,
        8: 0,
        9: 0,
      ]
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
