✅ Cambios agregados al comando /stats:

1. Separación de estadísticas en dos embeds:

    Separamos FPP y TPP en dos páginas (embeds) distintas:

   - 🟦 FPP (first-person): con estadísticas de solo-fpp, duo-fpp y squad-fpp.

   - 🟩 TPP (third-person): con estadísticas de solo, duo y squad.

2. Paginación con botones:

    Se añadieron botones interactivos para navegar entre las estadísticas:

   - ◀️ FPP – Muestra el embed de estadísticas FPP.

   - ▶️ TPP – Muestra el embed de estadísticas TPP.

3. Botón ⏹️ Cerrar:

    - Se añadió un botón ⏹️ Cerrar que borra el mensaje de estadísticas.

    - Solo el usuario que ejecutó el comando puede usar este botón.

4. Restricción de botones por usuario:

    - Si otra persona intenta usar los botones, recibe un mensaje: ❌ Solo tú puedes usar estos botones.

5. Auto deshabilitado después de 60 segundos:

    - Los botones se desactivan automáticamente después de 1 minuto si no se usan, para evitar que queden activos permanentemente.

6. Mejoras visuales con emojis personalizados:

    - Se agregaron íconos en los campos para distinguir las estadísticas fácilmente:

   🎮 Partidas
   🎯 Kills
   🏆 Wins
   ⚔️ K/D

✅ Cambios agregados al comando /compare

Soporte para TPP y FPP:

- Ahora se muestran estadísticas separadas para ambos modos (TPP y FPP).

- Se generan dos embeds distintos, uno para cada modo.

Paginación con botones:

- Se agregaron botones para navegar entre el embed de TPP y el de FPP.

- Botón de “⏹️ Cerrar” para eliminar el mensaje.

 Colores personalizados:

- El embed de TPP tiene color verde.

- El embed de FPP tiene color azul.

Campos estadísticos más completos:

- Se comparan kills, wins, K/D, partidas jugadas y top 10 para cada modo.

✅ Cambios agregados al comando /ranking

Estadísticas TPP y FPP:
Se obtienen y muestran estadísticas para ambos modos (TPP y FPP).
Color dinámico según promedio de kills:

El color del embed cambia según el promedio de kills de los jugadores en el ranking (ejemplo: rojo si kills bajas, dorado si altas).

Mejor presentación:

- Se muestran las estadísticas ordenadas (top 10).
- Se incluyen kills totales y kills por modo.

✅ Cambios agregados al comando /top

- Soporte para Squad FPP y Squad TPP:
- Obtuve y ordené el top 5 de jugadores por wins para modo squad FPP y modo squad TPP por separado.

- Embeds separados para cada modo:
- Creé dos embeds distintos: uno para el top de Squad FPP y otro para Squad TPP.

- Botones interactivos para paginar entre embeds:
- Añadí botones que permiten alternar entre la vista de FPP y TPP sin enviar múltiples mensajes.

- Botón "Cerrar":
- Permite al usuario eliminar el mensaje con el top para no dejar basura en el canal.

- Seguridad y tiempo de expiración:
- Solo el autor del comando puede usar los botones, y los botones se desactivan tras 2 minutos.

✅ Cambios agregados al comando /profile

- Separación de estadísticas FPP y TPP:
- En lugar de mostrar solo un modo (como solo FPP o solo un modo random), agregué paginación para que el usuario pueda ver su perfil en FPP y TPP por separado.

- Embeds paginados con botones:
- Dos embeds: uno con las estadísticas de FPP, otro con las de TPP.
- Botones para navegar entre ambos embeds y para cerrar el mensaje.

- Botón "Cerrar":
- Igual que en /top, para eliminar el mensaje.

- Manejo seguro del uso de botones:
- Solo el usuario que ejecutó el comando puede usar la paginación.

✅ Cambios agregados al comando /history

- Paginación para mostrar partidas recientes:
- Si el historial tiene varias partidas, se muestran en páginas con botones “Anterior” y “Siguiente”.

- Separación o filtro opcional por modo FPP o TPP (según implementaciones):
- Se puede modificar para mostrar partidas filtradas o separadas.

- Botón "Cerrar":
- Para eliminar el mensaje si el usuario desea cerrar la paginación.

- Control de interacciones:
- Solo el usuario que ejecutó el comando puede interactuar con los botones y hay un tiempo límite para la interacción.

 ✅ Nuevo comando /updates

 - Te permite ver en tiempo real las actualizaciones y cambios del bot.
