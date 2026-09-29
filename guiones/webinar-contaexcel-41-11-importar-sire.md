# GUION WEBINAR — CONTAEXCEL 41.11
## "Importar compras y ventas desde la propuesta del SIRE — ContaExcel"

**Duración:** 30 minutos (4:00 – 4:30 p.m.) | **Plataforma:** Zoom, sin cámara
**Expositor:** Axel Barzola, programador del sistema ContaExcel
**Apoyo:** Carlos responde consultas por el chat | **Cierre:** pase a Ingrid (promociones)
**Público:** contadores

> **Supuestos:**
> - Mantuve el formato de siempre y **sin preguntas al público**.
> - **Omití la instalación** (descargar, extraer, desbloquear, clave), como pediste.
> - **Sí dejé, en 2 minutos, la actualización de empresas** (UTILITARIOS → ACTUALIZAR VERSIÓN). No es instalación, y para quien viene de la 41.6 es obligatoria: si no la hacen, llaman a soporte. Si prefieres sacarla, ese bloque se borra entero y el tiempo pasa al Tema 3.
> - **Cambié el orden del video en una parte:** ahí se corrigen los datos al final, después de guardar. En el webinar se corrigen **antes** de autocompletar y guardar, que es el orden correcto para trabajar.

---

## 🎯 EL HILO CONDUCTOR DE HOY

La novedad de la 41.11 es una sola, pero trae consigo un cambio de hábito. El mensaje del día es este: **ahora la propuesta del SIRE entra directo al sistema, y justamente por eso hay que revisarla antes.**

El recorrido se cuenta en tres pasos, como un proceso de trabajo:

1. **Diagnosticar:** ver qué trae la propuesta, sin tocar nada.
2. **Importar:** traerla al sistema y dejar que la **Revisión SIRE** marque lo que no cuadra.
3. **Revisar, corregir y guardar:** limpiar lo observado y seguir con la importación masiva de siempre (CUO, autocompletar, guardar).

Así la función no se queda en "un botón nuevo". Se convierte en **un método de trabajo nuevo**. Y hay un beneficio comercial de paso: la función ahorra horas de digitación, algo que cualquier contador entiende al toque, y encima muestra que el sistema **cuida** al usuario (valida y avisa). Esa combinación vende sola.

---

## 🏆 LOS PUNTOS DE MAYOR VALOR

Si de todo el webinar solo se llevan esto, ya valió la pena:

1. **Se acabó copiar columna por columna.** La propuesta del SIRE (TXT o CSV) se importa directo, **incluso comprimida**.
2. **Diagnosticar primero.** Da la cantidad de comprobantes y los totales **sin importar nada**, para cuadrar antes de subir.
3. **El periodo del sistema tiene que ser el mismo del archivo.** Si no coinciden, el sistema frena y **no modifica nada**.
4. **La propuesta del SIRE no viene validada.** Trae incoherencias, sobre todo en **compras**: fechas de vencimiento anteriores a la emisión, IGV que no cuadra con ninguna tasa.
5. **La Revisión SIRE las marca.** Se corrigen en la estructura de importación **antes** de autocompletar y guardar.
6. **Después, el proceso de siempre:** CUO, autocompletar columnas y guardar en base de datos.
7. **Si vienen de la 41.6:** UTILITARIOS → ACTUALIZAR VERSIÓN, **en cada empresa**.

---

## ⚠️ CHECKLIST ANTES DE EMPEZAR

1. **Ten la 41.11 instalada y la empresa de demo ya actualizada.** La actualización de empresas solo se muestra con una. No instales nada en vivo.
2. **Ten las propuestas descargadas en una carpeta ordenada** (ej. `Propuestas SIRE`):
   - Compras julio y Ventas julio, **comprimidas**, tal como bajan del SIRE. Así demuestras que no hace falta descomprimir.
   - **Una propuesta de otro mes** (ej. enero) para la demo del candado de periodo.
3. **Ten una captura del botón EXPORTAR del SIRE** (con las opciones TXT y CSV). **No entres a SUNAT Operaciones en Línea en vivo:** es riesgo de mostrar credenciales y depender de que SUNAT responda.
4. **La empresa de demo tiene que estar en JULIO 2026** en DATOS GENERALES. Si está en otro mes, la importación se cae en vivo.
5. **Ensaya la importación de compras antes del webinar** y anota qué filas salen observadas y por qué. En el video son la **16 y la 17** (fecha de vencimiento) y la **18** (IGV). Si usas otros archivos, las observaciones van a cambiar y el guion tiene que acompañar.
6. **Saca una copia de la base de datos de demo** antes de ensayar, para dejarla limpia para el webinar. Y ten **otra empresa con la importación ya hecha** como plan B.
7. **Ten el cálculo de la fila 18 a la mano:** total 110.53 → a la tasa del 18% la base sería **93.67** y el IGV **16.86**, no 97.10 y 13.43 como viene en la propuesta.
8. **Cuidado con los datos en pantalla:** la propuesta trae RUC y razones sociales reales de proveedores y clientes. Usa la propuesta de una empresa que se pueda mostrar.
9. **Confirma con Carlos:**
   - Qué recomendar con el comprobante de IGV descuadrado: declararlo tal cual o corregirlo.
   - Las tasas que valida el sistema (18%, 10% y 10.5%) y a qué casos corresponden, por si preguntan.
   - Si la 41.11 ya les llegó a todos los clientes o sigue en envío.
10. **Verifica los nombres exactos de los botones** en tu pantalla (REVISIÓN SIRE, VER COLUMNAS RECONOCIDAS, GUARDAR DE TODOS MODOS, AUTOCOMPLETAR COLUMNAS, GUARDAR EN BASE DE DATOS). El guion los toma del video.

**Técnico:**
- Comparte **solo la ventana de Excel**. Hoy también vas a mostrar el Explorador de Windows (la carpeta de propuestas): tenlo ordenado y sin archivos personales a la vista.
- Zoom de Excel al **130–150%**. Hoy se leen muchas celdas y fechas: si no se ven, el mensaje se pierde.
- Cierra notificaciones. Modo "No molestar".
- Audífonos con micrófono. Vaso de agua.

**Regla de oro sin cámara:** nunca hagas clic en silencio. Hoy hay varias ventanas de aviso seguidas: **léelas en voz alta** antes de aceptar. Son parte del mensaje.

---

## MAPA DE TIEMPOS

| Bloque | Tiempo | Duración |
|---|---|---|
| Bienvenida y agenda | 4:00 – 4:03 | 3 min |
| Antes de empezar: actualizar sus empresas | 4:03 – 4:05 | 2 min |
| **Tema 1: La propuesta y el módulo nuevo** | 4:05 – 4:08 | 3 min |
| **Tema 2: Diagnosticar antes de importar** | 4:08 – 4:12 | 4 min |
| **Tema 3: Importar compras y la Revisión SIRE** | 4:12 – 4:20 | 8 min |
| **Tema 4: Corregir, CUO y guardar** | 4:20 – 4:24 | 4 min |
| **Tema 5: Ventas y el candado del periodo** | 4:24 – 4:27 | 3 min |
| Repaso | 4:27 – 4:29 | 2 min |
| Pase a Ingrid | 4:29 – 4:30 | 1 min |

---

## GUION MINUTO A MINUTO

### 🕐 4:00 – 4:03 — BIENVENIDA Y AGENDA

*[Diapositiva simple: título + logo + "Versión 41.11".]*

> Hola, ¿qué tal? Muy buenas tardes a todos y bienvenidos.
>
> Mi nombre es **Axel Barzola** y soy el **programador del sistema ContaExcel de PeruContable**.
>
> Rapidito, confírmenme en el chat si se me escucha bien.
>
> *[**Pausa 6 segundos. Verifica y sigue.**]*
>
> Perfecto, vamos entonces. Y les recuerdo que **Carlos está con nosotros en el chat**, atendiendo consultas en paralelo.
>
> Hoy les vengo a mostrar la novedad de la **versión 41.11** de ContaExcel. Y es una que muchos de ustedes nos venían pidiendo: **ahora pueden importar la propuesta del SIRE directamente al sistema, tanto de compras como de ventas.**
>
> O sea, ya no tienen que estar copiando y pegando columna por columna. Descargan la propuesta, la suben, y listo.
>
> Pero, y esto lo quiero dejar claro desde el inicio, **que entre directo no significa que entre bien.** La propuesta del SIRE trae errores, y hoy les voy a mostrar cuáles, y cómo el sistema se los marca para que los corrijan antes de registrar.
>
> Lo vamos a ver en tres pasos:
>
> **Primero, diagnosticar:** ver qué trae la propuesta, sin importar nada.
>
> **Segundo, importar:** subirla al sistema y ver qué nos observa.
>
> **Y tercero, revisar, corregir y guardar**, para terminar con la importación masiva que ya conocen.
>
> Pero antes, un paso previo que es obligatorio para algunos de ustedes.

*[Cambia a la pantalla del sistema.]*

---

### 🕐 4:03 – 4:05 — ANTES DE EMPEZAR: ACTUALIZAR SUS EMPRESAS

> Todos los que son clientes y tienen la **membresía activa** van a recibir, o ya recibieron, un correo con el asunto **"Actualización del sistema ContaExcel"**. Ahí vienen el archivo, los pasos y un **video tutorial** de la instalación. La instalación es la misma de siempre, así que hoy no la vamos a repetir.
>
> Lo que sí quiero mostrarles es lo que viene **después** de instalar, porque ahí es donde la gente se olvida.
>
> **Si ustedes están pasando de la versión 41.6 a la 41.11, es obligatorio actualizar sus empresas.** Una por una.
>
> *[SISTEMA CONTABLE → RUTA DE BASE DE DATOS.]*
>
> Me voy a la pestaña de **SISTEMA CONTABLE**, módulo **RUTA DE BASE DE DATOS**, y selecciono la primera empresa. Por ejemplo, asesoría. **Abrir.**
>
> Me sale datos generales, le doy **salir**.
>
> *[UTILITARIOS → ACTUALIZAR VERSIÓN.]*
>
> Y ahora me voy a **UTILITARIOS**, a **ACTUALIZAR VERSIÓN**… y le doy **aceptar** a todos los avisos que aparezcan.
>
> Listo, esa empresa ya está actualizada. Y **ese mismo procedimiento lo hacen con cada una de sus empresas.** Ruta de base de datos, abrir, utilitarios, actualizar versión.
>
> Si tienen veinte empresas, son veinte veces. Son dos minutos cada una, y les evita problemas después.
>
> Y si están viniendo de la **41.7**, no es necesario. Pero si igual quieren hacerlo, no pasa nada.

---

### 🕐 4:05 – 4:08 — TEMA 1: LA PROPUESTA Y EL MÓDULO NUEVO

#### 🔹 De dónde sale el archivo

> Vamos entonces a lo nuevo. Primero, **¿qué archivo es el que vamos a importar?**
>
> *[Muestra la captura del botón EXPORTAR del SIRE.]*
>
> Esta es una imagen de dónde aparece siempre la opción en el SIRE, tanto en el registro de compras como en el de ventas electrónico. Tienen este botón de **EXPORTAR**, con dos opciones: **TXT y CSV**.
>
> ¿Cuál descargan? **La que quieran. O las dos.** El sistema lee cualquiera de las dos.
>
> *[Abre el Explorador en la carpeta de propuestas.]*
>
> Acá tengo mis propuestas descargadas: compras y ventas, de enero y de julio. Y fíjense que están **comprimidas**, porque así es como las entrega el SIRE. Si tienen WinRAR, les van a aparecer con ese ícono.
>
> Y acá va la buena noticia: **no es necesario que las descompriman.** El sistema las lee directamente así, comprimidas.

#### 🔹 ⭐ Dónde está el módulo nuevo

> *[Vuelve a Excel → pestaña LIBROS ELECTRÓNICOS.]*
>
> En el sistema, la novedad está en la pestaña de **LIBROS ELECTRÓNICOS**, en este módulo nuevo: **IMPORTAR COMPRAS Y VENTAS**.
>
> *[Abre el módulo.]*
>
> Y acá adentro tenemos **tres opciones**:
>
> - **Importar registro de compras o ventas**, con dos submódulos: **importar compras** e **importar ventas**. Esta es la principal, la que sube la información.
> - **Revisión SIRE**, que ahorita está desactivada. **Se activa sola después de que importemos**, y es donde el sistema nos marca lo que encontró mal.
> - Y **diagnóstico del archivo**, con **diagnosticar compras** y **diagnosticar ventas**.
>
> Y vamos a empezar justamente por la última, porque es la que yo les recomiendo usar primero.

---

### 🕐 4:08 – 4:12 — TEMA 2: DIAGNOSTICAR ANTES DE IMPORTAR

#### 🔹 ⭐ Diagnosticar compras

> El diagnóstico sirve para una sola cosa: **darles un resumen de lo que tiene la propuesta, sin importar nada.** Es como mirar la caja antes de abrirla.
>
> Les comento que estoy trabajando en **julio de 2026**.
>
> *[DIAGNÓSTICO DEL ARCHIVO → DIAGNOSTICAR COMPRAS.]*
>
> Selecciono **diagnóstico del archivo**, **diagnosticar compras**, y me voy a la carpeta de mis propuestas… **julio compras**.
>
> Acá tengo el TXT y el CSV. Puedo seleccionar cualquiera de los dos.
>
> *[Selecciona. Aparece la ventana de diagnóstico.]*
>
> Y acá tenemos el resumen. Miren lo que me dice:
>
> - El **periodo**: julio.
> - La **cantidad de comprobantes** en la propuesta: **7**.
> - Los **totales por columna**: base imponible, IGV, valor de adquisiciones no gravadas e importe total.
> - Y la **cantidad de comprobantes por tipo de documento**: 6 facturas y 1 de tipo de documento 30. Total, 7.
>
> *[Detente un segundo en los totales.]*
>
> ¿Para qué me sirve esto? Para que ustedes **comparen estos totales y esta cantidad con su propio registro** antes de subir nada. Si ustedes tenían 9 facturas y la propuesta trae 7, ya saben que algo falta, y lo saben **antes** de importar.

#### 🔹 Ver columnas reconocidas

> Acá abajo tengo el botón **VER COLUMNAS RECONOCIDAS**.
>
> *[Clic.]*
>
> Esto me indica **qué columnas se van a llenar** cuando haga la importación. Es solo informativo: si le doy aceptar, no hace nada.
>
> Le doy **cerrar**… y cierro el diagnóstico. **No se modificó nada en el sistema.**

#### 🔹 Diagnosticar ventas

> Con ventas es lo mismo.
>
> *[DIAGNOSTICAR VENTAS → carpeta → julio ventas.]*
>
> Diagnosticar ventas, carpeta, **julio ventas**…
>
> Periodo julio, **6 comprobantes**, los totales de base imponible, IGV e importe total, y por tipo de documento: **6 facturas**.
>
> Mismo botón de columnas reconocidas, mismo botón cerrar.
>
> Entonces, resumiendo: **el diagnóstico es su foto previa.** Cantidad de comprobantes, totales, y saben exactamente qué van a meter al sistema.

---

### 🕐 4:12 – 4:20 — TEMA 3: IMPORTAR COMPRAS Y LA REVISIÓN SIRE

#### 🔹 ⚠️ Primero: ¿en qué mes estoy?

> Ahora sí, vamos a importar. Y antes del primer clic, lo más importante: **fíjense en qué mes está trabajando el sistema.**
>
> *[Señala el periodo arriba / DATOS GENERALES.]*
>
> Acá arriba, y en datos generales, veo que estoy en **julio**.
>
> ¿Por qué es importante? Porque **la propuesta que suban tiene que ser del mismo mes en el que está el sistema.** Si tengo la propuesta de agosto y el sistema está en julio, no me la va a dejar subir.
>
> Si me pasa eso, me voy a **datos generales**, cambio el mes a agosto, y recién subo el archivo. Al final se los muestro en vivo.

#### 🔹 Importar compras

> *[IMPORTAR REGISTRO → IMPORTAR COMPRAS → carpeta → julio compras → abrir.]*
>
> Selecciono **importar compras**, me voy a la carpeta, **julio compras**, abrir.
>
> Y me sale el mismo resumen que vimos en el diagnóstico: periodo, cantidad de comprobantes, totales. **Pero ahora tengo un botón adicional: IMPORTAR.**
>
> Si le doy **cancelar**, el proceso termina acá y no pasa nada. Si le doy **importar**, continúa.
>
> *[Clic en IMPORTAR.]*
>
> Le doy importar…

#### 🔹 ⭐ El primer aviso: fechas de vencimiento

> *[Aparece el aviso. Léelo despacio.]*
>
> Y miren lo primero que me dice el sistema. Aviso de **fecha de vencimiento o pago**: *de siete comprobantes importados, dos traen la fecha de vencimiento anterior a la emisión. Revíselos antes de generar el diario.*
>
> Y me dice también que **cada uno queda marcado en la Revisión SIRE**, que es el módulo del medio, el que estaba desactivado.
>
> Le doy **aceptar**, para mostrárselos con detalle.

#### 🔹 ⭐ La Revisión SIRE

> *[Se abre REVISIÓN SIRE.]*
>
> Y acá tenemos la **Revisión SIRE**. Me indica **la fila de cada comprobante** que hay que revisar, y tengo la opción de ir revisando uno por uno.
>
> *[Revisa el comprobante de la fila 16.]*
>
> **Fila 16.** Me muestra el detalle del comprobante, la columna a corregir, y el motivo: *la fecha de vencimiento o pago, 1 de junio de 2026, es anterior a la fecha de emisión.*
>
> La factura se emitió el **7 de julio**… y según el SIRE vence el **1 de junio**. O sea, vence un mes **antes** de existir. Eso no tiene sentido, y el sistema me dice: **corrija la columna F antes de generar el diario.**
>
> *[Fila 17.]*
>
> **Fila 17.** Lo mismo: emitida el **16 de julio**, vence el **15 de julio**. Un día antes de emitirse.
>
> *[Fila 18. Detente acá.]*
>
> Y **fila 18**, que es otro tipo de observación y es la más importante: **el IGV de este comprobante no corresponde a ninguna tasa: ni al 18%, ni al 10%, ni al 10.5%.** Tiene otro porcentaje.
>
> Les hago la cuenta rápida. Este comprobante tiene un total de **110.53**. Viene con base de **97.10** e IGV de **13.43**. Pero si saco el 18% de 97.10, no me da 13.43. **Está mal calculado.**
>
> ¿Y de dónde viene el error? **De la propuesta misma.** Puede ser que el proveedor lo haya emitido mal, o que así esté en el SIRE. El sistema no lo inventa: **lo detecta y se los avisa.**

#### 🔹 ⚠️ El mensaje más importante del día

> Y acá quiero detenerme, porque esto es lo más importante que les voy a decir hoy.
>
> Antes, cuando importaban **copiando columna por columna desde un Excel**, esa información ya estaba **validada por ustedes**: el área contable ya había revisado que los porcentajes de IGV cuadren, que las fechas de emisión y de vencimiento tengan sentido, que el tipo de documento y la serie estén bien.
>
> **La propuesta del SIRE no pasó por esa revisión.** Viene como viene. Y viene, como acaban de ver, con incoherencias.
>
> Si la suben sin revisar, **esa información incorrecta termina en su registro y, eventualmente, en lo que declaran.**
>
> Por eso el consejo: **antes de importar, asegúrense de que lo que van a subir sea correcto.** El sistema les va a ayudar con estos avisos, y **vamos a seguir agregando más validaciones**, pero la revisión final es de ustedes.
>
> Y por cierto: **el método de copiar y pegar sigue funcionando.** No lo quitamos. Esto es una opción más para que ya no tengan que digitar.

#### 🔹 Guardar la importación

> *[Clic en GUARDAR dentro de la Revisión SIRE.]*
>
> Ahora le doy **guardar** para realizar la importación.
>
> *[Aparece el aviso. Léelo.]*
>
> Y fíjense que el sistema insiste: *todavía hay un comprobante con los importes sin cuadrar. Si guarda ahora, pasa al registro con los importes descuadrados.*
>
> Yo voy a darle **guardar de todos modos**, porque lo voy a corregir en el siguiente paso. Pero **noten que el sistema no los deja pasar sin avisar dos veces.**
>
> *[Aparece "Importación terminada". Léelo.]*
>
> **Importación terminada:** registros cargados, **7**, en la hoja **Compras 8.1**. Filas observadas: **1**, la 18, por el porcentaje del IGV. Y me recuerda: **la columna C, el CUO, la debe completar usted.**
>
> Acepto.
>
> *[Muestra la estructura de importación.]*
>
> Y acá ya está: el sistema me mandó toda la información a la **estructura de importación**, que es la misma que ya conocen. Las filas 16, 17 y 18 son las observadas.

---

### 🕐 4:20 – 4:24 — TEMA 4: CORREGIR, CUO Y GUARDAR

#### 🔹 ⭐ Corregir antes de guardar

> Y esta es una de las facilidades del módulo: **pueden corregir acá mismo, en la estructura, antes de autocompletar y guardar.**
>
> *[Ve a la fila 16, columna F.]*
>
> **Las fechas de vencimiento.** Tienen dos opciones: **ponen la fecha correcta**, o **la eliminan**. Muchos de ustedes en compras no usan la fecha de vencimiento; si es su caso y viene mal, la borran y listo. Eso lo decide cada uno según su criterio.
>
> *[Corrige o borra la fecha de las filas 16 y 17.]*
>
> *[Ve a la fila 18.]*
>
> **El comprobante con el IGV mal calculado.** Acá también tienen dos caminos, y los dos se ven en la práctica:
>
> - Hay clientes que prefieren **declararlo tal cual**, porque así lo declaró el proveedor.
> - Y hay otros que prefieren **corregir la base y el IGV a la tasa correcta, sin alterar el importe total.**
>
> Si lo corrigiera, con un total de 110.53 al 18%, la base quedaría en **93.67** y el IGV en **16.86**. Lo cambio acá mismo, en la celda.
>
> *[Corrige, o solo señala, según lo que acordaste con Carlos.]*
>
> ¿Cuál de los dos? Ese es **criterio contable de cada uno**. Si tienen dudas sobre cuál aplicar, **escríbanle a Carlos por el chat**, que ese es su terreno. Yo les muestro que el sistema les deja hacer cualquiera de los dos.

#### 🔹 El proceso de siempre: CUO, autocompletar, guardar

> Una vez corregido, **sigue el proceso de importación masiva que ya conocen.** Nada cambió de acá en adelante.
>
> *[Va a la columna C, primera fila.]*
>
> Primero, el **CUO** en la columna C. La estructura sigue siendo la misma: **el año, 26; el mes, 07; y el correlativo.** Como es mi primer registro del mes, pongo el **CUO 1**, y lo arrastro hacia abajo… hasta el **7**.
>
> *[AUTOCOMPLETAR COLUMNAS → COMPRAS.]*
>
> Luego **autocompletar columnas → compras**.
>
> *[GUARDAR EN BASE DE DATOS → COMPRAS.]*
>
> Y **guardar en base de datos → compras**.
>
> Y listo: las compras de julio, que venían de la propuesta del SIRE, **ya están en el sistema sin haber digitado nada.** Revisadas y corregidas.
>
> Lo que hace este módulo, en resumen, es **reemplazar el copiar y pegar**. Todo lo demás es igual.

---

### 🕐 4:24 – 4:27 — TEMA 5: VENTAS Y EL CANDADO DEL PERIODO

#### 🔹 Importar ventas

> Con **ventas** es exactamente lo mismo.
>
> *[IMPORTAR VENTAS → julio ventas → IMPORTAR.]*
>
> Importar ventas, selecciono mi archivo, **julio ventas**… el resumen… **importar**.
>
> *[Aparece el aviso. Léelo.]*
>
> **Importación terminada sin observaciones.** Registros cargados, **6**, en la hoja **Ventas 14.1**, de la fila 12 a la 17. Y el recordatorio del CUO.
>
> ¿Por qué en ventas no salió ninguna observación? Porque **las ventas las emitimos nosotros mismos.** Las fechas, los datos del comprobante y los montos suelen venir bien.
>
> **Donde hay que estar más atentos es en compras**, porque ahí la información viene de lo que emitieron terceros.
>
> *[CUO → autocompletar → guardar.]*
>
> Y cierro igual: el **CUO**, y como en compras me quedé en el 7, **acá continúo en el 8**. Arrastro, **autocompletar columnas → ventas 14.1**, **guardar datos en ventas 14.1**, procesar. Listo.

#### 🔹 ⭐ El candado del periodo

> Y para cerrar, les muestro lo que les prometí: **qué pasa si intentan subir una propuesta de otro mes.**
>
> *[IMPORTAR COMPRAS → propuesta de ENERO.]*
>
> Estoy en julio, y voy a intentar importar las compras de **enero**…
>
> *[Aparece el aviso. Léelo.]*
>
> *No se puede importar este archivo. El archivo es de un periodo distinto al que está trabajando. Periodo del archivo: enero 2026. Periodo del sistema: julio 2026.*
>
> Y me dice qué hacer: **entrar a datos generales, cambiar el mes y el año a enero 2026, y volver a intentar.**
>
> Y lo más importante: **no se modificó nada.** Ninguna hoja del sistema se tocó. El sistema detecta que la propuesta es de otro mes y corta el proceso.
>
> Con ventas pasa exactamente lo mismo.
>
> Entonces, si les sale este aviso, no se asusten: **es el sistema cuidándolos** de subir un mes en el lugar equivocado.
>
> *[Abre REVISIÓN SIRE.]*
>
> Y si ahora vuelvo a la Revisión SIRE, me dice que **no hay comprobantes observados**. Ya corregimos y terminamos compras. **Así es como tiene que quedar antes de cerrar el mes.**

---

### 🕐 4:27 – 4:29 — REPASO

*[Diapositiva de resumen.]*

> Repasemos lo esencial de la 41.11.
>
> **Antes de empezar:**
>
> **Uno.** Si vienen de la **41.6**, actualicen **cada empresa**: utilitarios, actualizar versión.
>
> **Sobre la propuesta:**
>
> **Dos.** Se descarga del SIRE con **EXPORTAR**, en **TXT o CSV**, y se sube **comprimida**, tal cual baja.
>
> **Tres.** Todo está en **LIBROS ELECTRÓNICOS → IMPORTAR COMPRAS Y VENTAS**.
>
> **Sobre el proceso:**
>
> **Cuatro.** **Diagnostiquen primero.** Cantidad de comprobantes y totales, sin importar nada, para cuadrar con su registro.
>
> **Cinco.** **El periodo del sistema tiene que ser el mismo que el del archivo.** Si no, cambien el mes en datos generales.
>
> **Seis.** La **Revisión SIRE** se activa sola y les marca lo que no cuadra: fechas de vencimiento incoherentes, IGV fuera de tasa.
>
> **Siete.** **Corrijan en la estructura antes de guardar.** Eliminar o corregir la fecha, declarar tal cual o recalcular el IGV: es criterio de cada uno.
>
> **Ocho.** Después, lo de siempre: **CUO, autocompletar columnas, guardar en base de datos.**
>
> **Y la idea que quiero que se lleven:**
>
> **Nueve.** **La propuesta del SIRE no viene validada.** Sobre todo en compras. El sistema les ahorra la digitación, **no la revisión.**
>
> Y si quieren aprovechar el webinar de verdad: **descarguen hoy la propuesta de un mes que ya tengan cerrado y pásenla por el diagnóstico.** Comparen los totales con lo que ya registraron. Ahí van a ver con sus propios datos lo que les mostré.

---

### 🕐 4:29 – 4:30 — CIERRE Y PASE A INGRID

> Bueno, eso es todo de mi parte. Muchísimas gracias a todos por acompañarme.
>
> Cualquier consulta que les haya quedado, **escríbanla en el chat que Carlos la está atendiendo**.
>
> Y ahora **no se me vayan todavía**, porque le paso la palabra a mi compañera **Ingrid**, que les va a comentar **las promociones que tenemos esta semana**.
>
> Ingrid, te dejo con ellos. Adelante.

*[Deja de compartir pantalla si Ingrid necesita la suya. Quédate conectado.]*

---

## ANEXO A — MENSAJES PARA EL CHAT

**Mensaje 1 (minuto 1):**
```
👋 Bienvenidos al webinar de PeruContable
Hoy: novedad de ContaExcel 41.11
📥 Importar la propuesta del SIRE (compras y ventas) directo al sistema
1️⃣ Diagnosticar
2️⃣ Importar y revisar
3️⃣ Corregir y guardar
💬 Consultas en el chat — Carlos las responde por acá.
```

**Mensaje 2 (minuto 4:05, al cerrar la actualización de empresas):**
```
📌 ¿VIENES DE LA 41.6?
Actualiza CADA empresa:
SISTEMA CONTABLE → RUTA DE BASE DE DATOS → abrir empresa
→ UTILITARIOS → ACTUALIZAR VERSIÓN → aceptar avisos
(Desde la 41.7 no es necesario)
```

**Mensaje 3 (minuto 4:20, al cerrar el tema 3):**
```
📌 IMPORTAR LA PROPUESTA SIRE
• LIBROS ELECTRÓNICOS → IMPORTAR COMPRAS Y VENTAS
• TXT o CSV, se puede subir COMPRIMIDO
• DIAGNOSTICAR primero: cantidad y totales, sin importar nada
• ⚠️ El mes del sistema = el mes del archivo
• REVISIÓN SIRE marca fechas incoherentes e IGV fuera de tasa
```

**Mensaje 4 (minuto 4:27, con el repaso):**
```
📌 DESPUÉS DE IMPORTAR
• Corrige en la estructura ANTES de guardar
• Luego lo de siempre: CUO → Autocompletar → Guardar en BD
• En ventas el CUO continúa el correlativo de compras
• ⚠️ La propuesta SIRE NO viene validada: revísala, sobre todo compras
• El copiar y pegar sigue funcionando
```

---

## ANEXO B — RESPUESTAS PREPARADAS

**"¿Cómo me llega la 41.11?"**
> Por correo, con el asunto "Actualización del sistema ContaExcel", a todos los clientes con membresía activa. Ahí vienen el archivo, los pasos y el video tutorial de instalación. *[⚠️ Confirma con Carlos si ya se envió a todos.]*

**"No me llegó el correo / no tengo la contraseña del archivo."**
> Escríbanle a soporte al WhatsApp 945 035 566. *(No digas la contraseña al aire.)*

**"¿Tengo que actualizar todas mis empresas?"**
> Si vienen de la 41.6, sí, una por una: utilitarios, actualizar versión. Si vienen de la 41.7, no es necesario, aunque hacerlo no causa ningún problema.

**"¿Descargo el TXT o el CSV?"**
> Cualquiera de los dos. El sistema lee ambos.

**"¿Tengo que descomprimir el archivo?"**
> No. El sistema lo lee comprimido, tal como baja del SIRE.

**"No me deja importar, dice que el periodo es distinto."**
> El mes del sistema tiene que ser el mismo que el del archivo. Entren a datos generales, modificar, cambien el mes y el año al de la propuesta, actualizar, y vuelvan a importar. No se modificó nada en el sistema.

**"La Revisión SIRE me sale desactivada."**
> Se activa sola después de importar compras o ventas. Antes no tiene nada que revisar.

**"¿El diagnóstico sube algo al sistema?"**
> No. Solo muestra el resumen: cantidad de comprobantes, totales y tipos de documento. Si cierran, no pasa nada.

**"¿Esto envía algo a SUNAT?"**
> No. El sistema lee el archivo que ustedes descargaron. No se conecta al SIRE ni envía nada.

**"¿Qué hago con las fechas de vencimiento que vienen mal?"**
> Las corrigen con la fecha real o, si no usan la fecha de vencimiento en compras, las eliminan. Se hace en la estructura, antes de autocompletar y guardar.

**"¿Declaro el comprobante con el IGV descuadrado tal cual o lo corrijo?"**
> *[⚠️ CRITERIO CONTABLE — pasa a Carlos.] "Esa te la responde Carlos por el chat. El sistema te deja hacer cualquiera de las dos."*

**"¿Por qué valida 18%, 10% y 10.5%?"**
> *[⚠️ VERIFICA CON CARLOS.] Si no lo confirmaste: "Esa te la afina Carlos por el chat."*

**"¿Ya no puedo usar el copiar y pegar?"**
> Sí pueden. Ese método sigue funcionando igual. Esto es una opción adicional.

**"¿El CUO de ventas empieza en 1?"**
> En la demo continuamos el correlativo: compras terminó en 7 y ventas empezó en 8. Usen el mismo criterio de numeración que ya venían usando en la importación masiva.

**"¿Qué otras validaciones va a tener?"**
> Vamos a seguir agregando validaciones en las próximas versiones, para que estén prevenidos de más incoherencias que puedan venir en la propuesta.

**"¿Cuánto cuesta el sistema / cómo renuevo la membresía?"**
> Eso lo ve Ingrid, que entra justo después de mí. Quédense para esa parte.

---

## ANEXO C — FRASES DE EMERGENCIA

**Si el archivo no carga o sale un error al leerlo:**
> Déjenme probar con el otro formato… *[Selecciona el CSV si estabas con el TXT, o al revés.]* Por eso les decía que pueden descargar los dos: si uno falla, tienen el otro.

**Si te sale el aviso de periodo sin querer (empresa en otro mes):**
> Y miren, justo me pasó lo que les iba a mostrar al final: el sistema me frena porque estoy en otro mes. *[Cambia el mes en datos generales y sigue. Luego, en el Tema 5, solo menciona el candado en vez de repetirlo.]*

**Si la Revisión SIRE muestra observaciones distintas a las ensayadas:**
> Acá me está marcando esta fila por este motivo… *[Lee lo que diga la pantalla.]* Y justamente de eso se trata: cada propuesta trae sus propias incoherencias, y el sistema se las va señalando.

**Si la importación falla a mitad de demo:**
> Voy a usar la empresa donde ya tenía la importación hecha, para mostrarles cómo queda. *[Pasa al plan B.]*

**Si preguntan algo tributario:**
> Esa te la responde Carlos por el chat. Yo les muestro cómo lo hace el sistema, el criterio se los afina él.

**Si te trabas:**
> Déjenme resumirles el punto clave hasta acá: [repite la idea del bloque].

**Si son las 4:24 y vas atrasado:**
> *[Ventas solo de palabra ("es exactamente el mismo proceso, y en ventas no suelen salir observaciones"). Muestra el candado del periodo con compras, haz el repaso en versión corta y pasa a Ingrid a las 4:29. **Nunca le quites tiempo a Ingrid.**]*

---

## NOTAS FINALES

- **El hilo es "diagnosticar → importar → revisar".** Recuérdalo en las transiciones: "ya vimos qué trae, ahora lo subimos", "ya lo subimos, ahora lo revisamos". Eso mantiene el ritmo sin preguntas al chat.
- **El momento clave es la fila 18.** Ahí se entiende que la propuesta trae errores. Tómate tu tiempo, haz la cuenta en voz alta y deja que el mensaje se asiente.
- **No vendas la función como "importa y listo".** El valor está en que ahorra digitación **y** avisa. Si alguien sale pensando que ya no tiene que revisar, el webinar falló.
- **Lee los avisos en voz alta.** Sin cámara, los avisos del sistema son tu mejor material: muestran que el sistema cuida al usuario.
- **Si vas sobrado de tiempo**, extiéndete en cómo cuadrar el diagnóstico contra el registro propio (qué hacer si la cantidad no coincide). A los contadores con muchas empresas les interesa mucho.
- **Si vas justo**, lo más comprimible es ventas: dilo de palabra.
- **Nunca hagas clic en silencio.**
- **Vigila el reloj a las 4:24.**
