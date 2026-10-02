# Task Manager Pro

Plantilla gratis: tareas, calculadora inteligente y notas con formato en una sola página. Todo se guarda automáticamente en el navegador, con backups, snapshots y papelera.

**Demo:** https://devlewiso.github.io/tasker-manager/

## Características

### Tareas
- Agrega tareas con prioridad (alta, normal, baja) y fecha de vencimiento; las vencidas se marcan en rojo.
- Marca como completada (con «Undo»). Las completadas no se pierden: quedan en la pestaña **Done** con la fecha.
- Doble clic para editar y arrastrar para reordenar.
- «Clear done» manda las completadas a la papelera, con «Undo».
- Anillo de progreso con el porcentaje completado.

### Calculadora
- Sin `eval`: un analizador propio, seguro, que acepta `+ − × ÷`, paréntesis, decimales y signo.
- **Porcentaje real:** `200 + 10%` = 220, `200 − 10%` = 180, `200 × 10%` = 20, `50%` = 0.5.
- Vista previa del resultado mientras escribes y uso con el teclado (Enter, Esc).
- Historial de las últimas 30 operaciones, con botones para reutilizar o copiar el resultado.
- Botón para convertir el resultado en una tarea.

### Notas
- Varias notas con título, en pestañas.
- Editor de texto enriquecido (Quill): títulos, negrita, listas, listas de verificación, enlaces, citas y código.
- Contador de palabras y caracteres; autoguardado al escribir.

## Tus datos no se borran

- **Autoguardado doble:** cada cambio se guarda en `localStorage` y en IndexedDB. Si una copia falta, se recupera de la otra.
- **Almacenamiento persistente:** se pide al navegador que no borre los datos para liberar espacio.
- **Papelera:** tareas y notas borradas se pueden restaurar. Para vaciarla hay que confirmar.
- **Snapshots automáticos:** se guardan los últimos 10: uno diario y uno antes de restaurar, importar o vaciar la papelera.
- **Backup:** descarga un `.json` con todo y restaúralo con **Merge** o **Replace**. Si no hay backup reciente, aparece un recordatorio.

Los datos solo se pierden si borras los datos de navegación del sitio, usas una ventana privada o cambias de navegador o equipo. Para eso está el backup.

## Uso

Abre `index.html` en el navegador o sírvelo localmente:

```bash
python3 -m http.server 8000
```

Atajo: `N` enfoca el campo de nueva tarea.

## Tecnologías

HTML, CSS y JavaScript en un solo archivo. Bootstrap 5, Bootstrap Icons y Quill 2 desde CDN.

## Licencia

MIT — plantilla gratuita de [Neural Code Lab](https://neuralcodelab.com).
