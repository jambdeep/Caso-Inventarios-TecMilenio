# La decisión de las 300 unidades — instrucciones de publicación

Sitio interactivo para 120 minutos de clase. HTML/CSS/JS estático y un libro de Excel.

## Publicar en GitHub Pages (sin comandos)

1. Abre https://github.com/new e inicia sesión.
2. Crea un repositorio, por ejemplo `caso-inventarios-tecmilenio`, con visibilidad **Public**.
3. En la pestaña **Code**, selecciona **Add file → Upload files**.
4. **Extrae este ZIP antes de subirlo.** Arrastra los archivos *dentro* del ZIP, NO el ZIP. Asegúrate de que `index.html` quede en la raíz (no dentro de una carpeta).
5. Pulsa **Commit changes**.
6. En **Settings → Pages → Build and deployment**, elige **Deploy from a branch** y **main / (root)**; guarda.
7. Abre la URL que GitHub muestre en Pages, habitualmente `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO/`.
8. Prueba Inicio → Estación 1 → Estación 2 → Estación 3 → Sala de decisiones → Glosario y el enlace del Excel.

## Importante

- Se publica en internet con acceso público. No subas respuestas ni archivos con información personal de estudiantes.
- Las respuestas de los formularios HTML se guardan en el navegador local y/o se descargan manualmente. **No llegan al profesor por sí solas.** Para la primera clase, solicítalas por Teams.
- El libro Excel debe abrirse en la aplicación de escritorio para comprobar las fórmulas y recalcular las simulaciones. La versión web o móvil puede comportarse distinto.
- La descarga del Excel está ligada al archivo en la raíz del repositorio.
- Algunos navegadores de tablets impiden descargas/copias; prioriza respuestas en Teams si sucede.
- El sitio funciona sin Google Sites. Si quieres, después puedes enlazarlo o incrustar su URL allí.

## Contenido

- `index.html`: inicio y decisión inicial
- `caso_inventarios_estacion1.html`: estadística descriptiva
- `caso_inventarios_estacion2.html`: modelo determinístico
- `caso_inventarios_estacion3.html`: Monte Carlo
- `caso_inventarios_sala_decisiones.html`: defensa y síntesis
- `caso_inventarios_glosario.html`: glosario
- `Caso_Interactivo_Inventarios_Temas_1_2_3.xlsx`: libro didáctico

## Fuente y licencia de datos

Chen, D. (2015). *Online Retail* [Data set]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33. Datos bajo licencia Creative Commons Attribution 4.0 (CC BY 4.0). La adaptación y los supuestos del caso son educativos.
