# URL Shortener Service

Este es un servicio de acortamiento de URLs construido con Node.js, Express y MongoDB. Permite a los usuarios crear, recuperar, actualizar y eliminar URLs cortas, así como obtener estadísticas sobre el uso de las mismas.

## Tabla de Contenidos

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [API Endpoints](#api-endpoints)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Características

- Crear una nueva URL corta.
- Recuperar la URL original a partir de una URL corta.
- Actualizar una URL corta existente.
- Eliminar una URL corta existente.
- Obtener estadísticas sobre el uso de la URL corta.

## Tecnologías Utilizadas

- Node.js
- Express.js
- MongoDB
- Mongoose
- nanoid (para generar códigos únicos)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/url-shortener.git
   cd url-shortener
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Asegúrate de que MongoDB esté en ejecución en tu máquina local.

4. Inicia el servidor:

   ```bash
   node server.js
   ```

   El servidor se ejecutará en `http://localhost:3000`.

## Uso

Puedes usar herramientas como [Postman](https://www.postman.com/) para interactuar con la API. A continuación se presentan los endpoints disponibles:

### API Endpoints

1. **Crear un Short URL**
   - **Método**: `POST`
   - **URL**: `/api/short

https://roadmap.sh/projects/url-shortening-service