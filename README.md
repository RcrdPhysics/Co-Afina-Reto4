# Co-Afina-Reto4
Repositorio de solución al reto 4 del Co-Afina.

# PROYECTO

## Carl Sagan Verificador

## Objetivo: Dar un número de confiabilidad (+ Plots) para @divulgador_medico

Para lograr esto se necesitan los siguientes pasos:
1. Extracción
    1. Conectar y autenticar con API
    2. Extrae dataI en un raw_pd - Tweets [+user.verified]
    3. Etiquetado confiable/noconfiable 
        1. Excel con 25 tweets de 1 divulgador: user_id, 1 0 (confiable o no confiable)
        2. Excel con 25 tweets de 1 pseudocientifico: user_id, 1 0 (confiable o no confiable)
2. Procesamiento
    1. Limpieza y lematizacion de texto
    2. Construir word_pd
        1. Variables del paper
        2. Definir categorias
        3. Variables extras (opcional)
3. EDA - Plots 
    1. Obtencion de palabras clave por bigrama y trigrama
    2. Recurrencia de palabras clave
    3. Análisis y visualizaccicón de resultados
4. Machine Learning 
    1. Análisis de Sentimiento.
    2. Categorización de temáticas.
    3. Análisis y visualización de resultados.
5. Visualización centrada en el usuario.
    1. Figma 
    2. Codigo bien presentado
    3. Video
