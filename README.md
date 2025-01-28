# Pokémon App

Esta es una aplicación móvil desarrollada con Ionic Framework (Angular) que lista Pokémon utilizando la PokeAPI. La aplicación incluye scroll infinito, diseño responsive y una vista detallada para cada Pokémon.

## Características

- **Listado de Pokémon:** Muestra una lista de Pokémon con su imagen y nombre.
- **Scroll Infinito:** Carga progresiva de 20 elementos por vez.
- **Vista Detallada:** Información detallada de cada Pokémon, incluyendo:
  - Imagen
  - Nombre
  - Altura
  - Peso
  - Tipos
  - Estadísticas base
- **Diseño Responsive:** Optimizado para dispositivos móviles y tablets.
- **Manejo de Estado:** Control eficiente del estado de la aplicación.
- **Gestión de Errores:** Manejo de errores para fallos en la API.

## Tecnologías Utilizadas

- **Ionic Framework** (Angular)
- **TypeScript**
- **Axios** para consumo de la API RESTful
- **PokeAPI** como fuente de datos

## Instalación

1. Asegúrate de tener instalado Node.js y NPM.
2. Instala Ionic CLI globalmente:
   ```bash
   npm install -g @ionic/cli
   ```
3. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/pokemon-app.git
   ```
4. Ve al directorio del proyecto:
   ```bash
   cd pokemon-app
   ```
5. Instala las dependencias:
   ```bash
   npm install
   ```
6. Inicia la aplicación:
   ```bash
   ionic serve
   ```

## Estructura del Proyecto

```
src/
├── app/
│   ├── pages/
│   │   ├── pokemon-list/       # Página de listado de Pokémon
│   │   ├── pokemon-details/    # Página de detalles de Pokémon
│   ├── app-routing.module.ts   # Rutas de la aplicación
│   ├── app.module.ts          # Configuración principal
├── assets/                     # Recursos estáticos
├── environments/               # Configuraciones de entorno
```

## Uso

### Listado de Pokémon
- Abre la aplicación para ver una lista de Pokémon.
- Haz scroll hacia abajo para cargar más elementos.

### Vista Detallada
- Haz clic en cualquier Pokémon para ver información detallada sobre él.

## Capturas de Pantalla

_Agrega aquí capturas de pantalla de la aplicación funcionando en diferentes dispositivos._

## Notas

- La aplicación carga inicialmente los primeros 20 Pokémon. El scroll infinito permite cargar más hasta el Pokémon número 1200.
- Las imágenes de los Pokémon se obtienen directamente desde la PokeAPI.

## Recursos

- **PokeAPI:** [https://pokeapi.co/](https://pokeapi.co/)
- **Ionic Framework:** [https://ionicframework.com/](https://ionicframework.com/)

## Autor

Desarrollado por Luis.

---

¡Gracias por probar esta aplicación! Si tienes preguntas o sugerencias, no dudes en abrir un issue en el repositorio.
