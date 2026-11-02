# php-mvc-framework

Aplicación web en PHP construida con arquitectura MVC, con router propio, autoloading con Composer y compilación de assets con Gulp.

## 🛠️ Tecnologías
PHP · MySQL · Composer · Node.js · Gulp · HTML · CSS · JavaScript

## 📁 Estructura
- `controllers/`: lógica de cada ruta
- `models/`: acceso a datos
- `views/`: plantillas HTML
- `classes/`: clases auxiliares
- `includes/`: configuración y funciones
- `src/`: assets fuente (CSS/JS)
- `public/`: archivos públicos y punto de entrada
- `Router.php`: enrutador de la aplicación

## ⚙️ Instalación
```bash
git clone https://github.com/ikercruzz/mvc-php.git
cd mvc-php
composer install
npm install
npm run dev
```
Configura tu conexión a base de datos en `includes/` y levanta el servidor:
```bash
php -S localhost:3000 -t public
```
## 👤 Autor
Iker De la Cruz · [LinkedIn](https://www.linkedin.com/in/iker-dela-cruz/)
