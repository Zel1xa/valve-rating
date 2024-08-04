### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1605.7<br />
<br />
Final Rank Value (1605.7) = Starting Rank Value (1721.6) + Head To Head Adjustments (-115.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.416[<sup>2</sup>](#table1)
- LAN Wins: 0.901[<sup>2</sup>](#table1)

The average of these factors is 0.646<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1721.6
- 400 + ( ( 0.646 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1721.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      555 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.62 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      601 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.721 (0.721)    | 1 (1.000) |    22.73 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      612 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     2.87 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      623 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.294 (0.294)    | 1 (1.000) |     3.03 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      681 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.18 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1282 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.821      | -            | -                | -                | -         |   -12.74 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1401 | 2024-06-06 | Complexity         | W   | 0.807      | 0.715        | 0.342 (0.198)    | 0.380 (0.219)    | 1 (0.807) |    13.96 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1418 | 2024-06-06 | fnatic             | W   | 0.806      | 0.715        | 0.371 (0.214)    | 0.708 (0.408)    | 1 (0.806) |     8.84 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1440 | 2024-06-06 | Eternal Fire       | W   | 0.805      | 0.715        | 0.742 (0.427)    | 0.458 (0.263)    | 1 (0.805) |    15.53 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1470 | 2024-06-05 | BetBoom            | W   | 0.800      | 0.715        | 0.251 (0.143)    | 0.541 (0.310)    | 1 (0.800) |     6.72 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1487 | 2024-06-05 | BIG                | L   | 0.799      | -            | -                | -                | -         |   -19.98 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1565 | 2024-06-02 | GUN5               | L   | 0.780      | -            | -                | -                | -         |   -23.78 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1570 | 2024-06-02 | MOUZ NXT           | W   | 0.779      | 0.435        | 0.139 (0.047)    | 1.000 (0.339)    | -         |     1.43 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1609 | 2024-06-01 | Zero Tenacity      | W   | 0.772      | 0.435        | -                | 1.000 (0.335)    | -         |     1.51 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1660 | 2024-05-30 | RUBY               | W   | 0.759      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1768 | 2024-05-25 | 1WIN               | L   | 0.726      | -            | -                | -                | -         |   -22.07 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1780 | 2024-05-24 | Passion UA         | W   | 0.720      | 0.435        | 0.172 (0.054)    | 1.000 (0.313)    | -         |     0.88 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2343 | 2024-05-05 | Monte              | L   | 0.593      | -            | -                | -                | -         |   -18.11 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2363 | 2024-05-04 | ENCE               | W   | 0.587      | 0.889        | 0.169 (0.088)    | -                | 1 (0.587) |     3.71 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2378 | 2024-05-03 | Bad News Kangaroos | W   | 0.580      | -            | -                | -                | 1 (0.580) |     0.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2421 | 2024-05-01 | FORZE              | L   | 0.567      | -            | -                | -                | -         |   -17.54 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2443 | 2024-04-30 | Liquid             | L   | 0.561      | -            | -                | -                | -         |   -10.56 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2693 | 2024-04-19 | MIBR               | L   | 0.489      | -            | -                | -                | -         |   -11.94 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2718 | 2024-04-19 | Metizport          | W   | 0.486      | -            | -                | -                | 1 (0.486) |     0.19 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2744 | 2024-04-18 | 9z                 | L   | 0.481      | -            | -                | -                | -         |   -10.27 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3035 | 2024-04-09 | HEROIC             | L   | 0.419      | -            | -                | -                | -         |    -8.82 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3064 | 2024-04-08 | MOUZ               | L   | 0.413      | -            | -                | -                | -         |    -3.82 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3076 | 2024-04-07 | Lynn Vision        | W   | 0.411      | -            | -                | -                | -         |     0.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3394 | 2024-03-22 | Gaimin Gladiators  | L   | 0.301      | -            | -                | -                | -         |    -9.30 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3412 | 2024-03-21 | FaZe               | L   | 0.295      | -            | -                | -                | -         |    -4.96 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3422 | 2024-03-21 | G2                 | L   | 0.293      | -            | -                | -                | -         |    -1.51 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3446 | 2024-03-20 | SAW                | W   | 0.287      | -            | -                | -                | -         |     0.44 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3462 | 2024-03-19 | ENCE               | W   | 0.281      | -            | -                | -                | -         |     1.70 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3470 | 2024-03-18 | KOI                | W   | 0.274      | -            | -                | -                | -         |     0.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3483 | 2024-03-17 | Lynn Vision        | L   | 0.268      | -            | -                | -                | -         |    -8.26 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3498 | 2024-03-17 | Legacy             | L   | 0.267      | -            | -                | -                | -         |    -8.24 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3847 | 2024-03-03 | Complexity         | W   | 0.175      | -            | -                | -                | -         |     2.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3881 | 2024-03-02 | Liquid             | W   | 0.167      | -            | -                | -                | -         |     1.74 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3903 | 2024-03-01 | Nouns              | W   | 0.161      | -            | -                | -                | -         |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4036 | 2024-02-23 | 9z                 | L   | 0.116      | -            | -                | -                | -         |    -2.64 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4050 | 2024-02-22 | 9z                 | W   | 0.109      | -            | -                | -                | -         |     0.95 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4057 | 2024-02-22 | Imperial           | W   | 0.108      | -            | -                | -                | -         |     0.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4338 | 2024-02-10 | Metizport          | L   | 0.027      | -            | -                | -                | -         |    -0.85 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4339 | 2024-02-10 | ex-Anonymo         | W   | 0.027      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4343 | 2024-02-10 | Metizport          | L   | 0.026      | -            | -                | -                | -         |    -0.82 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92,038.03)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.827 | $28,000.00     | $23,144.07      |
| 2024-06-02 |      0.780 | $10,000.00     | $7,799.07       |
| 2024-05-26 |      0.734 | $2,000.00      | $1,467.04       |
| 2024-05-12 |      0.640 | $12,000.00     | $7,678.89       |
| 2024-04-20 |      0.495 | $5,000.00      | $2,474.07       |
| 2024-04-14 |      0.452 | $5,000.00      | $2,260.07       |
| 2024-03-31 |      0.361 | $20,000.00     | $7,214.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
