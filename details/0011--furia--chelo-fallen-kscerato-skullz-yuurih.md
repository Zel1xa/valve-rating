### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1617.6<br />
<br />
Final Rank Value (1617.6) = Starting Rank Value (1749.2) + Head To Head Adjustments (-131.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.646[<sup>1</sup>](#table2)
- Bounty Collected: 0.625[<sup>2</sup>](#table1)
- Opponent Network: 0.421[<sup>2</sup>](#table1)
- LAN Wins: 0.925[<sup>2</sup>](#table1)

The average of these factors is 0.654<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1749.2
- 400 + ( ( 0.654 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1749.2


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
|           45 |      407 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.29 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      453 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |    22.46 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      464 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.185 (0.185)    | 0.973 (0.973)    | 1 (1.000) |     2.79 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      475 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.105 (0.105)    | 0.298 (0.298)    | 1 (1.000) |     3.13 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      533 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.14 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1134 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.846      | -            | -                | -                | -         |   -14.47 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1253 | 2024-06-06 | Complexity         | W   | 0.832      | 0.715        | 0.348 (0.207)    | -                | 1 (0.832) |    13.92 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1270 | 2024-06-06 | fnatic             | W   | 0.832      | 0.715        | 0.371 (0.221)    | 0.633 (0.376)    | 1 (0.832) |     9.21 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1292 | 2024-06-06 | Eternal Fire       | W   | 0.830      | 0.715        | 0.752 (0.446)    | 0.462 (0.274)    | 1 (0.830) |    16.24 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1322 | 2024-06-05 | BetBoom            | W   | 0.825      | 0.715        | 0.256 (0.151)    | 0.554 (0.327)    | 1 (0.825) |     7.07 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1339 | 2024-06-05 | BIG                | L   | 0.824      | -            | -                | -                | -         |   -21.81 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1417 | 2024-06-02 | GUN5               | L   | 0.805      | -            | -                | -                | -         |   -24.62 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1422 | 2024-06-02 | MOUZ NXT           | W   | 0.804      | 0.435        | 0.140 (0.049)    | 1.000 (0.350)    | -         |     1.39 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1461 | 2024-06-01 | Zero Tenacity      | W   | 0.797      | 0.435        | -                | 1.000 (0.346)    | -         |     1.49 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1512 | 2024-05-30 | RUBY               | W   | 0.784      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1620 | 2024-05-25 | 1WIN               | L   | 0.751      | -            | -                | -                | -         |   -22.97 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1632 | 2024-05-24 | Passion UA         | W   | 0.745      | 0.435        | 0.171 (0.055)    | 1.000 (0.324)    | -         |     0.81 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2195 | 2024-05-05 | Monte              | L   | 0.618      | -            | -                | -                | -         |   -18.87 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2215 | 2024-05-04 | ENCE               | W   | 0.612      | 0.889        | 0.173 (0.094)    | 0.404 (0.220)    | 1 (0.612) |     3.87 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2230 | 2024-05-03 | Bad News Kangaroos | W   | 0.605      | -            | -                | -                | 1 (0.605) |     0.16 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2273 | 2024-05-01 | FORZE              | L   | 0.593      | -            | -                | -                | -         |   -18.32 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2295 | 2024-04-30 | Liquid             | L   | 0.586      | -            | -                | -                | -         |   -13.84 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2545 | 2024-04-19 | MIBR               | L   | 0.514      | -            | -                | -                | -         |   -12.68 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2570 | 2024-04-19 | Metizport          | W   | 0.511      | -            | -                | -                | 1 (0.511) |     0.25 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2596 | 2024-04-18 | 9z                 | L   | 0.506      | -            | -                | -                | -         |   -10.85 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     2887 | 2024-04-09 | HEROIC             | L   | 0.444      | -            | -                | -                | -         |    -9.27 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     2916 | 2024-04-08 | MOUZ               | L   | 0.438      | -            | -                | -                | -         |    -3.90 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     2928 | 2024-04-07 | Lynn Vision        | W   | 0.436      | -            | -                | -                | -         |     0.26 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3246 | 2024-03-22 | Gaimin Gladiators  | L   | 0.326      | -            | -                | -                | -         |   -10.08 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3264 | 2024-03-21 | FaZe               | L   | 0.320      | -            | -                | -                | -         |    -5.16 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3274 | 2024-03-21 | G2                 | L   | 0.319      | -            | -                | -                | -         |    -1.83 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3298 | 2024-03-20 | SAW                | W   | 0.313      | -            | -                | -                | -         |     0.46 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3314 | 2024-03-19 | ENCE               | W   | 0.306      | -            | -                | -                | -         |     1.83 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3322 | 2024-03-18 | KOI                | W   | 0.299      | -            | -                | -                | -         |     0.27 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3335 | 2024-03-17 | Lynn Vision        | L   | 0.294      | -            | -                | -                | -         |    -9.10 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3350 | 2024-03-17 | Legacy             | L   | 0.292      | -            | -                | -                | -         |    -9.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3699 | 2024-03-03 | Complexity         | W   | 0.200      | -            | -                | -                | -         |     2.37 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3733 | 2024-03-02 | Liquid             | W   | 0.192      | -            | -                | -                | -         |     1.09 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3755 | 2024-03-01 | Nouns              | W   | 0.186      | -            | -                | -                | -         |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     3888 | 2024-02-23 | 9z                 | L   | 0.141      | -            | -                | -                | -         |    -3.25 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     3902 | 2024-02-22 | 9z                 | W   | 0.134      | -            | -                | -                | -         |     1.14 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     3909 | 2024-02-22 | Imperial           | W   | 0.133      | -            | -                | -                | -         |     0.31 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4190 | 2024-02-10 | Metizport          | L   | 0.052      | -            | -                | -                | -         |    -1.64 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4191 | 2024-02-10 | ex-Anonymo         | W   | 0.052      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4195 | 2024-02-10 | Metizport          | L   | 0.052      | -            | -                | -                | -         |    -1.61 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($94,109.67)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.852 | $28,000.00     | $23,851.46      |
| 2024-06-02 |      0.805 | $10,000.00     | $8,051.71       |
| 2024-05-26 |      0.759 | $2,000.00      | $1,517.56       |
| 2024-05-12 |      0.665 | $12,000.00     | $7,982.06       |
| 2024-04-20 |      0.520 | $5,000.00      | $2,600.39       |
| 2024-04-14 |      0.477 | $5,000.00      | $2,386.39       |
| 2024-03-31 |      0.386 | $20,000.00     | $7,720.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
