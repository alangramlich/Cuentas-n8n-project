<img src="imagenes/qr.png" alt="QR" width="500">

# Introducción

**Cuentas** es una herramienta pensada para facilitar la contabilidad del hogar.  
Permite al usuario categorizar fácilmente sus gastos para luego analizarlos.  
Utiliza como interfaz un **chat de Telegram**, al que se pueden enviar imágenes, audio o texto para informar de gastos o ingresos, y estos se reflejan automáticamente en un **archivo de Google Sheets personal**.

**APIs utilizadas:** Mistral OCR, OpenAI LLM, Google Drive, Google Sheets, Telegram.

<img src="imagenes/ticket1.jpg" alt="Ticket original" width="500">

<img src="imagenes/rta_ticket1.png" alt="Respuesta del bot" width="500">

<img src="imagenes/sheets_ticket1.png" alt="Registro en Google Sheets" width="500">

**Las categorías (en el ejemplo, "alimentación") son definidas en la hoja "mis categorías" del Sheets donde se suben los datos.  
La siguiente imagen muestra las categorías predefinidas:**

<img src="imagenes/mis_categorias_predefinidas.png" alt="Categorías predefinidas" width="500">

| **Categoría**         | **Descripción**                                                                                                                                                      | **Gasto/Ingreso** |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Alimentación           | Compras de supermercado, verdulería, carnicería, panadería, bebidas y snacks.                                                                                        | Gasto             |
| Vivienda               | Alquiler, expensas, impuestos, servicios (agua, luz, gas, internet).                                                                                                 | Gasto             |
| Transporte             | Nafta, pasajes de colectivo/tren/subte, peajes, mantenimiento de vehículos.                                                                                          | Gasto             |
| Salud                  | Medicamentos, consultas médicas, estudios, obra social o prepaga.                                                                                                   | Gasto             |
| Educación              | Colegios, universidades, cursos, útiles escolares, libros, idiomas (Inglés, Alemán, Francés, etc.).                                                                  | Gasto             |
| Ocio y Recreación      | Salidas a comer, cine, streaming, deportes, hobbies, entretenimiento en general.                                                                                    | Gasto             |
| Indumentaria           | Ropa, calzado y accesorios.                                                                                                   | Gasto             |
| Tecnología             | Celulares, electrodomésticos, computadoras, mantenimiento y servicios digitales.                                              | Gasto             |
| Seguros                | Seguro de auto, hogar, vida, salud.                                                                                           | Gasto             |
| Ingresos               | Dinero recibido por salario, pagos, cobros o transferencias (“Me pagaron…”, “Cobré…”).                                        | Ingreso           |
| Ahorro                 | Dinero reservado durante el mes en curso.                                                                                    | Gasto             |

---

**Pero... ¿y si quiero categorizar más a fondo mis alimentos?**

<img src="imagenes/rta_ticket2.png" alt="Respuesta con categorías personalizadas" width="500">

**Simplemente basta con modificar la hoja donde estas categorías están definidas.**

<img src="imagenes/modificar_categorias.png" alt="Modificar categorías" width="500">

| **Categoría**        | **Descripción**                                                                                                                                                     | **Gasto/Ingreso** |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| Alimentación          | Alimentos en general.                                                                                                                                               | Gasto             |
| Vivienda              | Alquiler, expensas, impuestos, servicios (agua, luz, gas, internet).                                                                                                | Gasto             |
| Transporte            | Nafta, pasajes, peajes, mantenimiento de vehículos.                                                                                                                 | Gasto             |
| Salud                 | Medicamentos, consultas médicas, estudios, obra social o prepaga.                                                                                                   | Gasto             |
| Educación             | Colegios, universidades, cursos, libros, idiomas.                                                                             | Gasto             |
| Ocio y Recreación     | Salidas, cine, streaming, deportes, hobbies, entretenimiento.                                                                  | Gasto             |
| Indumentaria          | Ropa, calzado y accesorios.                                                                                                   | Gasto             |
| Tecnología            | Celulares, electrodomésticos, computadoras, servicios digitales.                                                              | Gasto             |
| Seguros               | Seguro de auto, hogar, vida, salud.                                                                                           | Gasto             |
| Ingresos              | Dinero recibido por salario, pagos, cobros o transferencias.                                                                  | Ingreso           |
| Ahorro                | Dinero reservado durante el mes en curso.                                                                                    | Gasto             |
| Lácteos               | Leche, yogures, quesos, manteca, crema, postres lácteos y derivados.                                                         | Gasto             |
| Carnes                | Carne vacuna, pollo, cerdo, pescado y embutidos.                                                                             | Gasto             |
| Cereales              | Arroz, fideos, harinas, pan, galletitas, cereales para desayuno y panificación.                                              | Gasto             |

---

**Y Cuentas ya es capaz de adaptarse a nuestras categorías personalizadas.**

<img src="imagenes/rta_ticket2_cat_modificadas.png" alt="Categorías personalizadas en acción" width="500">

**Cuentas también lleva el control de cuánto dinero nos queda para el mes, y podemos consultarlo cuando lo necesitemos.**

<img src="imagenes/restante.png" alt="Saldo restante" width="500">

---

# Registro automático

**Cuentas** permite el registro automático de nuevos usuarios.  
Para comenzar a usarlo, solo hay que indicarle un correo electrónico.

<img src="imagenes/registro.png" alt="Registro de usuario" width="500">

<img src="imagenes/sheet_recibido.jpg" alt="Hoja generada automáticamente" width="500">

---

Te invito a comenzar a usarlo o descargar la plantilla (presente en este repositorio) y evaluarlo por tu cuenta.  
> **Nota:** El registro puede fallar ocasionalmente. Contactarse a alangramlichklein@gmail.com por cualquier inconveniente.

