TALLER INTEGRADOR INDIVIDUAL


JOSE AGUSTIN BARRANCO MUÑOZ


Hallasgos:
| Defecto encontrado | Por qué era un problema | Como lo corrigió |
|---|---|---|
| Renombrar Nombres de archivo con espacios, mayúsculas mezcladas y extensión en mayúscula: Mi Pagina De Notas.HTML, Estilos Del Sitio.CSS | No siguen convención (kebab-case/minúsculas), los espacios pueden romper rutas o requerir codificación URL, y la extensión debe ir en minúscula | Se renombro los dos archivos siguiendo la convención kebab-case. |
| El href del CSS referencia el archivo con espacios en el nombre: href="Estilos Del Sitio.CSS" | Es consecuencia directa del defecto 1; enlaces con espacios sin codificar son frágiles entre sistemas operativos y servidores | Se actualizo el href con el nuevo nombre del archivo styles.css. |
| Variable mal nombrada: TempValue2 | Mezcla convenciones (PascalCase donde debería ser camelCase), y el sufijo "2" no tiene sentido porque nunca existió un TempValue1 | Se renombró a promedio, siguiendo la convención camelCase y sin el sufijo "2" innecesario. |
| Variables de una sola letra sin significado: a, b, c | Obligan a leer todo el código para saber qué representan; deberían llamarse algo como nota1, nota2, nota3 | Se renombraron a nota1, nota2, nota3. |
| Constante sin nombre significativo: let x = 3; | Un número con nombre de una letra no explica su propósito (es la cantidad de notas) | Se renombró a CANTIDAD_NOTAS, en mayúsculas por convención de constantes, y ahora indica claramente qué representa. |
| IDs de HTML abreviados y no descriptivos: n1, n2, n3, r, r2 | No comunican su propósito; deberían ser algo como nota1, resultadoPromedio, resultadoEstado | Se renombraron a inputNota1, inputNota2, inputNota3, resultadoPromedio y resultadoEstado. |
| Variable declarada y nunca utilizada: let data1 = []; | Código muerto: ocupa espacio y confunde a quien lee el archivo sin cumplir ninguna función | Se eliminó por completo, ya que no cumplía ninguna función en el código. |
| Título de la pestaña no descriptivo: <title>pagina</title> | No dice qué hace la página; debería describir su función (p. ej. "Calculadora de Promedio") | Se cambió a <title>Calculadora de Promedio</title>, describiendo el propósito real de la página. |


Enlace al sitio publicado: https://calculadora-de-promedios.netlify.app/


