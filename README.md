# Análisis de Ventas Históricas de Videojuegos

## Tabla de Contenidos
- [Descripción](#Descripción)
- [Datos](#Datos)
- [Análisis](#Análisis)
- [Tecnologías y herramientas](#Tecnologías-y-herramientas)
- [Resultados](#Resultados)
- [Contribuciones](#Contribuciones)
- [Licencia](#Licencia)
- [Contacto](#Contacto)

## Descripción
Análisis integral de patrones que determinan el éxito en ventas de videojuegos para la tienda online ICE, utilizando datos históricos hasta 2016 para pronosticar ventas 2017 y optimizar campañas de marketing.

## Datos
Se utilizó un onjunto de datos principal:  
- **games.csv**: Contiene registros de ventas por juego, plataforma, año, y regiones (Norteamérica, Europa, Japón, y resto del mundo), calificaciones de críticos, usuarios, y rating. 

Características clave incluyen:  
- 16,715 registros históricos.  
- Variables: nombre, plataforma, año, género, clasificación ESRB, ventas por región, calificaciones de críticos y usuarios.  
- Datos limpios y normalizados para análisis.  

## Análisis
El enfoque incluyó:  
- Estudio de ciclos de vida de generaciones de plataformas, identificando tendencias y puntos máximos de ventas.
- Evaluación del comportamiento de ventas y rentabilidad de las principales plataformas (PS4, X-One, 3DS, WiiU, PC).
- Análisis de correlaciones entre ventas totales y reseñas de críticos y usuarios.
- Perfilamiento regional de ventas por plataforma, género y clasificación ESRB en Norteamérica, Europa y Japón.
- Comparación estadística para validar diferencias significativas en calificaciones de usuarios entre plataformas y géneros.

## Tecnologías y herramientas
- Python 3.9 para programación general y análisis de datos
- Pandas y NumPy para manipulación y procesamiento de datos
- Matplotlib y Seaborn para visualización estadística y exploratoria
- SciPy para análisis estadístico avanzado
- Jupyter Notebook para desarrollo interactivo y presentación de resultados

## Resultados
- PS4 lidera en ventas globales y en mercados de NA y UE, mientras que 3DS domina en Japón; PC y X-One son menos aceptadas en Japón.
- Géneros de acción y disparos concentran más del 49% de las ventas globales, mientras que RPG domina en el mercado japonés.
- Clasificación ESRB M es la más vendida globalmente, aunque con baja aceptación en Japón donde predomina la clasificación E.
- Correlación moderada positiva entre ventas y reseñas de críticos; reseñas de usuarios muestran correlación muy débil con ventas.
- Se confirma diferencia significativa en calificaciones de usuarios entre géneros Acción y Deportes, pero no entre Xbox One y PC.

## Contribuciones
Bienvenidas sugerencias, correcciones y nuevas visualizaciones. Por favor, abre un issue o pull request para colaborar.

## Licencia
Este proyecto está bajo la licencia MIT.

## Contacto
Nombre: Alejandro M. García  
Email: [alexkhype@gmail.com](mailto:alexkhype@gmail.com)  
LinkedIn: [linkedin.com/in/amggl](https://linkedin.com/in/amggl)
