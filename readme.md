# What is CRUD_model?

**CodeIgniter CRUD_Model**, Es una simplificación de las funciones *crear*, *leer*, *editar*, *deshabilitar*, *habilitar* y *eliminar*. cietamente existen varias herramientas mucho más completas. No queria tener algo que no usaba. asi que dicidi creear mi propia estructrua CRUD_model. A este pretendo agregarle funcionalidades según sea la necesidad,  así como un sistema de observador basado en eventos, adivinanzas inteligentes de nombres de tablas y eliminación sin problemas.

Este modelo no es precisamente una libreria y una aplicacion de tercero, por lo que permite facilmente trabajar control modelos inclusos crear modelos para cada controlador y usar la base del CRUD sin ningun problema.

## Installation:

1. descarga el archivo `CRUD_model.php` del repositorio. colocalo en  la ruta.
``` 
CodeIgniter
  ├── application
      └── model
          └── CRUD_Model.php
```
2. Entra en `aplication > Confing ` y edita el archivo `autoload.php` solo debes agregar  
 `$autoload['model'] = array('CRUD_model');`

Listo ya puedes usarlo desde tu controlador. 


## Table of contents:
|    Property | Status | Description                                                            |
|------------:|:--------:|:------------------------------------------------------------------------|
| [__getAll](#__getAll)    |:warning:| Es un constructor de 'read' pasado el nombre de la entidad a consultar |
|      create |:+1:| Registra un nuevo elemento en base de datos                         |
|[create](create)||           Registra un nuevo elemento en base de datos|
|[create_much](create_much)||      Correr una array e insertar varios elementos|
|             [create_much](create_much) | :warning: | Registra un nuevo elemento en base de datos                                        |
|                           [read](read) | :warning: | Correr una array e insertar varios elementos                                       |
|                     [read_id](read_id) | :warning: | <> lee todos los elementos de una <>                                               |
|   [read_field_table](read_field_table) | :warning: | <>                                                                                 |
|               [read_where](read_where) | :warning: | Retorna el campo solicitado ejemplo: << db->select('cod_key') >>                   |
|                 [read_last](read_last) | :warning: | <> retorna todos los valores de tabla                                              |
|     [read_data_table](read_data_table) | :warning: | Retorna el ultimo valor solicitado. ORDER_BY = DESC, LIMIT = 1                     |
|                           [edit](edit) | :warning: | Realiza un > > retorna el valor en formato                                         |
|                 [edit_much](edit_much) | :warning: | Editar un elemento pasado el ID                                                    |
|       [edit_all_where](edit_all_where) | :warning: | Corre (2) array con todos los Id's a editar y otro con los dato a modificar por Id |
|               [edit_where](edit_where) | :warning: | realiza un > de todos los elementos de la tabla >                                  |
|                       [delete](delete) | :warning: | editar un elemento pasado un ID >                                                  |
|             [delete_much](delete_much) | :warning: | Elimina el elemento pasado el ID                                                   |
|           [delete_where](delete_where) | :warning: | Corre un array con todos los Id's a eliminar de la tabla                           |
|                     [disable](disable) | :warning: | Eliminar un elemento pasado el ID >                                                |
|           [disable_much](disable_much) | :warning: | Cambia de 'estado' (I inactivo)                                                    |
| [disable_all_where](disable_all_where) | :warning: | Corre un array con todos los Id's que se van ha desabilitar (disable)              |
|                       [enable](enable) | :warning: | desabilita todos los elementos de la tabla >                                       |
|             [enable_much](enable_much) | :warning: | Habilita un elemento que fue desabilitado >                                        |

  


##### Leyenda:
 Status | Description  |
:--------:|:--------------|
:+1:|  Funciona 
:-1:| No funciona (Bug o falta completar)
:warning: | Falta desarrollar


- :warning:  Falta desarrollar


# Documentation 
Intentare dar el mayor numero de destalles posible sobre cada una de las funciones desarrolladas. no todas estan en funcionameinto muchas de de ellas tan solo son una idea de lo que se quiere hacer mas adelante.

### __getAll($entity, $where, $method)

<details>
<summary>
<a name="__getAll"></a> :warning: | Show info.
</summary>
  
```python
print("hello world!")
```

</details>

---

### create($entity, $where, $method)
<details>
<summary>
<a name="__getAll"></a> :warning: | Show info.
</summary>
  
```python
print("hello world!")
```

</details>

# :scream:¡INCOMPLETO! :scream:

