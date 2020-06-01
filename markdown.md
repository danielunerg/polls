# Markdown Practice 
- [Summary](#Summary)
- [Block_Elements](#Block_Elements)
     * [Headings](#Headings)
     * [Blockquotes](#Blockquotes)
     * [List](#List)
- [Inline_Elements](#Inline_Elements)
- Code 
     * [C#](#Csharp)
     * [HTML](#HTML)
     * [SQL](#SQL)
![Cualquier parecido es pura conincidencia](https://statics-cuidateplus.marca.com/sites/default/files/styles/natural/public/enfermedad-alopecia-hombre-cabello_0.jpg?itok=c6KkDKSg)  

## Summary
||
|:---|
Este pequeño resumen está elaborado con la idea que podamos unificar 
criterios respecto a la elaboración de documentación utilizando Markdown.  
Dejando definido como formatear textos, incorporar imágenes, índices, 
incorporar códigos, entre otros.

## Block_Elements
* ### Headings
    ```Niveles
    Encabezado 1
    ========
    Encabezado 2
    --------  
    # Encabezado 1 #
    ## Encabezado 2 ##
    ### Encabezado 3 ###
    ```
 
* ### Blockquotes
   > La sintaxis se basa en la manera en que los programas de correo electrónico  
   >! suelen hacer las citas.
* ### List
   ```
   - Utiliza un signo menos para las viñetas
   + O un signo más
   * O un asterisco
   ```
## Inline_Elements
* ### Bold [`**`]
      **Esto está en negrita**, y __esto__ también.
* ### Italics [`*`]
     *Esto está en cursiva*, y _esto_ también.  
      <br>Utiliza ***cursiva y negrita juntas*** si lo ___necesitas___.
## Code
* ### Csharp
```csharp
  using System;
  namespace LosTongePanas
  {
      public class Hair
      {
          private bool _hair;
          public static Hair(bool hair)
          {
              _hair = hair;
          }
      }
  }
```
* ### HTML
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8"> </meta>
  </head>
</html>
```
* ### SQL
```sql
CREATE DATABASE tongue;
USE tongue;
CREATE TABLE tongeRatas ( id INT PRIMARY KEY, nombre VARCHAR(20) );
INSERT INTO tongeRatas VALUES ( 1, 'PM' );
INSERT INTO tongeRatas VALUES ( 2, 'Argemen' );
INSERT INTO tongeRatas VALUES ( 3, 'Canux' );
SELECT id, nombre FROM tongeRatas WHERE id = 1;
UPDATE tongeRatas SET nombre = 'Stayfree' WHERE id = 1;
SELECT id, nombre FROM tongeRatas;
DELETE FROM tongeRatas WHERE id = 1;
SELECT id, nombre FROM tongeRatas;
DROP DATABASE tongue;
SELECT count(1) from tongeRatas;
```
