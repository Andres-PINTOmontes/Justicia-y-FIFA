# Análisis Estadístico del Sorteo de la Copa Mundial de la FIFA 2010
## Descripción
Este proyecto presenta un análisis estadístico cuantitativo del sorteo de la Copa Mundial de la FIFA 2010 para evaluar si la estructura de los grupos fue estadísticamente inusual. Usando una simulación de Monte Carlo, se introdujo el Índice de Balance Estructural (IBE) para medir tanto el equilibrio externo (dispersión de la calidad de los equipos entre los grupos) como el equilibrio interno (variabilidad dentro de cada grupo) del sorteo. El análisis busca determinar si el sorteo fue "justo" desde una perspectiva estadística.

## Objetivo
El objetivo de este estudio es abordar la cuestión de si el sorteo de la Copa Mundial 2010 fue significativamente diferente de lo que se podría esperar de un proceso puramente aleatorio, dadas las restricciones geográficas y de cabezas de serie impuestas por la FIFA.

## Metodología
1. Índice de Balance Estructural (IBE)
Se introdujo el IBE, una métrica compuesta que combina dos medidas de desbalance:

### Balance Externo (Bext): Mide la disparidad en la fuerza promedio entre los grupos.

### Balance Interno (Bint): Mide la disparidad dentro de los grupos en términos de la variabilidad de las fuerzas de los equipos.

2. Simulación de Monte Carlo
Se realizaron 1,000 simulaciones de sorteos, replicando las reglas de la FIFA y respetando restricciones geográficas. El valor del IBE para el sorteo real de 2010 se comparó con la distribución empírica obtenida de las simulaciones.

3. Análisis Estadístico
Se contrastó la hipótesis nula de que el IBE observado en el sorteo real es típico de la distribución simulada. Un valor p de 0.032 indicó que el sorteo real fue más equilibrado que el 96.8% de los sorteos aleatorios.

## Resultados
Los resultados mostraron que el sorteo de 2010 fue estructuralmente más equilibrado que la mayoría de los sorteos simulados. El IBE real (38.67) fue significativamente menor que la media de los IBE simulados (41.41), con un valor p de 0.032. Esto indica que no existe evidencia estadística para afirmar que el sorteo fue injusto.

## Conclusiones
El análisis concluye que el sorteo de la Copa Mundial de la FIFA 2010 fue justo y más equilibrado de lo que la mayoría de los sorteos aleatorios podrían haber generado. Este enfoque puede extenderse para evaluar la equidad estructural en otros torneos deportivos.

## Referencias
Montgomery, D. C. (2017). Design and Analysis of Experiments (9th ed.). John Wiley & Sons.

Guyon, J. (2015). "The FIFA World Cup draw: a conditional-ergodic-process-based analysis of the ‘group of death’ probability". Journal of Quantitative Analysis in Sports, 11(3), 149-160.

Kemp, S., & Trewin, C. (2009). "Fairness in Fixture Scheduling: A Methodology for Group Assignment". Journal of Quantitative Analysis in Sports, 5(2), 17-28.

Owen, P. D., King, D. A. (2011). "Competitive balance in the major European soccer leagues: an analysis by club and country". International Journal of Sport Finance, 6(4), 275-295.

Wikipedia. (2024). Copa Mundial de Fútbol de 2010. Consultado el 24 de mayo de 2024, desde https://es.wikipedia.org/wiki/Copa_Mundial_de_Ftbol_de_2010.
