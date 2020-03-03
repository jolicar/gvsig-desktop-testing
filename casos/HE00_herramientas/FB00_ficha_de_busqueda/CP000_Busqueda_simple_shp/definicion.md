

## HE00FB00CP000 Busqueda simple en un shape.

### Descripción

Cargar un shape, **ne_110m_admin_0_countries**, y comprobar que se puede realizar una
busqueda sobre una de sus columnas utilizando la *ficha de busqueda*. 

### Prerrequisitos

1. Tener instalado *gvSIG desktop 2.5.1+* con el proveedor de shape cargado.
2. Tener acceso al shape **shape/ne_110m_admin_0_countries.shp**.
3. Tener arrancada la aplicacion con una vista nueva y vacia activa.

### Pasos

1. Cargar la capa **shape/ne_110m_admin_0_countries.shp** en la vista.
2. Seleccionar menu **layer/Busqueda por attributos**. Al hacerlo
   aparecera la ficha de busqueda con 177 elementos.
3. Seleccionaremos el campo "CONTINENT"
4. Seleccionaremos el operador "Igual a"
5. Seleccionaremos el valor "Oceania"
6. Pulsaremos en el boton "Buscar"

### Resultado esperado

Como resultado de la busuqeda obtendremos 7 elementos:
- Fiji
- P.N.G
- Van.
- New C.
- S. Is.
- N.Z.
- Auz.

### Reportar fallo

En caso de que los resultados obtenidos no sean los correctos puede reportar
una incidencia en el *redmine* de *gvSIG deskop* que puede localizar en 
https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues .

[Registrar indicendia](https://redmine.gvsig.net/redmine/projects/gvsig-desktop/issues/new?issue[subject]=HE00FB00CP000+Busqueda+simple+en+un+shape)



