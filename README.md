# Cubito vs Esferas

Este es un juego simple implementado utilizando la biblioteca Pygame. El juego se llama "Cubito vs Esferas". Aquí hay una descripción del código:

## Descripción del código

- Importa los módulos necesarios: `pygame` y `random`.
- Inicializa Pygame con `pygame.init()`.
- Define los colores `WHITE` y `BLACK` utilizando valores RGB.
- Establece las dimensiones de la pantalla con `SCREEN_WIDTH` y `SCREEN_HEIGHT`.
- Crea la ventana del juego utilizando `pygame.display.set_mode()` y establece el título de la ventana.
- Define la clase `Player`, que representa el personaje del jugador. Hereda de la clase `pygame.sprite.Sprite`. El jugador es un cubo blanco que puede moverse horizontal y verticalmente. También tiene un método `shoot()` para crear proyectiles.
- Define la clase `Enemy`, que representa los objetos enemigos. También hereda de `pygame.sprite.Sprite`. Los enemigos son esferas blancas que se mueven verticalmente en la pantalla.
- Define la clase `Bullet`, que representa los proyectiles disparados por el jugador. También hereda de `pygame.sprite.Sprite`. Las balas son círculos blancos que se mueven verticalmente.
- Crea grupos de sprites para todos los sprites, enemigos y balas.
- Crea una instancia del jugador y agrégala al grupo de sprites.
- Crea múltiples instancias de enemigos y agrégalas a los grupos de sprites.
- Crea un objeto `Clock` para controlar la velocidad de fotogramas del juego.
- Entra en el bucle principal del juego (`while running`) para manejar eventos y actualizar el estado del juego.
- Procesa eventos, como salir del juego o mover al jugador.
- Actualiza todos los sprites en los grupos de sprites.
- Comprueba las colisiones entre el jugador y los enemigos. Si hay una colisión, finaliza el juego.
- Comprueba las colisiones entre los enemigos y las balas. Si hay una colisión, elimina al enemigo y crea uno nuevo.
- Dibuja los sprites en la pantalla y actualiza la visualización.
- Finaliza Pygame cuando el bucle del juego termine.

## Cómo ejecutar el juego

Para ejecutar este código, asegúrate de tener Pygame instalado y ejecútalo utilizando un intérprete de Python. Se abrirá la ventana del juego y podrás controlar al jugador usando las teclas de flecha. Presiona la barra espaciadora para disparar balas. Evita las colisiones con las esferas enemigas e intenta derribarlas. El juego terminará si el jugador colisiona con una esfera enemiga.

## Atribuciones

- Este juego fue creado utilizando la biblioteca Pygame (https://www.pygame.org/).


