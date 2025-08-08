# 📦 Power Apps – Northwind Traders Canvas App

## 👩‍💻 Autor
**Michelle Molano**  
Estudiante de Ingeniería de Software – Uniempresarial  

---

## 📌 Descripción del Proyecto
Este proyecto corresponde al **Taller 1.1 – Creación de Aplicación Canvas con Power Apps y Northwind Traders**.  
Se desarrolló una **aplicación de lienzo (Canvas App)** conectada a **Dataverse**, utilizando la solución **Northwind Traders** para simular un escenario empresarial real de gestión de pedidos.  

La app cuenta con tres componentes principales:
1. **Galería de Pedidos** → Lista todos los pedidos desde Dataverse.
2. **Formulario de Resumen** → Muestra información general de un pedido seleccionado.
3. **Galería de Detalles** → Despliega los productos y cantidades asociados a ese pedido.

---

## 🎯 Objetivo del Taller
- Instalar y configurar la solución **Northwind Traders** en un entorno de desarrollo de Power Apps.
- Construir paso a paso una app Canvas funcional con integración a Dataverse.
- Implementar navegación fluida y componentes interactivos para mostrar pedidos y detalles.
- Practicar el flujo de creación, exportación y documentación de aplicaciones en Power Apps.

---

## 🛠️ Proceso de Desarrollo

### **1️⃣ Instalación de Northwind Traders**
- Ingresé a [make.powerapps.com](https://make.powerapps.com).
- Seleccioné mi entorno de desarrollo en Power Platform.
- Instalé la solución **Northwind Traders** siguiendo la guía oficial.
- Confirmé que las tablas y datos de ejemplo aparecieran en Dataverse.

📸 **Evidencia** → Captura de pantalla mostrando la solución instalada.

---

### **2️⃣ Creación de la Galería de Pedidos**
- Abrí un nuevo lienzo (Canvas App).
- Agregué una **galería vertical** conectada a la tabla de pedidos (`Orders`) en Dataverse.
- Configuré el diseño para mostrar ID del pedido, fecha, cliente y estado.

📸 **Evidencia** → Captura de la galería funcionando y mostrando datos.

---

### **3️⃣ Agregar Formulario de Resumen**
- Inserté un **formulario de visualización** vinculado al registro seleccionado en la galería.
- Mostré campos clave: ID de pedido, fecha, nombre del cliente y total.

📸 **Evidencia** → Captura del formulario mostrando la información del pedido seleccionado.

---

### **4️⃣ Agregar Galería de Detalles**
- Añadí una **galería secundaria** conectada a la relación `Order_Details` de Dataverse.
- Configuré columnas para producto, cantidad y precio unitario.
- Ajusté la navegación para que, al seleccionar un pedido en la galería principal, se actualicen el formulario y la galería de detalles.

📸 **Evidencia** → Captura de la galería de detalles mostrando los productos.

---

## 📤 Entregables
- 📷 **Capturas** de cada componente (galería, formulario y detalles).
- 📦 **Archivo `.msapp`** exportado de Power Apps.
- 🎥 **Video (3 min)** explicando:
  1. Instalación de Northwind Traders.
  2. Creación de la galería de pedidos.
  3. Implementación del formulario de resumen.
  4. Agregado de la galería de detalles.
  5. Lo que aprendí en el taller.

---

## 📚 Aprendizaje y Conclusiones
Este taller me permitió:
- Conocer el flujo completo de instalación de una solución empresarial en Power Apps.
- Comprender cómo consumir datos en tiempo real desde Dataverse.
- Configurar correctamente componentes visuales y sus relaciones.
- Mejorar la navegación y la presentación de información en una app sin código.

Con esta práctica confirmé que **Power Apps es una herramienta muy potente para desarrollar aplicaciones empresariales rápidamente** y que, con una buena estructura de datos en Dataverse, se puede crear una solución funcional en poco tiempo.

---

## 📄 Licencia
Proyecto académico desarrollado únicamente con fines educativos.
