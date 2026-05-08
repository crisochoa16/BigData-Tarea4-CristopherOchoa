# Proyecto MongoDB - Logitech

## Descripción del proyecto

Este proyecto consiste en el diseño e implementación de una base de datos NoSQL utilizando MongoDB para una tienda de periféricos Logitech.

---

# Caso de uso

El sistema representa una tienda virtual especializada en periféricos Logitech, incluyendo:

- Mouse
- Teclados
- Audífonos

Cada cliente puede realizar pedidos de diferentes productos y el sistema almacena la información relacionada con las compras.

MongoDB fue seleccionado debido a:

- Flexibilidad en el manejo de documentos
- Escalabilidad
- Facilidad para trabajar con estructuras dinámicas
- Soporte para agregaciones y consultas complejas

---

# Colecciones implementadas

## clientes
Almacena información de los clientes registrados.

### Campos
- nombre
- email
- telefono
- ciudad
- direccion

---

## productos
Contiene el catálogo de periféricos Logitech.

### Campos
- nombre
- categoria
- marca
- precio
- stock
- descripcion
- disponible
- fechaCreacion

---

## pedidos
Almacena las compras realizadas por los clientes.

### Campos
- clienteId
- fechaPedido
- estado
- productos
- total
- metodoPago

---

# Funcionalidades implementadas

## Consultas básicas
- Inserción de documentos
- Selección de documentos
- Actualización de documentos
- Eliminación de documentos

---

## Consultas con filtros y operadores
- Filtro por categoría
- Operadores:
  - $gt
  - $lt
  - $gte
  - $lte
- JOIN con $lookup

---

## Consultas de agregación
- countDocuments()
- $group
- $sum
- $avg
- $min
- $max

---

# Autor

Cristopher Ochoa Ramos
