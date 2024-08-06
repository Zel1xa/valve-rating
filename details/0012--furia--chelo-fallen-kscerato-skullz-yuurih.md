### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1607.7<br />
<br />
Final Rank Value (1607.7) = Starting Rank Value (1720.3) + Head To Head Adjustments (-112.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.620[<sup>2</sup>](#table1)
- Opponent Network: 0.402[<sup>2</sup>](#table1)
- LAN Wins: 0.898[<sup>2</sup>](#table1)

The average of these factors is 0.642<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1720.3
- 400 + ( ( 0.642 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1720.3


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
|           45 |      602 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.76 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      648 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.694 (0.694)    | 1 (1.000) |    22.75 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      659 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.958 (0.958)    | 1 (1.000) |     2.87 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      670 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.277 (0.277)    | 1 (1.000) |     2.90 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      728 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.24 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1329 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.807      | -            | -                | -                | -         |   -12.60 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1448 | 2024-06-06 | Complexity         | W   | 0.794      | 0.715        | 0.341 (0.194)    | -                | 1 (0.794) |    13.55 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1465 | 2024-06-06 | fnatic             | W   | 0.793      | 0.715        | 0.371 (0.210)    | 0.680 (0.386)    | 1 (0.793) |     8.62 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1487 | 2024-06-06 | Eternal Fire       | W   | 0.791      | 0.715        | 0.738 (0.418)    | 0.438 (0.248)    | 1 (0.791) |    15.14 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1517 | 2024-06-05 | BetBoom            | W   | 0.787      | 0.715        | 0.248 (0.139)    | 0.513 (0.289)    | 1 (0.787) |     6.47 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1534 | 2024-06-05 | BIG                | L   | 0.785      | -            | -                | -                | -         |   -19.78 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1612 | 2024-06-02 | GUN5               | L   | 0.767      | -            | -                | -                | -         |   -23.38 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1617 | 2024-06-02 | MOUZ NXT           | W   | 0.766      | 0.435        | -                | 0.962 (0.320)    | -         |     1.42 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1656 | 2024-06-01 | Zero Tenacity      | W   | 0.758      | 0.435        | 0.143 (0.047)    | 1.000 (0.330)    | -         |     1.50 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1707 | 2024-05-30 | RUBY               | W   | 0.746      | -            | -                | -                | -         |     0.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1815 | 2024-05-25 | 1WIN               | L   | 0.712      | -            | -                | -                | -         |   -21.65 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1827 | 2024-05-24 | Passion UA         | W   | 0.706      | 0.435        | 0.173 (0.053)    | 1.000 (0.307)    | -         |     0.88 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2390 | 2024-05-05 | Monte              | L   | 0.580      | -            | -                | -                | -         |   -17.73 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2410 | 2024-05-04 | ENCE               | W   | 0.573      | 0.889        | 0.173 (0.088)    | 0.422 (0.215)    | 1 (0.573) |     3.78 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2425 | 2024-05-03 | Bad News Kangaroos | W   | 0.567      | -            | -                | -                | 1 (0.567) |     0.16 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2468 | 2024-05-01 | FORZE              | L   | 0.554      | -            | -                | -                | -         |   -17.14 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2490 | 2024-04-30 | Liquid             | L   | 0.547      | -            | -                | -                | -         |   -10.35 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2740 | 2024-04-19 | MIBR               | L   | 0.475      | -            | -                | -                | -         |   -11.75 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2765 | 2024-04-19 | Metizport          | W   | 0.473      | -            | -                | -                | 1 (0.473) |     0.24 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2791 | 2024-04-18 | 9z                 | L   | 0.468      | -            | -                | -                | -         |   -10.08 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3082 | 2024-04-09 | HEROIC             | L   | 0.406      | -            | -                | -                | -         |    -8.63 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3111 | 2024-04-08 | MOUZ               | L   | 0.399      | -            | -                | -                | -         |    -3.75 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3123 | 2024-04-07 | Lynn Vision        | W   | 0.397      | -            | -                | -                | -         |     0.36 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3441 | 2024-03-22 | Gaimin Gladiators  | L   | 0.288      | -            | -                | -                | -         |    -8.90 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3459 | 2024-03-21 | FaZe               | L   | 0.282      | -            | -                | -                | -         |    -4.85 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3469 | 2024-03-21 | G2                 | L   | 0.280      | -            | -                | -                | -         |    -1.44 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3493 | 2024-03-20 | SAW                | W   | 0.274      | -            | -                | -                | -         |     0.40 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3509 | 2024-03-19 | ENCE               | W   | 0.267      | -            | -                | -                | -         |     1.70 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3517 | 2024-03-18 | KOI                | W   | 0.261      | -            | -                | -                | -         |     0.23 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3530 | 2024-03-17 | Lynn Vision        | L   | 0.255      | -            | -                | -                | -         |    -7.84 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3545 | 2024-03-17 | Legacy             | L   | 0.254      | -            | -                | -                | -         |    -7.84 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3894 | 2024-03-03 | Complexity         | W   | 0.161      | -            | -                | -                | -         |     2.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3928 | 2024-03-02 | Liquid             | W   | 0.154      | -            | -                | -                | -         |     1.60 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3950 | 2024-03-01 | Nouns              | W   | 0.148      | -            | -                | -                | -         |     0.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4083 | 2024-02-23 | 9z                 | L   | 0.102      | -            | -                | -                | -         |    -2.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4097 | 2024-02-22 | 9z                 | W   | 0.096      | -            | -                | -                | -         |     0.82 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4104 | 2024-02-22 | Imperial           | W   | 0.095      | -            | -                | -                | -         |     0.21 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4385 | 2024-02-10 | Metizport          | L   | 0.014      | -            | -                | -                | -         |    -0.43 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4386 | 2024-02-10 | ex-Anonymo         | W   | 0.014      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4390 | 2024-02-10 | Metizport          | L   | 0.013      | -            | -                | -                | -         |    -0.41 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($90,952.29)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.813 | $28,000.00     | $22,773.33      |
| 2024-06-02 |      0.767 | $10,000.00     | $7,666.67       |
| 2024-05-26 |      0.720 | $2,000.00      | $1,440.56       |
| 2024-05-12 |      0.627 | $12,000.00     | $7,520.00       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,407.87       |
| 2024-04-14 |      0.439 | $5,000.00      | $2,193.87       |
| 2024-03-31 |      0.347 | $20,000.00     | $6,950.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
