# atp_matches_2020

## Autores:
Enrique Martínez Gestoso y Antonio de la Rubia Salvador

## Contenido:
README.md: Contiene información sobre los autores, ficheros y contenido del dataset.

atp_2020_PRA2.Rmd: Contiene el código en R para la ejecución del programa de limpieza y analisis de datos sobre el csv original.

ATP_2020.csv: Dataset en formato CSV proveniente del usuario de GitHub @JeffSackmann https://github.com/JeffSackmann/tennis_atp/blob/master/atp_matches_2020.csv.

PRA2_ARS_EMG.pdf: Documento PDF con las respuestas a las preguntas y nombres de los componentes del grupo así como la tabla de contribuciones al trabajo.

Contribuciones: Contiene la tabla de las contribuciones por integrante.

## Español 
Limpieza y validación de los datos proporcionados por el usuario @JeffSackmann. Se pretende realizar un análisis de los partidos disputados en el 2020 de la liga ATP.

Las bibliotecas necesarias para ejecutar el script son:

```
dplyr
```

Las estadísticas se almacenan en un dataset de tipo CSV.

Se incluyen las siguientes estadísticas para cada partido de la temporada ATP 2020:

- Tourney_id: Año-ID del torneo (2020-8888)
- Tourney_name: Nombre del torneo (Atp Cup, Davis Cup)
- Surface: Superficie de la pista de juego (Hard, Clay, Grass)
- Draw_size: Número de jugadores del torneo (4, 8, 24)
- Tourney_level: Nivel del torneo (A, D, F)
- Tourney_date: año, me sy dia del partido (20200106)
- Match_num: Numero de partido (1, 2, 3)
- Winner_seed: cabeza de serie (1, 2, 3, 4)
- Winner_entry: 
- Winner_name: Nombre del jugador vencedor (Novak Djokovic, Roberto Bautista, Rafael Nadal)
- Winner_hand: Mano dominante del jugador vencedor (R, L , U)
- Winner_ht: Altura del jugador vencedor (188, 190, 183)
- Winner_ioc: Nacionalidad del jugador vencedor (SRB, ESP, FRA)
- Winner_age: Edad del jugador vencedor (32’6, 34’7, 27’4)
- Loser_id: Identificador del jugador perdedor (104925, 105138)
- Loser_seed: cabeza de serie (1, 2, 3, 4)
- Loser_entry: 
- Loser_name: Nombre del jugador perdedor (Novak Djokovic, Roberto Bautista, Rafael Nadal)
- Loser_hand: Mano dominante del jugador perdedor (R, L , U)
- Loser_ht: Altura del jugador perdedor (188, 190, 183)
- Loser_ioc: Nacionalidad del jugador perdedor (SRB, ESP, FRA)
- Loser_age: Edad del jugador perdedor (32’6, 34’7, 27’4)
- Score: Puntuación final del partido
- Best_of: Número de sets del partido (3, 5)
- Round: Ronda del torneo (F, SF, QF)
- Minutes: Duración del partido en minutos
- l_ace: Número de Ace’s del jugador perdedor
- l_df: Número de dobles faltas del jugador perdedor
- l_svpt: Número de puntos de servicio del jugador perdedor
- l_1stIn: Número de primeros servicios dentro de la pista del jugador perdedor
- l_1stWon: Número de puntos por primer servicio del jugador perdedor
- l_2ndWon: Número de puntos por segundo servicio del jugador perdedor
- l_svgms: Número de juegos de servicio del jugador perdedor
- l_bpSaved: Número de puntos de break salvados del jugador perdedor
- l_bpFaced: Número de puntos de break enfrentados del jugador perdedor
- Winner_rank: Ranking del jugador vencedor
- Winner_rank_points: Puntos de ranking del jugador vencedor
- Loser_rank: Ranking del jugador perdedor
- Loser_rank_points: Puntos de ranking del jugador perdedor
