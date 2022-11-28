# Delitos en Sonora
Proyecto final de la materia bases de datos II, cursada durante el semestre 2022-2 en la Universidad de Sonora.

### Instrucciones para ejecutar la libreta
 1. Crear un entorno de anaconda utilizando el archivo db-env.yml
    ```console
    path@user:~$ conda env create -f db-env.yml
    ```
 2. Activa el entorno de anaconda
 ```console
    path@user:~$ conda activate db-env
    ```
 3. Ejecuta el siguiente comando para crear un kernel relacionado al entorno db-env.
    ```console
    path@user:~$ python -m ipykernel install --user --name=db-env
    ```
 4. Utiliza el archivo *db_project.sql* para crear la estructura y llenar con registros la base de datos, antes de correrlo, asegurate de crear un nuevo esquema.
 5. En la libreta, llena los datos correspondientes a tu servidor de bases de datos.
