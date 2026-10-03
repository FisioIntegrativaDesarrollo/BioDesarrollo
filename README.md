# Segmentación holoblástica radial en el erizo de mar

Modelo didáctico e interactivo de las primeras siete divisiones de la segmentación del erizo de mar, desde el cigoto hasta la blástula de 128 células.

El proyecto es una página HTML autocontenida (sin dependencias ni conexión a internet) y una hoja de cálculo con el resumen y el conteo celular.


## Qué muestra el modelo

La segmentación es **holoblástica radial**: el huevo se divide por completo y las divisiones siguen planos simétricos respecto al eje animal-vegetal. Las primeras siete divisiones son estereotípicas, es decir, siguen el mismo patrón en todos los individuos de la especie.

| Segmentación | Células | Plano / tipo | Qué ocurre |
|---|---|---|---|
| 1.ª | 2 | Meridional | Pasa por ambos polos; blastómeras iguales |
| 2.ª | 4 | Meridional, perpendicular a la 1.ª | Cuatro blastómeras iguales |
| 3.ª | 8 | Ecuatorial | Separa hemisferio animal (4) y vegetal (4) |
| 4.ª | 16 | Asimétrica | Animal: meridional igual, 8 mesómeras. Vegetal: ecuatorial desigual, 4 macrómeras y 4 micrómeras |
| 5.ª | 32 | Animal: ecuatorial. Vegetal: meridional | Capas an₁ y an₂; anillo de 8 macrómeras bajo an₂. Las micrómeras se dividen un poco más tarde |
| 6.ª | 64 | Animal: meridional. Vegetal: ecuatorial | Se alternan los planos |
| 7.ª | 128 | Animal: ecuatorial. Vegetal: meridional | El patrón se invierte; blástula de 128 células |

Después de la 7.ª segmentación, las divisiones pierden su regularidad estereotípica.

## Contenido didáctico

### Objetivos de aprendizaje

Al terminar de explorar el modelo, deberías poder:

1. Explicar qué significa que una segmentación sea holoblástica y radial.
2. Distinguir los planos meridional y ecuatorial y reconocer cuál ocurre en cada división.
3. Describir la asimetría de la 4.ª segmentación y el origen de mesómeras, macrómeras y micrómeras.
4. Identificar las capas an₁, an₂, veg₁ y veg₂ y explicar por qué se alternan los planos en la 6.ª y 7.ª segmentación.
5. Calcular el número de células tras cada división.

### Glosario

| Término | Definición |
|---|---|
| Holoblástica | Segmentación en la que los planos de división atraviesan todo el huevo |
| Radial | Las divisiones son simétricas respecto al eje animal-vegetal |
| Estereotípica | Sigue el mismo patrón en todos los individuos de la especie |
| Meridional | Plano que pasa por los polos animal y vegetal |
| Ecuatorial | Plano perpendicular al eje animal-vegetal, que separa capas |
| Blastómera | Cada célula que resulta de la segmentación |
| Mesómeras | Las 8 células del piso animal tras la 4.ª segmentación |
| Macrómeras | Células grandes del piso vegetal (4 tras la 4.ª segmentación) |
| Micrómeras | Células pequeñas en el polo vegetal (4 tras la 4.ª segmentación) |
| an₁ y an₂ | Las dos capas que forman las mesómeras en la 5.ª segmentación |
| veg₁ y veg₂ | Capas del piso vegetal que se forman al alternar los planos |
| Blástula | Estadio de 128 células, desde donde las divisiones pierden la regularidad |

### Idea clave en una frase

Cada división duplica las células (2ⁿ), pero lo que cambia es el **plano** en que se divide cada hemisferio: meridional, ecuatorial o asimétrico.

### Actividades sugeridas

1. **Predice y comprueba.** Antes de pasar al siguiente estadio, anota cuántas células habrá y qué plano de división ocurrirá. Luego verifícalo en el modelo.
2. **Dos vistas, un embrión.** Compara la vista lateral con la vista desde el polo animal. ¿Por qué la 3.ª segmentación no cambia lo que se ve desde arriba?
3. **Cuenta por capas.** En el estadio de 128 células, cuenta cuántas células hay en cada hilera y comprueba que el total coincide con 2⁷.
4. **Completa la tabla.** Imprime la tabla resumen sin las dos últimas columnas y complétala de memoria.
5. **Cuaderno de cálculo.** En la hoja `Conteo celular`, cambia la fórmula para que la división inicial no sea 0 y observa cómo se recalculan los valores.

### Preguntas de repaso

1. ¿Qué diferencia hay entre un plano meridional y uno ecuatorial?
2. ¿Por qué la 4.ª segmentación se llama asimétrica?
3. ¿Cuántas células animales y vegetales hay en el estadio de 8 células?
4. ¿Qué células forman las capas an₁ y an₂ y en qué segmentación aparecen?
5. ¿Qué cambia entre la 6.ª y la 7.ª segmentación?
6. ¿Qué ocurre con la regularidad de las divisiones después de las 128 células?

<details>
<summary>Ver respuestas</summary>

1. El meridional pasa por ambos polos; el ecuatorial es perpendicular al eje animal-vegetal y separa capas.
2. Porque el piso animal se divide de forma igual y el vegetal de forma desigual, y da macrómeras y micrómeras.
3. 4 animales y 4 vegetales.
4. Las mesómeras, en la 5.ª segmentación, al dividirse ecuatorialmente.
5. Se invierte el patrón: en la 6.ª las animales se dividen meridionalmente y las vegetales ecuatorialmente; en la 7.ª, al revés.
6. Las divisiones pierden su regularidad estereotípica.

</details>

## Características técnicas

- Un solo archivo HTML con CSS y JavaScript incrustados; las vistas se dibujan en SVG generado por código.
- Compatible con modo claro y oscuro (`prefers-color-scheme`).
- Diseño adaptable a pantallas de escritorio y móvil.
- La hoja de cálculo usa fórmulas para el conteo celular, de modo que se recalcula si se modifican los valores de entrada (celdas en azul).


## Licencia

Contenido didáctico, creado para los estudiantes de Biología del Desarrollo de la UMCE.
