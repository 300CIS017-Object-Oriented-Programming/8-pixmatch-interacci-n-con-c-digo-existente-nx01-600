## Requisitos Funcionales y Criterios de Aceptación
### 1. Configuración de Nivel de Dificultad
**Requisito:** El sistema debe permitir a los jugadores seleccionar el nivel de dificultad antes de comenzar el juego.

**Criterios de Aceptación:**
- Opciones de dificultad fácil, medio y difícil disponibles para selección.
- La configuración de dificultad debe influir en la mecánica del juego, como la frecuencia de regeneración de imágenes y la puntuación.
- Tiempos de regeneración específicos:
  - Fácil: cada 8 segundos.
  - Medio: cada 6 segundos.
  - Difícil: cada 5 segundos.


2. **Interfaz de Usuario Responsiva**
   
   **Requisito:** La interfaz de usuario debe ser sensible y adaptarse a diferentes tamaños de pantalla y dispositivos.

   **Criterios de Aceptación:**
   - La interfaz de usuario debe ser legible y funcional en dispositivos de diferentes tamaños, como teléfonos móviles, tablets y computadoras de escritorio.
   - Los elementos de la interfaz deben reorganizarse automáticamente para adaptarse al tamaño de la pantalla del dispositivo.

3. **Gestión de Puntuación y Temporizador**
   
   **Requisito:** El sistema debe gestionar la puntuación del jugador y un temporizador para limitar el tiempo de juego.

   **Criterios de Aceptación:**
   - La puntuación del jugador debe actualizarse en tiempo real según su rendimiento durante el juego.
   - El temporizador debe comenzar a contar tan pronto como se inicie el juego y reducir la puntuación del jugador a intervalos regulares.
   - El temporizador debe detenerse cuando se complete el juego o cuando el jugador abandone.

4. **Personalización del Jugador**
   
   **Requisito:** El sistema debe permitir al jugador ingresar su nombre y país antes de comenzar un nuevo juego.

   **Criterios de Aceptación:**
   - Debe haber campos de texto disponibles para que el jugador ingrese su nombre y país antes de comenzar el juego.
   - La información del jugador ingresada debe mostrarse en la interfaz durante el juego, posiblemente en la barra lateral.

5. **Finalización y Registro del Juego**
   
   **Requisito:** El sistema debe detectar cuándo se ha completado el juego y registrar la puntuación del jugador.

   **Criterios de Aceptación:**
   - Se debe verificar si todas las celdas del tablero han sido seleccionadas por el jugador.
   - La puntuación final del jugador debe mostrarse en la pantalla de finalización del juego.
   - La puntuación del jugador y los detalles del juego (como nombre y país) deben registrarse en un marcador al finalizar el juego.
