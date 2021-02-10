# ExMon

**Learning elixir with this game where the player against the computer with 3 movements available, 2 attack and 1 healing, whoever reaches 0 health first loses**

## Installation
Clone the rep and install the dependencies.

```sh
$ cd ex_mon
$ mix deps.get
```
### Running
  Start the server, create the player, start the game, and you can choose what move to play, the game ends when the player or the computer reachs 0 life.
```sh
$ iex -S mix run
iex(1)>playername = ExMon.create_player("Jogador 1", :voadora, :carrinho, :canadeacucar)
iex(2)>ExMon.start_game(playername)
iex(3)>ExMon.make_move(:voadora)

```

