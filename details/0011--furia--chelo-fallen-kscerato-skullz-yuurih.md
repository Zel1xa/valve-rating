### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1602.1<br />
<br />
Final Rank Value (1602.1) = Starting Rank Value (1742.1) + Head To Head Adjustments (-140.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.648[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.417[<sup>2</sup>](#table1)
- LAN Wins: 0.924[<sup>2</sup>](#table1)

The average of these factors is 0.652<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1742.1
- 400 + ( ( 0.652 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1742.1


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
|           45 |      446 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.14 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      497 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.719 (0.719)    | 1 (1.000) |    22.72 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      508 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.186 (0.186)    | 0.970 (0.970)    | 1 (1.000) |     2.94 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      519 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.106 (0.106)    | 0.322 (0.322)    | 1 (1.000) |     3.29 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      577 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -3.96 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1179 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.840      | -            | -                | -                | -         |   -16.68 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1307 | 2024-06-06 | Complexity         | W   | 0.826      | 0.715        | 0.318 (0.188)    | -                | 1 (0.826) |    13.72 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1324 | 2024-06-06 | fnatic             | W   | 0.826      | 0.715        | 0.292 (0.172)    | 0.568 (0.335)    | 1 (0.826) |     5.28 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1347 | 2024-06-06 | Eternal Fire       | W   | 0.824      | 0.715        | 0.757 (0.446)    | 0.461 (0.272)    | 1 (0.824) |    16.02 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1379 | 2024-06-05 | BetBoom            | W   | 0.819      | 0.715        | 0.257 (0.151)    | 0.551 (0.323)    | 1 (0.819) |     6.84 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1396 | 2024-06-05 | BIG                | L   | 0.818      | -            | -                | -                | -         |   -21.76 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1474 | 2024-06-02 | GUN5               | L   | 0.799      | -            | -                | -                | -         |   -24.28 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1480 | 2024-06-02 | MOUZ NXT           | W   | 0.798      | 0.435        | 0.141 (0.049)    | 1.000 (0.347)    | -         |     1.42 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1519 | 2024-06-01 | Zero Tenacity      | W   | 0.791      | 0.435        | -                | 1.000 (0.344)    | -         |     1.43 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1570 | 2024-05-30 | RUBY               | W   | 0.778      | -            | -                | -                | -         |     0.62 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1680 | 2024-05-25 | 1WIN               | L   | 0.745      | -            | -                | -                | -         |   -22.74 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1692 | 2024-05-24 | Passion UA         | W   | 0.739      | 0.435        | 0.173 (0.055)    | 1.000 (0.321)    | -         |     0.85 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2292 | 2024-05-05 | Monte              | L   | 0.612      | -            | -                | -                | -         |   -18.66 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2312 | 2024-05-04 | ENCE               | W   | 0.606      | 0.889        | 0.173 (0.093)    | 0.403 (0.217)    | 1 (0.606) |     3.84 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2327 | 2024-05-03 | Bad News Kangaroos | W   | 0.599      | -            | -                | -                | 1 (0.599) |     0.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2372 | 2024-05-01 | FORZE              | L   | 0.587      | -            | -                | -                | -         |   -18.13 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2395 | 2024-04-30 | Liquid             | L   | 0.580      | -            | -                | -                | -         |   -12.59 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2651 | 2024-04-19 | MIBR               | L   | 0.508      | -            | -                | -                | -         |   -12.63 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2677 | 2024-04-19 | Metizport          | W   | 0.505      | -            | -                | -                | 1 (0.505) |     0.25 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2704 | 2024-04-18 | 9z                 | L   | 0.500      | -            | -                | -                | -         |   -14.98 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     2999 | 2024-04-09 | HEROIC             | L   | 0.438      | -            | -                | -                | -         |    -9.39 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3027 | 2024-04-08 | MOUZ               | L   | 0.432      | -            | -                | -                | -         |    -3.85 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3039 | 2024-04-07 | Lynn Vision        | W   | 0.430      | -            | -                | -                | -         |     0.26 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3370 | 2024-03-22 | Gaimin Gladiators  | L   | 0.320      | -            | -                | -                | -         |    -9.89 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3388 | 2024-03-21 | FaZe               | L   | 0.314      | -            | -                | -                | -         |    -5.10 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3398 | 2024-03-21 | G2                 | L   | 0.313      | -            | -                | -                | -         |    -1.73 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3422 | 2024-03-20 | SAW                | W   | 0.307      | -            | -                | -                | -         |     0.46 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3438 | 2024-03-19 | ENCE               | W   | 0.300      | -            | -                | -                | -         |     1.77 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3446 | 2024-03-18 | KOI                | W   | 0.293      | -            | -                | -                | -         |     0.12 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3459 | 2024-03-17 | Lynn Vision        | L   | 0.288      | -            | -                | -                | -         |    -8.91 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3474 | 2024-03-17 | Legacy             | L   | 0.286      | -            | -                | -                | -         |    -8.84 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3834 | 2024-03-03 | Complexity         | W   | 0.194      | -            | -                | -                | -         |     2.23 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3868 | 2024-03-02 | Liquid             | W   | 0.186      | -            | -                | -                | -         |     1.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3891 | 2024-03-01 | Nouns              | W   | 0.180      | -            | -                | -                | -         |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4029 | 2024-02-23 | 9z                 | L   | 0.135      | -            | -                | -                | -         |    -4.01 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4045 | 2024-02-22 | 9z                 | W   | 0.128      | -            | -                | -                | -         |     0.22 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4053 | 2024-02-22 | Imperial           | W   | 0.127      | -            | -                | -                | -         |     0.28 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4344 | 2024-02-10 | Metizport          | L   | 0.046      | -            | -                | -                | -         |    -1.45 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4345 | 2024-02-10 | ex-Anonymo         | W   | 0.046      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4349 | 2024-02-10 | Metizport          | L   | 0.046      | -            | -                | -                | -         |    -1.42 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($93,617.29)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.846 | $28,000.00     | $23,683.33      |
| 2024-06-02 |      0.799 | $10,000.00     | $7,991.67       |
| 2024-05-26 |      0.753 | $2,000.00      | $1,505.56       |
| 2024-05-12 |      0.659 | $12,000.00     | $7,910.00       |
| 2024-04-20 |      0.514 | $5,000.00      | $2,570.37       |
| 2024-04-14 |      0.471 | $5,000.00      | $2,356.37       |
| 2024-03-31 |      0.380 | $20,000.00     | $7,600.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
