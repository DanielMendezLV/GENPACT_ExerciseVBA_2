<p style="font-size: 18px">
VBA Macro
</p>



<h1 align="center" style="font-size: 40px; font-weight: bold;">Manual de pruebas</h1>


<div align="center">
Daniel Alberto Méndez Díaz
</div>

<br><br>

<h4 align="center" style="font-size: 18px; font-weight: bold;">Guatemala 2022</h4>

---

<h1>Tabla de Contenido</h1>


- [**_Usuarios de prueba_**](#usuarios-de-prueba)
- [**_Ejecución_**](#ejecución)
  - [**_Iniciar aplicación_**](#iniciar-aplicación)
  - [**_Formulario_**](#formulario)
  - [**_Agregar registro_**](#agregar-registro)
  - [**_Buscar registros_**](#buscar-registros)
  - [**_Modificar registros_**](#modificar-registros)
  - [**_Eliminar registros_**](#eliminar-registros)
  - [**_Reporte 1 Por Rango_**](#reporte-1-por-rango)
  - [**_Reporte 2 Por Inicial_**](#reporte-2-por-inicial)


---

# **Usuarios de prueba**

En la base de datos actual de la macro se encuentran los siguientes usuarios para realizar pruebas:

!["configuración-inicial"](/images/0.png)


---

# **Ejecución**

## **Iniciar aplicación**

[IMPORTANTE] Es necesario abrir la macro y dar permisos para ejecutar.

!["iniciar-ejecutar-1"](/images/1.png)

En esta sección tenemos las siguientes secciones que pueden darse click:

1. Abrir formulario
2. Esconder la hoja oculta (Contacts) (por defecto viene escondida)
3. Mostrar la hoja oculta (Contacts)
4. Hoja por defecto de la Macro

Los apartados 5 y 6 son hojas utilizadas para los reportes.
Se hace una copia de estas en un nuevo archivo.

!["iniciar-ejecutar-2"](/images/2.png)

La hoja oculta tiene como nombre: Contacts


## **Formulario**

El formulario tiene tres secciones marcadas de diferentes colores

!["formulario-inicio"](/images/3.png)

Rojo: El area de creación o edición, tiene los campos requeridos.
<br>
Verde: Es un panel que permite la búsqueda por código o Nombre, así como realizar edición.
<br>
Morado: Sección para generar los reportes.


## **Agregar registro**

Validaciones iniciales sobre los campos requeridos, para mostrar las validaciones es NECESARIO presionar el boton guardar:

!["formulario-inicio"](/images/4.png)

<br>
Validaciones de correo y fecha 
<br>

!["formulario-inicio"](/images/5.png)

Si los campos estan correctos como el siguiente ejemplo permite guardar y automaticamente cambia el ID:

!["processed"](/images/6.png)

!["processed"](/images/7.png)


## **Buscar registros**

Es posible buscar registros por medio del código o el nombre, es necesario dar click en buscar. De no ingresar código o nombre mostrara un mensaje de corrección:


!["processed"](/images/9.png)

Búsqueda por código:

!["processed"](/images/8.png)

Búsqueda por nombre:

!["processed"](/images/10.png)



## **Modificar registros**

Para modificar un registro es necesario SELECCIONARLO y dar click después en EDITAR, nos cargara los datos correspondientes:

!["processed"](/images/11.png)

Realizamos los respectivos cambios:

!["processed"](/images/12.png)

Verificamos el cambio:
!["processed"](/images/13.png)


## **Eliminar registros**

Para eliminar un registro es necesario SELECCIONARLO y dar click después en ELIMINAR, nos mostrara un mensaje de advertencia:

!["processed"](/images/14.png)
!["processed"](/images/15.png)

Presionamos YES y se muestra un mensaje de eliminación:
!["processed"](/images/16.png)


## **Reporte 1 Por Rango**

Es necesario ingresar el rango de los códigos que se necesite:

!["processed"](/images/17.png)
!["processed"](/images/18.png)


## **Reporte 2 Por Inicial**

Es necesario ingresar la inicial de los registros que se necesiten:

!["processed"](/images/19.png)
!["processed"](/images/20.png)

