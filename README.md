# Game
Importante:
Cada vez que se asigna una casilla, valida toda la matriz para saber si alguien ya ganó o si no hay otros posibles movimientos.
Se envía GAME_OVER, en ambos casos: si ganó envía el char de quien ganó (x / o), o si ya no hay más casillas disponibles envía GAME_OVER con el char vacío.
Se procesa así: char, int, int
