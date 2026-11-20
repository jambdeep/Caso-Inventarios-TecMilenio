# Sitio completo · Temas 1 al 6 · Prueba local

Este ZIP contiene las 23 piezas del sitio compartido anteriormente para los temas 1–5, más las cuatro estaciones nuevas del tema 6. Incluye los archivos Excel y los recursos HTML, CSS y JavaScript.

## Ajustes finales de esta versión

- Estación 1: líneas de conexión entre nodos de azar y resultados.
- Estación 3: indicación explícita de que la hipótesis del estudiante no altera los cálculos.
- Estación 4: barras de mayor altura y mejor legibilidad en la vista previa de diapositiva.
- Se conserva la navegación completa y el acceso al tema 6 desde la portada.

## Instalación local

1. Descomprime el ZIP en **una carpeta nueva**, sin mezclar archivos con versiones anteriores.
2. Abre esa carpeta desde VS Code (`Archivo > Abrir carpeta`).
3. Abre **`index.html`** mediante Live Server o Live Preview. No abras el archivo dentro del ZIP.
4. En la portada verás los accesos a Tema 4, Tema 5 y **Tema 6 · Decisiones cuantitativas**.
5. Entra al tema 6 y continúa por los enlaces al final de cada estación.

## Recorrido de control

| Sección | Prueba | Resultado esperado |
|---|---|---|
| Portada | Pulsar Tema 6 | Abre `caso_t6_arbol.html` |
| Estación 1 | Revelar escenario 25/50/25 | VE £183.13, £206.25 y £185.00 |
| Estación 1 | Pulsar Continuar | Abre sensibilidad |
| Estación 2 | Elegir hipótesis y revelar | Gráfico de tres políticas y cruce cerca de 40.74% |
| Estación 2 | Pulsar Continuar | Abre multicriterio |
| Estación 3 | Seleccionar hipótesis y calcular | Aparecen puntuaciones y se habilita el TXT |
| Estación 3 | Cambiar un peso, suma distinta de 100% | Botón de cálculo queda inhabilitado |
| Estación 3 | Restablecer y calcular; ir a estación 4 | La ficha abre sin perder la ruta |
| Estación 4 | Completar ficha y pulsar Actualizar | La diapositiva refleja las respuestas |
| Estación 4 | Importar resultados | Aparecen barras de las puntuaciones de estación 3 |
| Estación 4 | Descargar gráfica | Obtienes un archivo SVG insertable en PowerPoint |

## Importante sobre importación entre estaciones 3 y 4

Completa el cálculo en estación 3 y usa el enlace a estación 4 **en la misma pestaña y origen de Live Server/Live Preview**. La transferencia usa `sessionStorage` de tu navegador: no envía datos a ningún servidor y no es un mecanismo de entrega al profesor.

## Datos del tema 6

Escenarios didácticos: D=200/300/450, probabilidades 25/50/25. Costos didácticos: precio £1.65, costo £0.85, recuperación £0.30. No confundir estos escenarios con las observaciones de ventas reales de UCI Online Retail.

## Publicación en GitHub Pages

**Haz la publicación únicamente después de validar el paquete local.** Una vez comprobado, copia el contenido de esta carpeta a la raíz de tu repositorio existente, revisa los archivos modificados en VS Code y realiza commit y push. No es necesario crear una segunda carpeta anidada dentro del repositorio.
