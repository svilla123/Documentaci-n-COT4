# Manual de usuario del cotizador

## 1. Descripción de la plataforma

La plataforma permite solicitar cotizaciones de oligonucleótidos y otros productos de síntesis mediante una plantilla de Excel. El usuario completa los datos de la solicitud, carga el archivo en el portal y lo envía para su procesamiento.

Los productos compatibles con la cotización automática se procesan mediante el sistema. Algunos productos requieren una cotización manual por parte del equipo de ventas; estas excepciones se describen en la sección 3.5.

Para evitar errores o retrasos, ingrese información completa y precisa en los campos que correspondan a su solicitud.

## 2. Guía de campos

### 2.1. Datos del solicitante

| Campo | Descripción | Ejemplo |
| --- | --- | --- |
| Solicitante | Nombre completo de la persona que solicita la cotización o el producto. | Ivonne Zavala |
| Organización | Empresa, universidad, laboratorio o institución a la que pertenece el solicitante. | ITESI |
| Departamento/Laboratorio | Área de la organización a la que pertenece el solicitante. | Laboratorio de diversidad e interacción microbiana |


### 2.2. Datos de envío

| Campo | Descripción |
| --- | --- |
| Destinatario | Nombre completo de la persona que recibirá físicamente el producto. |
| Organización | Institución o empresa donde se entregará el producto. |
| Calle, número, colonia y referencias adicionales sobre el domicilio | Dirección completa de entrega. Incluya referencias que faciliten la localización del lugar. |
| Ciudad y estado | Ciudad y entidad federativa correspondientes al domicilio de entrega. |
| Código postal | Código postal del domicilio de entrega. |
| Teléfono de contacto | Número de contacto de la persona que recibirá el producto. Para números nacionales de México, capture los 10 dígitos. |
| E-MAIL para recepción del certificado de análisis | Correo electrónico vigente donde se recibirá el certificado de análisis. |

**Ejemplo de domicilio:** Carretera Irapuato-Silao, kilómetro 12.5, Comunidad El Copal, C.P. 36821, Irapuato, Guanajuato. Edificio F, Laboratorio LDIM.

### 2.3. Datos de facturación

| Campo | Descripción |
| --- | --- |
| Razón social | Nombre de la empresa o nombre completo de la persona física, tal como aparece en su registro fiscal ante el SAT. |
| RFC | Registro Federal de Contribuyentes con homoclave: 12 caracteres para personas morales y 13 para personas físicas. |
| Dirección fiscal | Domicilio registrado ante el SAT. Incluya calle, número exterior e interior cuando corresponda, colonia, municipio o alcaldía, estado y código postal. |
| Régimen fiscal | Clave y descripción del régimen bajo el cual tributa el receptor de la factura. Ejemplo: 601 - General de Ley Personas Morales. |
| Uso del CFDI | Uso fiscal que se dará al comprobante. Ejemplos: G01 - Adquisición de mercancías, G03 - Gastos en general o S01 - Sin efectos fiscales. Seleccione la opción que corresponda a su situación fiscal. |
| Método de pago | Indica si el pago se realiza en una sola exhibición o en parcialidades o de forma diferida. Opciones: PUE - Pago en una sola exhibición; PPD - Pago en parcialidades o diferido. |
| Forma de pago | Medio utilizado para realizar el pago. Ejemplos: transferencia electrónica de fondos, efectivo o cheque nominativo. Seleccione la opción correspondiente del catálogo disponible. |
| E-MAIL para recepción de factura | Correo electrónico destinado a recibir la factura. |

### 2.4. Producto y características

| Campo | Descripción |
| --- | --- |
| Producto | Tipo de producto de síntesis solicitado. Seleccione una opción de la lista desplegable. |
| Cantidad | Número de unidades solicitadas del producto. |
| Nombre de la secuencia | Nombre o identificador que permita reconocer cada producto. |
| Secuencia 5' a 3' | Secuencia de nucleótidos escrita en dirección 5' a 3'. Para ADN se utilizan A, T, C y G; para ARN, A, U, C y G. Utilice únicamente los símbolos admitidos por la plataforma para el producto seleccionado. |
| Escala | Escala de síntesis seleccionada, expresada en nmol o µmol. No debe interpretarse por sí sola como el rendimiento final entregado. |
| Purificación | Procedimiento de purificación solicitado, según las opciones disponibles para el producto. |
| Longitud | Número de nucleótidos de la secuencia. El campo se completa automáticamente según el flujo correspondiente. |
| Modificaciones | Grupos químicos o moléculas adicionales incorporados en el extremo 5', el extremo 3' o posiciones internas, según el producto y las opciones disponibles. Ejemplos: FAM, biotina y Cy5. |

**Códigos degenerados:** cuando la secuencia contenga posiciones ambiguas, utilice los códigos admitidos por la plantilla, como N, K o R. Ejemplo de una secuencia de ADN con un código degenerado: `AGTGATCGATNCGTAGCTAGCTAGT`.

**Productos disponibles en la plantilla descrita:**

| Producto | Referencia |
| --- | --- |
| PRIMER STD | OLIGO ESTÁNDAR |
| PRIMER C/MOD | OLIGO MODIFICADO |
| SONDA STARQ™ | SONDA |
| SONDA STARQ™ PLUS | SONDA |
| SONDA STARQ™ PRIME | SONDA CON QUENCHER INTERNO |
| SONDA STARQ™ POLARIS | SONDA CON MGB |
| T4BRICK™ | Producto sujeto a cotización manual. |
| T4GENE™ | Producto sujeto a cotización manual. |
| RNA | Producto de ARN sujeto a cotización manual. |

## 3. Procedimiento para solicitar una cotización

### 3.1. Descargar la plantilla

Ingrese al portal y seleccione **“Descargar plantilla”**. Abra el archivo descargado en Excel para completar los apartados de datos del solicitante, envío, facturación y características de los productos.

![Portal del cotizador y opción para descargar la plantilla](https://github.com/user-attachments/assets/3960cd46-1c4b-4145-9d6b-7355545f3fde)

![Vista general del formato de solicitud](https://github.com/user-attachments/assets/9f1200d8-7a70-4a5b-b367-47c504f2cc17)

La plantilla contiene campos de captura manual, listas desplegables y campos automáticos. Complete cada uno según las indicaciones siguientes.

### 3.2. Completar los datos del solicitante y de envío

**Datos del solicitante**

![Campos del solicitante, organización y departamento o laboratorio](https://github.com/user-attachments/assets/01a8fa39-6746-4248-b3dc-cfd94cb6957b)

Capture manualmente los siguientes datos obligatorios:

- Nombre del solicitante.
- Organización.
- Departamento/Laboratorio.

> **Nota:** El campo **COTIZACIÓN NO** será completado por nuestro equipo de ventas. Deje este campo en blanco.

**Datos de envío**

![Apartado de datos de envío de la plantilla](https://github.com/user-attachments/assets/354781de-5128-4ffd-9cdc-971eb0e23008)

Complete manualmente los campos de **Destinatario**, **Organización**, **Calle, número, colonia y referencias adicionales sobre el domicilio**, **Ciudad y estado**, **Código postal**, **Teléfono de contacto** y **E-MAIL para recepción del certificado de análisis**.

Revise que la dirección permita localizar el lugar de entrega y que los datos de contacto sean correctos.


### 3.3. Completar los datos de facturación

![Apartado de datos de facturación de la plantilla](https://github.com/user-attachments/assets/2149fb8e-1042-4821-8ab6-78e57c65843a)

Capture manualmente **Razón social**, **RFC**, **Dirección fiscal** y **E-MAIL para recepción de factura**.

Seleccione **Régimen fiscal**, **Uso del CFDI**, **Forma de pago** y **Método de pago** mediante las listas desplegables. Verifique que los datos correspondan al receptor de la factura.

### 3.4. Especificar el producto y sus características

![Tabla de productos y características de las secuencias](https://github.com/user-attachments/assets/564d329b-d559-4151-bcb0-c84b50436764)

Complete cada fila con los datos del producto solicitado. Para T4BRICK™, T4GENE™ y RNA, aplique las instrucciones especiales de la sección 3.5.

| Campo | Tipo de captura | Instrucción |
| --- | --- | --- |
| Producto | Lista desplegable | Seleccione PRIMER STD, SONDA STARQ™, SONDA STARQ™ PLUS, SONDA STARQ™ PRIME, SONDA STARQ™ POLARIS, PRIMER C/MOD, T4BRICK™, T4GENE™ o RNA. |
| Cantidad | Manual | Ingrese la cantidad solicitada como un número entero mayor que cero. |
| Nombre de la secuencia | Manual | Asigne un nombre que permita identificar el producto. |
| Secuencia 5' a 3' | Manual | Ingrese la secuencia en dirección 5' a 3', utilizando los símbolos admitidos. |
| Escala | Lista desplegable | Seleccione la escala requerida entre las opciones disponibles: 25 nmol, 50 nmol, 100 nmol, 200 nmol o 1 µmol. |
| Purificación | Lista desplegable | Seleccione la opción correspondiente: Desalado, Cartucho, HPLC, PAGE o High Pure. |
| Longitud | Automática | El número de bases se completa automáticamente; no lo capture manualmente. |
| Modificaciones extremo 5' | Lista desplegable | Seleccione la modificación requerida. Deje el campo en blanco si no aplica. |
| Modificaciones extremo 3' | Lista desplegable | Seleccione la modificación requerida. Deje el campo en blanco si no aplica. |

**Opciones de modificación en el extremo 5'**

- Fluoróforos: 5' FAM, 5'HEX, 5'TET, 5'ROX, 5'CY3, 5'CY5, 5'QUASAR 570, 5'QUASAR 670, 5'QUASAR 705, 5' CAL FLUOR ORANGE 560, 5'CAL FLUOR RED 610, 5' CAL FLUOR GOLD 540, 5'TEXAS RED y 5'TAMRA.
- Otras opciones del catálogo: 5'MIKE, 5'Biotina, 5'Fosfato, 5'Tiol C6, 5' Amino C6, 5'SPACER C3 y 5'Spacer C6.

**Opciones de modificación en el extremo 3' y combinaciones disponibles**

- 3'BHQ1, 3'BHQ2, 3'BHQ3, 3'MGB/BHQ1, 3'MGB/BHQ2, 3' BHQ1/NOVA, 3'BBQ, 3'TAMRA y 3'6-FAM.
- 3'Biotina, 3'Fosfato, 3'Amino C3, 3'SPACER C3, 3'SPACER C6 y 3'Tiol C6.
- T(BHQ1)/3'BHQ1, T(BHQ2)/3'BHQ1, T(BHQ1)/3'SPACER C3, T(BHQ1)/3'SPACER C6, T(BHQ1)/3'BHQ2, T(BHQ2)/3'BHQ2, T(BHQ2)/3'SPACER C3 y T(BHQ2)/3'SPACER C6.

Seleccione las denominaciones tal como aparecen en la lista desplegable. Las combinaciones que incluyen modificaciones internas deben solicitarse mediante la opción correspondiente del catálogo.

### 3.5. Productos sujetos a cotización manual

Los productos **T4BRICK™**, **T4GENE™** y **RNA** requieren una cotización manual y específica por parte del equipo de ventas.

Para estos productos, únicamente será necesario completar los siguientes campos del apartado de producto:

- **Producto:** seleccionar una opción del menú desplegable.
- **Nombre de la secuencia:** ingresar manualmente.
- **Secuencia 5' a 3':** ingresar manualmente.

> **¡Importante!** Para estos productos, todos los demás campos serán establecidos automáticamente por la plataforma como “No”. Esto permitirá realizar correctamente la identificación y validación de la solicitud con la base de datos interna (BLAST).

### 3.6. Guardar, cargar y enviar la solicitud

1. Revise los datos capturados y complete los campos aplicables al producto seleccionado.
2. Guarde el archivo de Excel.
3. En el portal, seleccione **“Cargar cotización”** y elija el archivo guardado.
4. Seleccione **“Enviar cotización”** para iniciar el procesamiento.

## 4. Comportamiento de la interfaz

El fondo de la interfaz muestra las letras **A**, **T**, **C** y **G** mediante una animación lenta. Durante el envío, estos elementos funcionan como indicadores visuales de actividad.

### 4.1. Procesamiento en curso

Al iniciar el procesamiento de la solicitud:

- La animación de las letras aumenta de velocidad.
- El indicador inferior cambia de **“READY”** a **“Processing”**.

![Interfaz durante el procesamiento de una solicitud](https://github.com/user-attachments/assets/7e26eb9b-66d8-40dd-8a54-8a1299fb5639)

### 4.2. Mensajes de la interfaz

Si el archivo se carga correctamente, aparece el mensaje **“Archivo [Nombre del archivo] cargado correctamente”** en la parte superior derecha.

![Mensaje de confirmación de carga del archivo](https://github.com/user-attachments/assets/d076bcba-7455-4060-beea-a0cc64b589e5)

La confirmación de carga indica que el archivo fue recibido. No debe interpretarse por sí sola como confirmación de compra ni de cotización finalizada.

Si ocurre un error durante la carga o el procesamiento, aparece un aviso amarillo con su descripción y, cuando corresponda, el nombre del error.

Al finalizar el proceso, la interfaz regresa a su estado inicial y la animación recupera su velocidad lenta. Revise el mensaje mostrado para conocer el resultado.

## 5. Qué hacer si aparece un error

Un aviso de error durante el envío indica que la carga o el procesamiento no se completaron correctamente. Lea el mensaje antes de volver a enviar el archivo.

### 5.1. Revisar los datos enviados

Si el mensaje señala información incompleta o incorrecta:

1. Abra el archivo de Excel que envió.
2. Revise el campo o la fila indicados en el mensaje, si se especifican.
3. Compruebe los datos obligatorios y las opciones seleccionadas en los desplegables.
4. Verifique la secuencia y las características del producto conforme a esta guía.
5. Corrija la información, guarde el archivo y vuelva a cargarlo y enviarlo.

### 5.2. Solicitar soporte

Si el error persiste o el mensaje no permite identificar la causa, contacte al equipo de soporte:

- **ventas@t4oligo.com**
- **biodata@itrasig.org**

Incluya el texto del error o una captura de pantalla, el nombre del archivo enviado y el ID de operación, si dispone de él. No todos los errores se deben al llenado de la plantilla; el mensaje debe orientar la revisión.

## 6. Notificaciones por correo electrónico

Después de enviar la solicitud, revise las notificaciones relacionadas con su procesamiento. A continuación se describen los tres tipos de comunicación contemplados en esta guía. Su recepción depende del estado de la solicitud; no representan necesariamente tres resultados excluyentes.

### 6.1. Ticket de compra: desglose de la solicitud

El documento denominado **“ticket de compra”** confirma el procesamiento de la solicitud y presenta el desglose de costos de los productos cotizados. Su recepción, por sí sola, no acredita que el pago se haya realizado.

![Ejemplo del ticket con el desglose de costos](https://github.com/user-attachments/assets/bf18f378-d7ab-43d4-a54c-cdd1a7df7e56)

| Dato | Descripción |
| --- | --- |
| ID de operación | Identificador único que permite dar seguimiento a la solicitud. |
| Costo de secuencia | Nombre de la secuencia, secuencia neta, número total de bases, costo por base y subtotal. |
| Costo de purificación | Tipo de purificación, escala y costo correspondiente. |
| Modificadores internos, 5', 3' y adicionales | Modificaciones incluidas y sus costos. |
| Bases degeneradas | Presencia de códigos degenerados, observaciones técnicas y cargos adicionales cuando correspondan. |
| Total | Importe indicado para los conceptos cotizados. |

### 6.2. Cotización e instrucciones de pago

![Ejemplo del correo de cotización e instrucciones de pago](https://github.com/user-attachments/assets/0daf02f5-73ca-4d4a-9145-843f8e0b25ad)

Este correo incluye los detalles de la cotización y la información para proceder con el pago:

- **Fecha de registro:** fecha en que se registró la solicitud.
- **Hora sugerida de pago:** referencia indicada en el correo para realizar el pago. Revise las condiciones de vigencia de la cotización; si el mensaje establece una fecha u hora límite, respete ese plazo para evitar la necesidad de solicitar una actualización.
- **Fecha estimada de envío:** fecha prevista para despachar el producto. No equivale necesariamente a la fecha de entrega en el domicilio.

El correo adjunta un archivo de Excel con el desglose de la cotización, los precios unitarios y totales, la opción de pago seleccionada y los datos bancarios correspondientes, como número de cuenta y CLABE cuando aplique.

### 6.3. Notificación de secuencias en revisión: sector salud

**¿Qué es BLAST?**

BLAST (*Basic Local Alignment Search Tool*) es una herramienta bioinformática que compara secuencias e identifica regiones de similitud. En este proceso, las secuencias enviadas se comparan con la base de datos utilizada por la plataforma.

Cuando se identifica una coincidencia que requiere revisión, el correo puede incluir el nombre de la secuencia, su identificador interno, las métricas del alineamiento y un archivo con el resultado del análisis.

**Cómo interpretar las métricas**

| Métrica | Significado |
| --- | --- |
| Query length | Longitud de la secuencia consultada, expresada en nucleótidos. |
| Identidad | Porcentaje de posiciones idénticas dentro del alineamiento. |
| Cobertura de la consulta | Porcentaje de la secuencia consultada cubierto por el alineamiento. No es equivalente al porcentaje de identidad. |
| Expect (E) value | Número esperado de coincidencias con una puntuación igual o mayor que podrían obtenerse por azar en una búsqueda de esas características. |
| Bit score | Puntuación normalizada del alineamiento; los valores mayores representan una puntuación más alta. |

**Ejemplo presentado en la guía**

![Ejemplo de notificación con un alineamiento de secuencia relacionado con HBV](https://github.com/user-attachments/assets/ffe95c73-844d-4472-b4d6-1363aab36230)

El ejemplo describe una coincidencia con una secuencia de referencia relacionada con HBV e incluye los siguientes valores:

- **Query length:** 20 nucleótidos.
- **Identidad:** 95 %, correspondiente a 19 coincidencias en un alineamiento de 20 posiciones.
- **E-value:** `5e-06`, equivalente a 0.000005 coincidencias esperadas por azar con una puntuación igual o mayor bajo las condiciones de la búsqueda.
- **Bit score:** 37.4 bits.

La interpretación requiere considerar conjuntamente la identidad, la cobertura, la longitud de la secuencia y la base de datos consultada. Una coincidencia no constituye por sí sola una identificación concluyente del origen de la secuencia ni un diagnóstico.

**¿Qué debe hacer el usuario?**

Si recibe un correo con el asunto **“secuencia_detectadas_sector_salud”**, la solicitud requiere revisión por parte del área técnica de Síntesis.

El equipo evaluará la viabilidad de la síntesis y determinará las acciones correspondientes. Posteriormente, se pondrá en contacto con el cliente. Esta notificación corresponde a una revisión técnica y no implica, por sí misma, que la plantilla se haya llenado incorrectamente.

## 7. Contacto

Para resolver dudas sobre el llenado, la cotización o los mensajes de la plataforma, escriba a:

- **Ventas:** ventas@t4oligo.com
- **Soporte:** biodata@itrasig.org

Si su solicitud ya cuenta con un **ID de operación**, inclúyalo en el mensaje para facilitar el seguimiento.
