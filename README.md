# ex_mon
A simple game developed during an Elixir course. 
The game is a simple batle between player (you) and the computer.
Basicaly we have 3 moves (:kick, :punch and :heal),
You can choose one of them to use each round.

# running
With all Elixir environment installed, go to project folder and run $iex -S mix

# Methods
The ExMon.create_player/1 is used to create your player, ex:
me = ExMon.create_player("Jef", :special_kick, :uppercut, :meditate)

Then you can use ExMon.start_game/ to start the game with created player, ex:
ExMon.start_game(me)

Finally you can make your move and wait the computer play, use method ExMon.make_move/1, ex:
ExMon.make_move(:uppercut)

You will se a message about the game status, just keep making moves until someone reach 0 points of life.

Enjoy =)

