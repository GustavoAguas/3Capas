
- **backend:** Contiene el código fuente y la configuración del servidor backend.
- **database:** Contiene el archivo de inicialización de la base de datos.
- **frontend:** Contiene el código fuente y la configuración del frontend Angular.
- **docker-compose.yml:** Archivo de configuración de Docker Compose.
- **.dockerignore:** Archivo para especificar los elementos a excluir durante la construcción de las imágenes de Docker.
- **.gitignore:** Archivo para especificar los elementos a excluir del control de versiones Git.

## Instrucciones de Uso

1. Clona este repositorio:

    ```bash
    git clone https://github.com/GustavoAguas/3Capas
    ```

2. Navega al directorio del proyecto:

    ```bash
    cd Act5-TresCapas
    ```

3. Construye y levanta los contenedores con Docker Compose:

    ```bash
    docker-compose up --build
    ```

4. Accede a la aplicación desde tu navegador:

    - Frontend: [http://localhost:4200](http://localhost:4200)
    - Backend: [http://localhost:3000](http://localhost:3000)

5. Detén los contenedores cuando hayas terminado:

    ```bash
    docker-compose down
    ```

## Personalización

- Puedes ajustar la configuración de cada servicio en el archivo `docker-compose.yml`.
- Personaliza los archivos `Dockerfile` en cada directorio para adaptar las imágenes de Docker según tus necesidades.

## Contribuir

Si encuentras algún problema o tienes sugerencias para mejorar el proyecto, ¡siéntete libre de contribuir abriendo un problema o enviando un pull request!

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
