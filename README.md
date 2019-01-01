# Land-Editor
a rather simple game were tiles change depending on what times are placed/edited next to them

C#

Rules (basic):
- Empty tiles can become any other type
- Any tile can change into a water tile
- Only tree tiles and dirt tiles can change into trees
- Only water tiles and dirt tiles can change into dirt

(Advanced):
- When a desert tile is placed, any nearby soil/grass tiles turn into desert
- Only dirt tiles can be changed into soil
- When a Grass tile is placed, any nearby soil tiles turn into Grass
- When a Beach tile is placed, any nearby fresh water tiles turn into salt water

- When a salt water tile is placed, any nearby fresh water tiles turn into salt water
- When a salt water tile is placed, any nearby dirt/oak tiles turn into beach
- When a fresh water tile is placed, any nearby salt water tiles turn into fresh water
- When a fresh water tile is placed, any nearby dirt tiles turn into grass
- When a fresh water tile is placed, any nearby Cacti tiles turn into desert

- A Cacti tile can only be changed from a desert or soil tile
- When a Cacti tile is placed, any nearby desert/Soil tiles turn into Cacti
- A Palm tile can only be changed from a beach or soil tile
- When a palm tile is placed, any nearby beach/Soil tiles turn into palm
- A Oak tile can only be changed from a Grass or soil tile
- When a Oak tile is placed, any nearby Grass/Soil tiles turn into oak
