💾 RetroFuze
Toolkit en PowerShell con GUI para gestionar colecciones de diferentes plataformas.
Permite fusionar imágenes CUE/BIN, generar listas de reproducción .m3u, renombrar archivos con limpieza automática y ordenar respaldos para XStation.
________________________________________
✨ Características principales
•	📄 Fusión de imágenes CUE/BIN
o	Combina múltiples BIN en uno solo.
o	Genera un nuevo .cue sincronizado.
o	Mueve los archivos originales a una carpeta segura.
•	🎵 Generación de playlists (.m3u)
o	Detecta automáticamente respaldos multi-disco.
o	Crea listas de reproducción listas para emuladores y ODEs.
•	🧼 Renombrado inteligente
o	Limpia títulos de etiquetas innecesarias (Beta, Demo, Hack, etc.).
o	Preserva y agrega la región del respaldo.
o	Estándar uniforme para tu librería.
•	📦 Organización para XStation
o	Ordena respaldos y discos en el formato correcto.
o	Soporta modo de simulación antes de aplicar cambios.
•	🛡️ Robustez y validaciones
o	Manejo de errores con logs claros (merge_errors.log).
o	Validación de archivos faltantes o dañados.
o	Progreso y estado en tiempo real.
________________________________________
🎶 Tracks soportados en la fusión
El script reconoce y soporta los siguientes tipos de tracks al fusionar BINs:
Tipo de Track	Tamaño de bloque
🎵 AUDIO	2352 bytes
💿 MODE1/2352	2352 bytes
💿 MODE2/2352	2352 bytes
💿 CDI/2352	2352 bytes
💿 CDG	2448 bytes
💿 MODE1/2048	2048 bytes
💿 MODE2/2336	2336 bytes
💿 CDI/2336	2336 bytes
✅ Si se encuentra un tipo de track desconocido, se usa por defecto 2352 bytes y se genera una advertencia en el log.
________________________________________
🖥️ Requisitos
•	Windows 10/11
•	PowerShell 5.1 o superior
•	.NET Framework (para la interfaz gráfica)
________________________________________
🚀 Uso
1.	Abrir la aplicación
Ejecuta el script .ps1 con PowerShell.
2.	Seleccionar carpeta
Escoge el directorio donde están tus archivos .cue / .bin.
3.	Elegir acción
o	🔄 Fusionar CUE/BIN → Unifica respaldos múltiples en un solo archivo.
o	🎶 Crear playlist .m3u → Agrupa respaldos y genera listas de reproducción.
o	🧹 Renombrar/Organizar → Limpieza de nombres y estructura.
o	📂 Ordenar para XStation → Prepara tu SD con todo listo.
4.	Confirmar
El script te pedirá confirmación antes de aplicar cambios.
________________________________________
📷 Capturas (Opcional)
👉 Aquí puedes poner screenshots de la GUI en acción.
________________________________________
🏆 Beneficios
•	✅ Librería más limpia y profesional.
•	✅ Compatibilidad con emuladores y ODEs (XStation, DuckStation, RetroArch).
•	✅ Automatización: menos trabajo manual.
•	✅ Logs claros para depuración.
•	✅ Seguro: mantiene copia de originales.
________________________________________
📌 Autor
👨‍💻 Gerardo Bernal
Si te sirve este proyecto, ¡dale una ⭐ en GitHub!
