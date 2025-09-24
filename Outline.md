2.6 Input παίχτη
- Εξηγησε τι ειναι input map
- Εξηγησε τι ειναι ενα action
- Δειξε πως φτιαχνουμε actions και φτιαξε actions
  - move_right
  - move_left
  - move_up
  - move_down
- Κανε τον παιχτη να κινηθει με apply force στο physics process
- Εξηγησε variable scope
- Βαλε μια global μεταβλητη για να ελεγχει ταχυτητα (οχι ακομα export)
- Δειξε πως κανουμε return απο function

2.7 Camera
- βαλε camera 2d στον παιχτη
- βαλε damping στο rigidbody = 3 (optional: εξηγησε το λιγο)
- βαλε ταχυτητα στον παιχτη = 300
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