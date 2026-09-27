# CaféExpress — Tema N°3: Modelado de Casos de Uso

**Curso:** Modelado y Desarrollo de Aplicaciones (CIIN1322P)
**Grupo:** Grupo 8
**Integrantes:**
- Aguirre Salvador, Italo Alexander
- García Huamán, Marilin Alexandra
- Moza Paredes, Sebastián
- Ulloa Huacanjulca, Rodrigo Aarón

## Descripción

Módulo de **Pedidos Online** del sistema CaféExpress. Incluye el modelado UML de casos
de uso, la especificación completa de 3 casos de uso clave, diagramas de actividad y
el prototipado de pantallas del flujo de compra.

## Enlaces

- 🎨 Prototipo / wireframes (Figma): [Ver en Figma](https://www.figma.com/design/xitg2Amh9aFVWMljCWgevg/Sin-t%C3%ADtulo?node-id=0-1)

## Estructura del repositorio

```
cafeexpress-tema3-grupo8/
├── README.md
├── Tema3_GarciaAlexandra.pdf
└── diagramas/
    ├── 01-casos-de-uso.drawio
    ├── 02-actividad-cu03-realizar-pedido.drawio
    ├── 03-actividad-cu04-realizar-pago.drawio
    └── 04-flujo-navegacion.drawio
```

## Matriz de trazabilidad

| ID CU | Caso de uso | Actor(es) | Especificación | Diagrama de actividad | Pantalla / Prototipo | Estado |
|---|---|---|---|---|---|---|
| CU-01 | Registrarse / Iniciar sesión | Cliente, Barista, Admin | Referenciado (precondición transversal) | — | Pendiente de prototipar | ⏳ Pendiente |
| CU-02 | Explorar catálogo | Cliente, Barista | Referenciado en CU-03 | — | Pantalla 1 (Catálogo) | ✅ Validado |
| CU-03 | Realizar pedido | Cliente | ✅ Completa | `02-actividad-cu03-realizar-pedido.drawio` | Pantalla 1 y 2 | ✅ Validado |
| CU-04 | Realizar pago | Cliente, Sistema de Pagos | ✅ Completa | `03-actividad-cu04-realizar-pago.drawio` | Pantalla 2 | ✅ Validado |
| CU-05 | Seguir estado del pedido | Cliente | Referenciado | — | Pantalla 3 (Seguimiento) | ✅ Validado |
| CU-06 | Cancelar pedido | Cliente | Referenciado (extend de CU-03) | — | Pantalla 3 (botón Cancelar) | ✅ Validado |
| CU-07 | Gestionar estado del pedido | Barista | ✅ Completa | Referenciado en `02-...` (fin del flujo) | Pantalla 3 | ✅ Validado |
| CU-08 | Gestionar catálogo | Administrador | Referenciado (inventario) | — | Pendiente de prototipar (backoffice) | ⏳ Pendiente |
| CU-09 | Generar reportes de ventas | Administrador | Referenciado (inventario) | — | Pendiente de prototipar (backoffice) | ⏳ Pendiente |

Diagrama de navegación general: `04-flujo-navegacion.drawio`

## Control de versiones

- Commits descriptivos siguiendo el formato `tipo: alcance del cambio` (ej. `docs:`, `feat:`).
- Versión de entrega: **v1.0-tema3**
