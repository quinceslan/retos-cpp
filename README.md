# Restos-cpp
Retos simples de proyectos C++ de consola
## Agenda de contactos
Objetivo: Aplicar clases, vectores, control de flujo, búsqueda y validación.
* Crea una clase Contacto con nombre, teléfono y correo electrónico.
* Usa un vector\<Contacto\> para almacenar los contactos.
* Implementa un menú para:
    * Crear un nuevo contacto (validar que el teléfono no se repita).
    * Buscar un contacto por nombre.
    * Eliminar un contacto  por nombre o teléfono.
    * Mostrar todos los contactos.
## Inventario de Productos
Objetivo: Realizar uso de clases, encapsulación, STL (vector o map), y funciones auxiliares.
* Crea una clase Producto con nombres, precio y cantidad.
* Crea una clase inventario que almacene los productos (puede usar map\<string, Producto\> para asociarlos por código).
* Permite:
    * Agregar productos nuevos (validar que el código sea único).
    * Eliminar productos por código.
    * Listar todos los productos con su información.
    * Calcular el valor del inventario.
* Extensión: Implementar modificación de cantidad o precio, y exportar el inventario a CSV.

## Biblioteca
Objetivo: Modelar relaciones entre clases, aplicar herencia y estructuras.
* Crea las clases Libro, Usuario y Préstamo.
* Cada libro tiene un título, autor, ISBN y estado de disponibilidad.
* Cada usuario tiene Usuario tiene nombre, ID y un historial de préstamos.
* Permite:
    * Registrar libros y usuarios.
    * Realizar un préstamo (controlar que el libro no este prestado).
    * Devolver libros y actualizar su estado.
    * Consultar libros disponibles y prestados.
* Extensión: Usar fechas y controlar vencimientos o retrasos en devolución.

## Simulador de banco
Objetivo: Aplicar herencia, polimorfismo y abstracción con lógica financiera básica.
* Crea la clase cuenta con atributos como saldo, numero de cuenta, y métodos depositar() y retirar().
* Crea la clase Cliente con nombre, ID y una lista de cuentas.
* Crea la clase Banco que administra todos los clientes y sus cuentas.
* Implementa herencia con:
    * CuentaAhorro: limita ala cantidad de retiros por mes.
    * CuentaCorriente: permite sobregiro con límite.
* Permite:
    * Crear clientes y cuentas.
    * Consultar saldos.
    * Realizar depósitos, retiros y transferencias.
* Extensión: Agrega un sistema de administración simple (ID y PIN) y genera un reporte general.
