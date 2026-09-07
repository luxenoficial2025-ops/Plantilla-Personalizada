# Guía de Metafields para Landing COD (Plantilla Dinámica)

Para que la plantilla product.landing-cod.json muestre información única por cada producto, debes crear los siguientes **Metafields de Producto** en el panel de administración de Shopify (Configuración > Datos personalizados > Productos).

Todos deben usar el **namespace** custom.

## Textos
1. **Problemas del cliente**
   - **Nombre:** Problemas Landing
   - **Namespace y key:** custom.landing_problemas
   - **Tipo:** Texto multilínea o Texto enriquecido
   - **Uso:** Rellena los "puntos de dolor" del cliente (ej. crujidos, dolor).

2. **Beneficios / Solución**
   - **Nombre:** Beneficios Landing
   - **Namespace y key:** custom.landing_beneficios
   - **Tipo:** Texto multilínea o Texto enriquecido
   - **Uso:** Rellena la lista de soluciones que aporta el producto.

3. **Texto de WhatsApp (Prueba Social)**
   - **Nombre:** Texto Chat Landing
   - **Namespace y key:** custom.landing_chat_texto
   - **Tipo:** Texto de una línea o multilínea
   - **Uso:** El testimonio que aparece en la burbuja de chat simulada.

4. **Autor de WhatsApp**
   - **Nombre:** Autor Chat Landing
   - **Namespace y key:** custom.landing_chat_autor
   - **Tipo:** Texto de una línea
   - **Uso:** Fecha y nombre (ej. "Ayer 15:30 • Carlos M.").

## Imágenes (Tipo: Archivo -> Aceptar solo imágenes)
5. **Infografía Principal**
   - **Namespace y key:** custom.landing_infografia
   - **Uso:** Imagen anatómica o explicativa del producto.

6. **Foto Antes**
   - **Namespace y key:** custom.landing_antes
   - **Uso:** Resultado negativo inicial (Día 1).

7. **Foto Después**
   - **Namespace y key:** custom.landing_despues
   - **Uso:** Resultado positivo (Día 21).

8. **Paso 1, 2 y 3 (Modo de uso)**
   - **Namespace y keys:** custom.landing_paso1, custom.landing_paso2, custom.landing_paso3
   - **Uso:** Las 3 imágenes de las instrucciones de uso.

9. **UGC 1 y UGC 2 (Entregas)**
   - **Namespace y keys:** custom.landing_ugc1, custom.landing_ugc2
   - **Uso:** Fotos de cajas entregadas o clientes con el producto.

*Nota: Si dejas un metafield vacío en un producto, la plantilla usará la imagen/texto configurado por defecto en el Theme Editor, o el contenido genérico de muestra.*