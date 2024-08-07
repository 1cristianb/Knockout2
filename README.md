# Knockout 2

## Descripción del Proyecto

Knockout 2 es un sitio web de e-commerce especializado en la venta de libros, cómics y manga. Los usuarios pueden navegar por una amplia colección de títulos, añadir productos a su carrito y realizar compras de manera segura y sencilla.

## Tecnologías Utilizadas

- **Angular**: Framework utilizado para la construcción de la interfaz de usuario.
- **TypeScript**: Lenguaje de programación utilizado en conjunto con Angular para el desarrollo del frontend.
- **Node.js**: Entorno de ejecución utilizado para el backend/servidor de la aplicación.
- **MySQL**: Base de datos utilizada para almacenar información.
- **Bootstrap**: Framework CSS utilizado para el diseño y la maquetación responsiva de la interfaz de usuario.

## Requisitos Previos

Asegúrate de tener instalados los siguientes componentes antes de comenzar:

- Node.js y npm
- MySQL Server

## Instalación

1. **Clonar el repositorio**:
    ```bash
    git clone https://github.com/1cristianb/knockout2.git
    cd knockout2
    ```

2. **Configurar la base de datos**:

    Crear una base de datos en MySQL. El script se puede encontrar en `servidor/db/script.sql`
    

3. **Configurar las credenciales de la base de datos**:

   Crea un archivo .env con lo siguiente:
    ```javascript
        PORT: 'tu_puerto'
        DB_HOST: 'localhost',
        DB_PORT='tu_puerto'
        DB_USER: 'tu_usuario',
        DB_PASSWORD: 'tu_contraseña',
        DB_DATABASE: 'knockout'
   
    ```

4. **Instalar dependencias**:

   - Backend:
     ```bash
     cd servidor
     npm install
     ```

   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

5. **Iniciar la aplicación**:

   - Backend:
     ```bash
     cd servidor
     npm start
     ```

   - Frontend:
     ```bash
     cd frontend
     ng serve
     ```

## Uso

Una vez que la aplicación esté en funcionamiento, puedes acceder al sitio web a través de tu navegador web en la siguiente dirección: http://localhost:4200

## Autor

Cristian Boschi ,Leandro Martinez y Tabatha Peralta

