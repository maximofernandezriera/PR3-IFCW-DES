# PR3-IFCW-DES

## API de gestión de gastos en Laravel

Este proyecto consiste en la creación de una API para una aplicación de seguimiento de gastos. La API permitirá a los usuarios crear, leer, actualizar y eliminar gastos, así como registrarse e iniciar sesión. Cada usuario tendrá su propio conjunto de gastos.

## REQUISITOS MÍNIMOS ESPECÍFICOS DE LARAVEL

* Registro de usuario
* Generación y validación de JWT para la autenticación y la sesión del usuario
* Lista y filtro de gastos
* Añadir nuevo gasto
* Eliminar gastos existentes
* Actualizar gastos existentes

## REQUISITOS GENERALES

* Se utilizará JWT (JSON Web Token) tal y como tenéis en el ejemplo proporcionado para proteger los endpoints e identificar al solicitante.
* Se pueden utilizar las siguientes categorías de gastos:
    * Comestibles
    * Ocio
    * Electrónica
    * Utilidades
    * Ropa
    * Salud
    * Otros

## Persistencia de datos

Persistencia de datos: Los datos de los gastos deben almacenarse en una base de datos SQLite tal y como hemos visto en clase.

## Documentación de la API

* Debes proporcionar las historias de usuario para que pueda realizarse el testing de todas las funcionalidades de la API.
* Se recomienda, como en entregas anteriores, el uso de Postman.

- Ejemplo de crear un gasto:
  
      http
      Copy
      POST /api/expenses
      Headers: { "Authorization": "Bearer <token>" }
      Body:
      {
        "amount": 150.50,
        "category": "comida",
        "description": "Cena en restaurante"
      }

## Rúbrica

| Criterio | Excelente (3) | Bueno (2) | Regular (1) | Necesita mejorar (0) |
|---|---|---|---|---|
| Funcionalidad | Todas las características requeridas funcionan correctamente. | La mayoría de las características requeridas funcionan correctamente. | Algunas de las características requeridas funcionan correctamente. | Pocas o ninguna de las características requeridas funcionan correctamente. |
| Código | El código es limpio, bien organizado y fácil de entender. | El código es en su mayoría limpio y bien organizado. | El código es algo desorganizado y difícil de entender. | El código es desorganizado y difícil de entender. |
| Pruebas | Hay pruebas unitarias y de integración para todas las características. | Hay pruebas unitarias y de integración para la mayoría de las características. | Hay algunas pruebas unitarias y de integración. | No hay pruebas unitarias ni de integración. |
| Documentación | La documentación es completa y clara. | La documentación es en su mayoría completa y clara. | La documentación es incompleta o poco clara. | No hay documentación. |
| Diseño | El diseño de la API es intuitivo y fácil de usar. | El diseño de la API es en su mayoría intuitivo y fácil de usar. | El diseño de la API es algo confuso. | El diseño de la API es confuso y difícil de usar. |
| Control de versiones | Se utiliza un sistema de control de versiones (Git) y se han realizado commits regulares con mensajes descriptivos. | Se utiliza un sistema de control de versiones (Git) pero no se han realizado commits regulares o los mensajes no son descriptivos. | Se utiliza un sistema de control de versiones (Git) pero no se han realizado commits o no se han realizado de forma adecuada. | No se utiliza un sistema de control de versiones. |

# NOTAS ADICIONALES

Podéis tomar como referencia este proyecto visto en clase:

- [Todo list api project](https://github.com/maximofernandezriera/todo-laravel)

# FECHA DE ENTREGA: 16-02-2025
