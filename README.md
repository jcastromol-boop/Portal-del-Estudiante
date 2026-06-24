[README.md](https://github.com/user-attachments/files/29313515/README.md)
# Sistema de Gestión Integral - Centro Hellen Keller

Este repositorio contiene la documentación y maquetación del **Sistema de Gestión Integral** diseñado para el Centro Nacional de Educación Hellen Keller (CNEHK). El objetivo del proyecto es centralizar y optimizar los procesos académicos y administrativos de la institución, mejorando la atención a estudiantes con discapacidad visual y sordoceguera.

## Integrantes y Roles
*   **[Nombre del Usuario]**: Responsable de la sección "Ejemplo de uso del sistema".

## Descripción del Proyecto
El sistema es una solución web interactiva que permite la gestión de terapias, planes educativos individualizados (PEI) y el seguimiento del progreso de los estudiantes. Facilita la comunicación entre administradores, terapeutas y encargados legales. Se enfoca en la accesibilidad y la usabilidad para apoyar la educación especial.

## Alcance
*   Gestión de usuarios y roles (Administrador, Terapeuta, Encargado Legal).
*   Creación y seguimiento de Programas Educativos Individualizados (PEI).
*   Visualización de reportes de progreso y gráficas de rendimiento simplificadas.
*   Portal de comunicación para encargados legales.

## Tecnologías Utilizadas (Ficticias)
Para la implementación de este sistema, se proponen las siguientes tecnologías:

*   **Frontend:** React.js con TypeScript, utilizando Next.js para renderizado del lado del servidor y Tailwind CSS para estilos.
*   **Backend:** Node.js con Express.js, implementando una API RESTful.
*   **Base de Datos:** PostgreSQL para la gestión de datos relacionales.
*   **Autenticación:** JWT (JSON Web Tokens) para la seguridad de las sesiones.
*   **Despliegue:** Docker para la contenerización y Vercel/AWS para el despliegue.

## Instalación (Ficticia)
Para configurar el entorno de desarrollo local, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/Sistema-Gestion-Integral.git
    cd Sistema-Gestion-Integral
    ```
2.  **Instalar dependencias del frontend:**
    ```bash
    cd frontend
    npm install
    ```
3.  **Instalar dependencias del backend:**
    ```bash
    cd ../backend
    npm install
    ```
4.  **Configurar variables de entorno:**
    Crea un archivo `.env` en las carpetas `frontend` y `backend` con las configuraciones necesarias (ej. `DATABASE_URL`, `JWT_SECRET`).
5.  **Iniciar la base de datos (Docker):**
    ```bash
    docker-compose up -d postgres
    ```
6.  **Ejecutar migraciones de la base de datos:**
    ```bash
    npm run migrate
    ```
7.  **Iniciar el servidor backend:**
    ```bash
    npm start
    ```
8.  **Iniciar el servidor frontend:**
    ```bash
    cd ../frontend
    npm start
    ```

## Uso
Una vez que el sistema esté en funcionamiento, podrás acceder a la interfaz de usuario a través de tu navegador web en `http://localhost:3000` (o el puerto configurado para el frontend).

## Documentación
Puedes encontrar la documentación detallada de la sección de ejemplo de uso del sistema en el archivo [docs/ejemplo_uso_sistema.md](docs/ejemplo_uso_sistema.md).

## Contribución
Si deseas contribuir a este proyecto, por favor, consulta nuestro archivo [CONTRIBUTING.md](CONTRIBUTING.md) para conocer las directrices.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---
*Proyecto desarrollado para el curso SOFT-06: Diseño y programación web, Universidad CENFOTEC.*
