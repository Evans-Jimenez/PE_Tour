# Tour Virtual de Flores Endémicas de la República Dominicana

### Descripción
Este proyecto es un tour virtual interactivo de flores, árboles y plantas endémicas de la República Dominicana, desarrollado utilizando **krpano**. El objetivo es educar e informar a los usuarios sobre la biodiversidad de la flora del país mediante un recorrido inmersivo y visualmente atractivo.

### Especies Presentadas
El tour incluye imágenes y descripciones detalladas de las siguientes especies:

- **Rosa de Bayahibe** (*Pereskia quisqueyana*): Una flor nacional, muy apreciada por su rareza y belleza.
- **Árbol Ceiba** (*Ceiba pentandra*): Un árbol icónico y de gran tamaño, venerado en muchas culturas del Caribe.
- **Cubanola** (*Cubanola domingensis*): Arbusto endémico con flores tubulares, conocidas por su fragancia agradable.
- **Árbol de Copey** (*Clusia rosea*): Árbol robusto que produce frutos interesantes y flores grandes.
- **Lengua de Buey** (*Plumeria alba*): Árbol pequeño con flores blancas aromáticas, común en la región.


### Tecnologías Utilizadas
- **krpano**: Utilizado para crear el tour virtual y la interacción en 3D.
- **HTML5/CSS3**: Estructura y estilo del contenido del tour.
- **JavaScript**: Lógica y funcionalidad adicional.

### Funcionalidades
- Navegación interactiva por diferentes vistas que representan el entorno de las plantas.
- Información detallada sobre cada especie, accesible mediante puntos interactivos.
- Imágenes de alta calidad y animaciones suaves.
  
### Instalación y Uso
1. Clona el repositorio:
   ```bash
   git clone https://github.com/Acrosszawarudo/PE_Tour.git
   ```
2. Instala las dependencias necesarias (si las hay).
3. Ejecuta el proyecto localmente o despliega en un servidor web:
   ```bash
   npm start
   ```
   
### Estructura del Proyecto
```
/PE_TOUR
│
├── /Carteles          # Imágenes o gráficos informativos del tour
├── /panos             # Panorámicas utilizadas en el tour virtual
├── /plugins           # Plugins adicionales de krpano
├── /recursos          # Recursos adicionales de diseño
├── /recursos3D        # Recursos 3D
├── /skin              # Skins y estilos personalizados
│
├── .gitignore         # Archivos y carpetas ignoradas por Git
├── index.html         # Página principal del tour
├── README.md          # Este archivo
├── tour_testingserver_macos  # Servidor de prueba para macOS
├── tour_testingserver.exe    # Servidor de prueba para Windows
├── tour.js            # Archivo JavaScript para el tour
├── tour.xml           # Archivo de configuración principal del tour (krpano)
```

### Próximos Pasos
- Añadir más especies endémicas.
- Mejorar las descripciones botánicas de las plantas.
- Optimizar el rendimiento del tour para dispositivos móviles.

### Contribuciones
Las contribuciones son bienvenidas. Por favor, sigue los siguientes pasos si deseas contribuir:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Realiza los cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature-nueva-funcionalidad`).
5. Abre un Pull Request.
