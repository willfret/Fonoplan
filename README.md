# FonoPlan

Aplicación web autónoma para planificación, evaluación inicial, registro de sesiones e informes de avance fonoaudiológico.

## Publicar con GitHub Pages

1. Cree un repositorio nuevo en GitHub.
2. Suba `index.html`, `.nojekyll` y este `README.md` a la rama `main`.
3. En GitHub abra **Settings > Pages**.
4. En **Build and deployment**, seleccione **Deploy from a branch**.
5. Seleccione la rama `main`, carpeta `/ (root)` y presione **Save**.
6. GitHub mostrará la dirección pública cuando finalice la publicación.

## Datos y privacidad

Los datos se guardan con `localStorage` en el navegador y dispositivo donde se usa la página. Publicar el programa no publica las fichas ni registros ingresados. Los datos no se sincronizan entre equipos; utilice **Crear respaldo** para exportarlos y **Importar respaldo** para recuperarlos en otro navegador.

La aplicación organiza información ingresada por un profesional y no genera diagnósticos clínicos automáticos.
