# Tesis
## Scripts: 

[Mapas promedio sanos](https://github.com/Taekleee/Tesis-modificada/blob/main/Promedio-mapas-sanos.R): Calcula el mapa promedio de todos los sujetos que se encuentran ubicados en la carpeta especificada en files.

[Mapas promedio ACV](https://github.com/Taekleee/Tesis-modificada/blob/main/Promedio-mapas-sanos-ACV.R):Calcula el mapa promedio de todas las personas con ACV que se encuentran ubicados en la carpeta especificada en files. Las personas no deben tener en las imágenes nifti la zona de infarto ni de penumbra (demora más tiempo que el anterior, ya que suma vóxel por vóxel, para promediar segùn las zonas que tengan valores distintos a 0, es decir, que no se consideran las zonas afectadas).

[Aplicar máscaras](https://github.com/Taekleee/Tesis-modificada/blob/main/applyMask.py): El script aplica las máscaras sobre los mapas completos de las complejidades estadísticas. Se espera que las carpetas y los archivos se encuentren distribuidos como aparece en el print de inicio del script.

[Aplicar máscaras LZC y PE](https://github.com/Taekleee/Tesis-modificada/blob/main/applyMaskLZC-PE.py): El script aplica las máscaras sobre los mapas completos obtenidos de las complejidades de Lempel Ziv y la entropía permutada. Se espera que las carpetas y los archivos se encuentren distribuidos como aparece en el print de inicio del script.

[Cerebros pareados](https://github.com/Taekleee/Tesis-modificada/blob/main/cerebros-pareados-script.R): Script con el pareo de los grupos para comparar los cerebros. Aplica el test estadístico correspondiente y obtiene los gráficos promedio.

[Cálculo entropías y complejidades](https://github.com/Taekleee/Tesis-modificada/blob/main/fmri.R): Cálculo de las entropías y complejidades para cada imágenes de resonancia magnética. Se debe tener la distribucoión de carpetas y archivos como aparece anteriormente.

[Gráficos por embedding](https://github.com/Taekleee/Tesis-modificada/blob/main/grafico-promedio-3-embedding.R): Gráficos promedio de las complejidades estadísticas con los 3 embedding (Sólo para comparar 2 grupos).

[Gráficos LZC - PE (3 zonas)](https://github.com/Taekleee/Tesis-modificada/blob/main/graficos-promedio-3-zonas-lzc-pe.R): Gráficos de las complejidades de Lempel Ziv y la entropía permutada, para las zonas de infarto, penumbra y el hemisferio completo.

[Gráfico individial complejidad/entropía](https://github.com/Taekleee/Tesis-modificada/blob/main/gr%C3%A1ficos-de-cada-entrop%C3%ADa-complejidad.R): Gráficos para ver cada una de las entropías y complejidades en específico. Se debe especificar la entropía, el desequilibrio y el embedding.

[Heatmap](https://github.com/Taekleee/Tesis-modificada/blob/main/heatmap.R): Gráfico de calor de las medias. Demuestra que existen variaciones, pero que los valores de estas en general son bajos.

[Hemisferios pareados](https://github.com/Taekleee/Tesis-modificada/blob/main/hemisferios-pareados-script.R): Script con el pareo de los grupos para comparar los hemisferios. Aplica el test estadístico correspondiente y obtiene los gráficos promedio.

[Zona de infarto, penumbra y hemisferio pareado](https://github.com/Taekleee/Tesis-modificada/blob/main/pareo-grupos-gr%C3%A1ficos-test.R): Script con el pareo de los grupos para comparar la zona de infarto, penumbra y el hemisferio. Aplica el test estadístico correspondiente y obtiene los gráficos promedio.

[Test estadísticos](https://github.com/Taekleee/Tesis-modificada/blob/main/test-estad%C3%ADsticos.R): T de student con bootstrapping y modelo mixto segùn corresponda para cada una de las comparaciones.

## Carpetas
[Carpeta general](https://github.com/Taekleee/Tesis-modificada/tree/main/Anonymous-fMRI-images): Carpeta que contiene a los sujetos sanos y con ACV, sus máscaras y los mapas promedio de cada una de las complejidades y entropías calculadas.

[Carpeta de resultados](https://github.com/Taekleee/Tesis-modificada/tree/main/Resultados): Carpeta con los resultados obtenidos, es decir, promedio de los mapas de los sujetos, valores de medias, etc.

[Máscaras](https://github.com/Taekleee/Tesis-modificada/tree/main/fMRI-atlases): Màscaras para los sujetos sanos.


## Documentos
[Tesis preliminar](https://github.com/Taekleee/Tesis-modificada/blob/main/Intento_de_tesis.pdf): Tesis enviada a la comisión
[Medias y p-valores](https://github.com/Taekleee/Tesis-modificada/blob/main/Medias%20tesis.pdf): p-valores y medias obtenidas.
