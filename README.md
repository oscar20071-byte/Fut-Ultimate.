# Fut-Ultimate

Simulador de fútbol independiente con interfaz original, adaptable a móviles y escritorio.

## Funciones
- Panel principal con resumen de clubes, jugadores, partidos y goles.
- Crear, renombrar y eliminar clubes.
- Crear, editar y eliminar jugadores.
- Media obligatoria de 1 a 99, posición y dorsal opcional.
- Importación de equipos y plantillas en bloque.
- Tabla de liga con PJ, victorias, empates, derrotas, GF, GC, DG y puntos.
- Calendario todos contra todos a una vuelta y simulación de jornadas.
- Resultados históricos de la temporada.
- Estadísticas simuladas de goles, asistencias y apariciones.
- Clasificaciones individuales: Bota de Oro, asistentes y destacados.
- Exportar e importar copias JSON para trasladar o respaldar partidas.
- Temporada editable y reinicio de resultados sin borrar clubes ni plantillas.
- PWA instalable y caché para carga básica sin conexión.

## Importar una plantilla
Primera línea: nombre del club. Luego una línea por jugador con el formato:

```text
Real Madrid
POR: Alex Pérez #1 | 82
DFC: Luis Díaz #4 | 79
DC: Mario Ruiz #9 | 88
```

La media es opcional en la importación y se establece en 70 si se omite. Posiciones admitidas: POR, DFC, LD, LI, MCD, MC, MCO, ED, EI y DC.

## Publicar
Activa GitHub Pages en **Settings → Pages → Deploy from a branch → main / root**.

## Datos y sincronización
Los datos se guardan localmente en el navegador. No hay todavía cuentas ni sincronización automática entre dispositivos. Para mover el progreso entre equipos, usa **Datos → Exportar copia** y luego **Importar copia** en el otro dispositivo.
