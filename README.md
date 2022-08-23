# Practica 9 con "Azure SQL Database"

*Crear una base de datos en consola y un Cosmos DB*

**Paso 1 _Consola_**
- Abrir cloud shell

![Paso 1.1](/imagenes/img1.png)

- Teclear en consola el siguiente comando "git clone https://github.com/MicrosoftLearning/DP-900T00A-Azure-Data-Fundamentals dp-900" y despues "ls"
  
![Paso 1.2](/imagenes/img1_2.png)

- Despues de clonar el repositorio, es necesario entrar a la siguiente carpeta "cd dp-900/sql" y ejecutamos "bash setup.sh"
  > Nota: El setup.sh contiene instrucciones para crear una bd en azure

  ![Paso 1.3](/imagenes/img1_3.png)

- Ahora es necesario ir a los recursos que nos creo que seran dos (uno para procesar la informacion y la bd como tal).
  
  ![Paso 1.4](/imagenes/img1_4.png)

- Posteriormente en informacion general ir a "establecer firewall"
  
  ![Paso 1.5](/imagenes/img1_5.png)

- Ahora es necesario agregar nuestra IP y guardamos
  
  ![Paso 1.6](/imagenes/img1_6.png)

- Despues damos clic en "Editor de consultas" e iniciamos sesion
  
  ![Paso 1.7](/imagenes/img1_7.png)

**Paso 2 _Consultas/Comandos_**
- Al elegir alguna tabla se nos mostrara una consola

![Paso 2.1](/imagenes/img2.png)

- Si queremos ver los datos de alguna tabla solo ponemos le decimos que seleccione "select" todo "*" de "from" la tabla que deseamos, en este caso "Inventory"(Color azul), despues damos en ejecutar(Color rojo) y nos mostrara los resultados (Color verde).

![Paso 2.2](/imagenes/img2_2.png)

- Si queremos ver los datos de alguna tabla donde aparezca cierto dato en cierta columna, solo es necesario seguir el ejemplo de la imagen siguiente.
  La consulta es igual que la anterior solo que esta ves despues del from, especificamos un where seguido del nombre de la columna y el valor que estamos buscando.

![Paso 2.3](/imagenes/img2_3.png)

- Ahora si queremos recuperar los artículos de inventario ordenados por la cantidad en las existencias, es necesario lo siguiente.

![Paso 2.4](/imagenes/img2_4.png)

**Paso 3 _Cosmos DB_**
- Buscar y elegir "Cosmos DB"

  ![Paso 3.1](/imagenes/img3.png)

- A continuacion damos en crear
  
  ![Paso 3.2](/imagenes/img3_2.png)

- Posteriormente seleccionamos "nucleo SQL"
  
  ![Paso 3.3](/imagenes/img3_3.png)

- Elegimos el grp de recursos, la region y lo demas lo dejamos igual, despues damos en "revisar y crear" y por ultimo en crear
  
  ![Paso 3.4](/imagenes/img3_4.png)

- Cuando se ha creado nuestro recurso lo elegimos, vamos a "inicio rapido", seleccionamos el lenguje y damos en "crear el contenedor"
  
  ![Paso 3.5](/imagenes/img3_5.png)

- Despues nos permitira descargarlo o abrir el explorador
  
  ![Paso 3.6](/imagenes/img3_6.png)

- En este caso abriremos el explorador, despues iremos a "items", posteriormente daremos en nuevo y pondremos los datos correspondientes para finalmente dar en "save" y luego "update". Se podran visualizar todas las que hemos creado.
  
  ![Paso 3.7](/imagenes/img3_7.png)

- Para ver datos solo tecleamos la instruccion segun la imagen y el id que deseemos conocer.
  
  ![Paso 3.8](/imagenes/img3_8.png)