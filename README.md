# Ciclos políticos y presentación de mociones en el congreso chileno
Estudio de carácter científico que busca dilucidar cómo los ciclos políticos afectan el envío de mociones en el congreso chileno. El estudio es capaz de determinar que los ciclos resultan ser relevantes para explicar la presentación de mociones, pero éstos impactan de manera distinta a lo planteado por la literatura sobre productividad legislativa hasta el momento.

# Aspectos técnicos
La base de datos en su totalidad fue construida por mi, con datos proporcionados por la página web del Senado en relación a las mociones enviadas por cada legislador. La codificación por ciclos fue hecha de manera manual y la base de datos tiene una estructura de panel donde se divide cada período (2002-2006, 2006-2010, 2010-2014) en cuatro ciclos que representan el año 1, año 2, año 3 y año 4.

A nivel estadístico se utiliza un modelo por variable de conteo. Se modela la variable explicativa a través de una distribución Negative Binomial debido a que los test pertinentes arrojaron una sobre dispersión de la misma.

### Todos los análisis descriptivos e inferenciales fueron realizados en R. El documento Results.Rmd tiene el detalle con todo el código utilizado.
