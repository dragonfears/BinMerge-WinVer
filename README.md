-💾 RetroFuze
-Toolkit en PowerShell con GUI para gestionar colecciones de diferentes plataformas.
-Permite fusionar imágenes CUE/BIN, generar listas de reproducción .m3u, renombrar archivos con limpieza automática y ordenar respaldos para XStation.
________________________________________
✨ Características principales

- 📄 Fusión de imágenes CUE/BIN
-	Combina múltiples BIN en uno solo.
- Genera un nuevo .cue sincronizado.
-	Mueve los archivos originales a una carpeta segura.
-	🎵 Generación de playlists (.m3u)
-	Detecta automáticamente respaldos multi-disco.
-	Crea listas de reproducción listas para emuladores y ODEs.
-	🧼 Renombrado inteligente
-	Limpia títulos de etiquetas innecesarias (Beta, Demo, Hack, etc.).
-	Preserva y agrega la región del respaldo.
-	Estándar uniforme para tu librería.
-	📦 Organización para XStation
-	Ordena respaldos y discos en el formato correcto.
-	Soporta modo de simulación antes de aplicar cambios.
-	🛡️ Robustez y validaciones
-	Manejo de errores con logs claros (merge_errors.log).
-	Validación de archivos faltantes o dañados.
-	Progreso y estado en tiempo real.
________________________________________
🎶 Tracks soportados en la fusión
El script reconoce y soporta los siguientes tipos de tracks al fusionar BINs:
- Tipo de Track	Tamaño de bloque
- 🎵 AUDIO	2352 bytes
- 💿 MODE1/2352	2352 bytes
- 💿 MODE2/2352	2352 bytes
- 💿 CDI/2352	2352 bytes
- 💿 CDG	2448 bytes
- 💿 MODE1/2048	2048 bytes
- 💿 MODE2/2336	2336 bytes
- 💿 CDI/2336	2336 bytes
- ✅ Si se encuentra un tipo de track desconocido, se usa por defecto 2352 bytes y se genera una advertencia en el log.
________________________________________
🖥️ Requisitos
-	Windows 10/11
-	PowerShell 5.1 o superior
-	.NET Framework (para la interfaz gráfica)
________________________________________
🚀 Uso
1.	Abrir la aplicación
Ejecuta el archivo.exe.
2.	Seleccionar carpeta
Escoge el directorio donde están tus archivos .cue / .bin.
3.	Elegir acción
o	🔄 Fusionar CUE/BIN → Unifica respaldos múltiples en un solo archivo.
o	🎶 Crear playlist .m3u → Agrupa respaldos y genera listas de reproducción.
o	🧹 Renombrar/Organizar → Limpieza de nombres y estructura.
o	📂 Ordenar para XStation → Prepara tu SD con todo listo.
4.	Confirmar
La aplicación te pedirá confirmación antes de aplicar cambios.
________________________________________
📷 Captura

<img width="515" height="535" alt="retrofuze" src="https://github.com/user-attachments/assets/fce8bdbe-8012-4525-9899-40cd42718051" />

________________________________________
🏆 Beneficios
-	✅ Librería más limpia y profesional.
-	✅ Compatibilidad con emuladores y ODEs (XStation, DuckStation, RetroArch).
-	✅ Automatización: menos trabajo manual.
-	✅ Logs claros para depuración.
-	✅ Seguro: mantiene copia de originales.
________________________________________
📌 Autor
👨‍💻 Gerardo Bernal
- Si te sirve este proyecto, ¡dale una ⭐ en GitHub!
