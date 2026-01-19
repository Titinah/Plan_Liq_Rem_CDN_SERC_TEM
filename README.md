# 🇨🇱 Calculadora de Liquidación de Sueldos - Chile 2026

Herramienta web interactiva para la gestión y simulación de remuneraciones bajo la normativa laboral chilena vigente a **Enero 2026**. Desarrollada originalmente para el **Centro de Negocios Sercotec Temuco**.

## 🚀 Características Principales

Esta aplicación permite realizar el cálculo completo de "Haberes a Líquido" y "Costo Empresa", considerando:

* **Normativa 2026:** Incluye Sueldo Mínimo ($539.000) y nuevos factores previsionales.
* **Tipos de Contrato:** Soporte para contrato Indefinido, Plazo Fijo y Part-Time (con cálculo proporcional de sueldo mínimo).
* **Gratificación Legal:** Cálculo automático con tope de 4.75 IMM (Art. 50) o proporcional.
* **Haberes:** Gestión de Sueldo Base, Horas Extras (50% y 100%), Comisiones, Bonos, Colación y Movilización.
* **Descuentos Legales:**
    * AFP (Tasas actualizadas por administradora).
    * Salud (Fonasa 7% o Isapre pactado).
    * Seguro de Cesantía (Trabajador y Empleador).
    * Impuesto de Segunda Categoría.
* **Aportes Patronales:** Cálculo de SIS, Mutual (Ley 16.744 + SANNA) y Seguro de Cesantía empleador.
* **Persistencia de Datos:** Utiliza `localStorage` para guardar el progreso del usuario automáticamente en el navegador.
* **Modo Impresión:** Genera una vista limpia tipo "Liquidación de Sueldo" lista para imprimir o guardar como PDF.

## 🛠️ Tecnologías

* **HTML5 & CSS3**
* **Bootstrap 5.3** (Diseño responsivo y componentes UI).
* **JavaScript (Vanilla):** Lógica de cálculo, manipulación del DOM y manejo de LocalStorage sin frameworks pesados.
* **Iconos:** Bootstrap Icons.

## 📋 Uso

Basta con clonar el repositorio y abrir el archivo `index.html` en cualquier navegador moderno. No requiere instalación de servidores ni dependencias de Node.js.

## ⚠️ Disclaimer

Los cálculos entregados por esta herramienta son estimativos y de carácter ilustrativo para facilitar la gestión de emprendedores y microempresas. Se recomienda siempre validar con un contador auditor.
