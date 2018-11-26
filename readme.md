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
| create_much |        |                                                                 |
|        read |        |  	


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

