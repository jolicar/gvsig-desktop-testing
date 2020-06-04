
## HE00FB00CP002 Busqueda de un campo de tipo string en una tabla de datos

### Descripción

Cargar la tabla de datos,**FB_datos1.csv**, y comprobar que se puede realizar una busqueda de un registro dobre uno de sus campos.


 
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