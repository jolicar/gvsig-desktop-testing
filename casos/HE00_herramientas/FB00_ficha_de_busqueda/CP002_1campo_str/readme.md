
## HE00FB00CP002 Busqueda de un campo de tipo string en una tabla de datos

[First, check the open issues of this test](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues?utf8=%E2%9C%93&set_filter=1&f%5B%5D=status_id&op%5Bstatus_id%5D=o&f%5B%5D=subject&op%5Bsubject%5D=%7E&v%5Bsubject%5D%5B%5D=HE00FB00CP002&f%5B%5D=&c%5B%5D=tracker&c%5B%5D=status&c%5B%5D=priority&c%5B%5D=subject&c%5B%5D=assigned_to&c%5B%5D=updated_on&group_by=)

### Descripcion

Cargar la tabla de datos,**FB_datos1.csv**, y comprobar que se puede realizar una busqueda de un registro dobre uno de sus campos. 

La falta de datos en un campo de tipo string hace que los resultados no sean los que esperariamos.

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1.* 
2. Tener acceso a la tabla de datos **FB_datos1.csv**
3. Tener arrancada la aplicacion con una vista nueva y vacia activa

### Pasos

1. Mostrar la tabla de atributos de **FB_datos1.csv** en la vista
2. Seleccionar menu Tabla/Busqueda por atributos. Escoger el atributo que queramos
3. Seleccionaremos el campo "STRING"
4. Seleccionaremos el operador "Igual a"
5. Seleccionaremos el valor "Yo yo7"
6. Pulsaremos en el boton "Buscar"

### Resultados esperados

Como resultado de la busqueda obtendremos 1 resultado, lo esperado seria obtener 2 resultados

### Reportar fallo

el registro numero 17 se encuentra vacio, no presenta datos para este campo
