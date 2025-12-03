# Manantial de Vida - Sitio Web de la Iglesia

Bienvenido al repositorio del sitio web de la Iglesia Manantial de Vida.

## 🌟 Acerca del Proyecto

Este es el sitio web oficial de la Iglesia Manantial de Vida, diseñado para proporcionar información sobre nuestra comunidad, servicios, ministerios y facilitar la comunicación con nuestros miembros y visitantes.

## 🚀 Características

- **Diseño Responsivo**: Totalmente adaptable a dispositivos móviles, tablets y computadoras
- **Navegación Intuitiva**: Menú fácil de usar con navegación suave entre secciones
- **Secciones Informativas**:
  - Inicio con mensaje de bienvenida
  - Acerca de nosotros (misión, visión, valores)
  - Servicios y horarios
  - Ministerios disponibles
  - Formulario de contacto
- **Interactividad**: Elementos animados y formulario de contacto funcional
- **Accesibilidad**: Diseñado siguiendo mejores prácticas de accesibilidad web

## 📁 Estructura del Proyecto

```
Manantial-de-Vida/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos del sitio
├── js/
│   └── script.js       # JavaScript para interactividad
├── images/             # Directorio para imágenes
└── README.md           # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- GitHub Pages (para hospedaje)

## 📦 Instalación y Uso

### Ver el Sitio Localmente

1. Clona este repositorio:
   ```bash
   git clone https://github.com/marckomendez/Manantial-de-Vida.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd Manantial-de-Vida
   ```

3. Abre `index.html` en tu navegador web preferido

### Despliegue en GitHub Pages

Este sitio está configurado para ser desplegado automáticamente a través de GitHub Pages:

1. Ve a la configuración del repositorio en GitHub
2. En la sección "Pages", selecciona la rama principal (main) como fuente
3. El sitio estará disponible en: `https://marckomendez.github.io/Manantial-de-Vida/`

## ✏️ Personalización

### Actualizar Información de Contacto

Edita el archivo `index.html` en la sección de contacto (líneas con clase `.contact-item`) para actualizar:
- Dirección física
- Número de teléfono
- Correo electrónico
- Horarios de oficina

### Modificar Horarios de Servicios

En `index.html`, busca la sección con id `servicios` y actualiza los horarios en cada `.service-time`.

### Cambiar Colores del Sitio

En `css/styles.css`, modifica las variables CSS en `:root`:
```css
:root {
    --primary-color: #2c5aa0;
    --secondary-color: #5b9bd5;
    --accent-color: #f39c12;
    /* ... otros colores */
}
```

### Agregar Imágenes

1. Coloca tus imágenes en el directorio `images/`
2. Referencia en HTML usando rutas relativas: `<img src="images/tu-imagen.jpg" alt="Descripción">`

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu característica (`git checkout -b feature/AmazingFeature`)
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es propiedad de la Iglesia Manantial de Vida. Todos los derechos reservados.

## 📞 Contacto

Para más información, visita nuestro sitio web o contáctanos directamente a través del formulario en la página.

---

**Manantial de Vida** - Una comunidad de fe, esperanza y amor 🙏