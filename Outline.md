2.7 Camera
- βαλε camera 2d στον παιχτη
- φτιαχνουμε ενα νεο scene για τα tiles
  - root node θα ειναι area2d (εξηγησε το λιγο)
  - ενα polygon collision shape
  - ενα polygon texture (tile.png)
  - φτιαξε τα uvs και βαλε το texture να κανει repeat
  - φτιαξε ενα level με το polygon
- βαλε το level στο main scene μας

2.8 Signals
- Φτιαχνουμε ενα νεο script στο root node του main level
- Κανουμε connect το body exited signal του area 2d maze στο level script
- Μολις βγει ο παιχτης κανε reload το level (get_tree().reload_current_scece()). εξηγησε λιγο τι κανει αυτο
- κανε parallax το background (canvas layer)
- βαλε start και end labels