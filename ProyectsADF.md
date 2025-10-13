# PROYECTOS EN AZURE DATA FACTORY!

**AZURE DATA FACTORY:** Servicio de integracion de datos dentros de Azure, es un orquestador
de pipelines(canalizaciones) que te permiten crear, automatizar flujo de trabajos para procesos
ETL

**Ejecicio 01:** Tengo un container con la carpeta input dentro de ella archivos con extensiones txt, y xlsx , la finalidad es llecarlo a otro contendor conde este en carpetas separadas con sus respectivas extensiones .

![Imagen de propuesta Proyect ADF](imagenes/Proyect01.png)

**Desarrollo:**
- Get Metada: Obtenmos los chilItemns como nombre y tipo
- Set variable:Obtiene la lista de los chilItems
- Iteracion ForEach: recorre la lista de cada valor del chilItems
- If Condicional anidado: Verifica si la extension comienza con txt, o si es xlsx
- Copy data anidado: dentro de if hay dos copy data que sirve para copiar los archivos dependiendo de su tipo de extension
- For Each: Bucle que va a ir recorriendo y ver las extensiones para llevarlo a su respectiva carpeta
- Delete: los archivos anteriores en su ruta original se eliminan
- Fin Proyect:Copia de multiples archivos con bucles y condicionales anidados
- Thank you¡

![Imagen de desarrollo Proyect ADF](imagenes/Proyec01_01.png)

![Resultado de Ejecucion ADF](imagenes/resultProyect01.png)