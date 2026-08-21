# 💰 Aplicación de Presupuesto

Una aplicación web interactiva diseñada para gestionar finanzas personales mediante el control detallado de ingresos y egresos. El proyecto calcula dinámicamente el presupuesto disponible y el porcentaje de gastos en tiempo real.

## 🚀 Características Principales
- **Cálculo Dinámico:** Actualización automática del saldo total y los porcentajes de cada gasto respecto a los ingresos.
- **Gestión de Registros:** Interfaz intuitiva para agregar y eliminar transacciones (ingresos y egresos).
- **Diseño Responsivo:** Experiencia de usuario optimizada para dispositivos móviles y de escritorio.
- **Arquitectura de Código:** Implementación de Programación Orientada a Objetos (POO) para mantener un código modular y escalable.

## 🛠️ Tecnologías Utilizadas
- **HTML5:** Estructura semántica.
- **CSS3:** Variables, Flexbox y diseño moderno.
- **JavaScript (Vanilla):** Lógica de negocio, manipulación del DOM y estructuración mediante clases (`Dato`, `Ingreso`, `Egreso`).

## 📂 Estructura del Proyecto
├── CSS/
│ ├── estilos.css
│ └── fondo.png
├── js/
│ ├── app.js # Lógica principal y controladores del DOM
│ ├── Dato.js # Clase padre
│ ├── Ingreso.js # Clase hija para ingresos
│ └── Egreso.js # Clase hija para egresos
└── index.html # Estructura principal
