### Roster Details<br />
Team Name: FURIA<br />
Roster: chelo, FalleN, KSCERATO, skullz, yuurih<br />
Global Rank: [12](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1607.9<br />
<br />
Final Rank Value (1607.9) = Starting Rank Value (1722.4) + Head To Head Adjustments (-114.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.647[<sup>1</sup>](#table2)
- Bounty Collected: 0.621[<sup>2</sup>](#table1)
- Opponent Network: 0.413[<sup>2</sup>](#table1)
- LAN Wins: 0.899[<sup>2</sup>](#table1)

The average of these factors is 0.645<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1722.4
- 400 + ( ( 0.645 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1722.4


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
|           45 |      581 | 2024-07-19 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -5.70 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           44 |      627 | 2024-07-18 | The MongolZ        | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.710 (0.710)    | 1 (1.000) |    22.74 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           43 |      638 | 2024-07-18 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.983 (0.983)    | 1 (1.000) |     2.84 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           42 |      649 | 2024-07-18 | FlyQuest           | W   | 1.000      | 1.000        | 0.104 (0.104)    | 0.286 (0.286)    | 1 (1.000) |     2.94 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           41 |      707 | 2024-07-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -4.24 | chelo, FalleN, KSCERATO, skullz, yuurih |
|           40 |     1308 | 2024-06-08 | Ninjas in Pyjamas  | L   | 0.813      | -            | -                | -                | -         |   -12.66 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           39 |     1427 | 2024-06-06 | Complexity         | W   | 0.800      | 0.715        | 0.342 (0.196)    | -                | 1 (0.800) |    13.70 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           38 |     1444 | 2024-06-06 | fnatic             | W   | 0.799      | 0.715        | 0.371 (0.212)    | 0.697 (0.398)    | 1 (0.799) |     8.70 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           37 |     1466 | 2024-06-06 | Eternal Fire       | W   | 0.797      | 0.715        | 0.740 (0.422)    | 0.449 (0.256)    | 1 (0.797) |    15.28 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           36 |     1496 | 2024-06-05 | BetBoom            | W   | 0.793      | 0.715        | 0.249 (0.141)    | 0.529 (0.300)    | 1 (0.793) |     6.54 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           35 |     1513 | 2024-06-05 | BIG                | L   | 0.791      | -            | -                | -                | -         |   -19.89 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           34 |     1591 | 2024-06-02 | GUN5               | L   | 0.773      | -            | -                | -                | -         |   -23.58 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           33 |     1596 | 2024-06-02 | MOUZ NXT           | W   | 0.772      | 0.435        | -                | 0.987 (0.331)    | -         |     1.42 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           32 |     1635 | 2024-06-01 | Zero Tenacity      | W   | 0.764      | 0.435        | 0.143 (0.048)    | 1.000 (0.332)    | -         |     1.48 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           31 |     1686 | 2024-05-30 | RUBY               | W   | 0.752      | -            | -                | -                | -         |     0.57 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           30 |     1794 | 2024-05-25 | 1WIN               | L   | 0.718      | -            | -                | -                | -         |   -21.84 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           29 |     1806 | 2024-05-24 | Passion UA         | W   | 0.713      | 0.435        | 0.173 (0.053)    | 1.000 (0.310)    | -         |     0.87 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           28 |     2369 | 2024-05-05 | Monte              | L   | 0.586      | -            | -                | -                | -         |   -17.91 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           27 |     2389 | 2024-05-04 | ENCE               | W   | 0.579      | 0.889        | 0.174 (0.090)    | 0.432 (0.223)    | 1 (0.579) |     3.78 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           26 |     2404 | 2024-05-03 | Bad News Kangaroos | W   | 0.573      | -            | -                | -                | 1 (0.573) |     0.17 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           25 |     2447 | 2024-05-01 | FORZE              | L   | 0.560      | -            | -                | -                | -         |   -17.33 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           24 |     2469 | 2024-04-30 | Liquid             | L   | 0.553      | -            | -                | -                | -         |   -10.47 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           23 |     2719 | 2024-04-19 | MIBR               | L   | 0.482      | -            | -                | -                | -         |   -11.85 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           22 |     2744 | 2024-04-19 | Metizport          | W   | 0.479      | -            | -                | -                | 1 (0.479) |     0.18 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           21 |     2770 | 2024-04-18 | 9z                 | L   | 0.474      | -            | -                | -                | -         |   -10.19 | chelo, FalleN, KSCERATO, kye, yuurih    |
|           20 |     3061 | 2024-04-09 | HEROIC             | L   | 0.412      | -            | -                | -                | -         |    -8.73 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           19 |     3090 | 2024-04-08 | MOUZ               | L   | 0.405      | -            | -                | -                | -         |    -3.79 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           18 |     3102 | 2024-04-07 | Lynn Vision        | W   | 0.404      | -            | -                | -                | -         |     0.35 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           17 |     3420 | 2024-03-22 | Gaimin Gladiators  | L   | 0.294      | -            | -                | -                | -         |    -9.09 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           16 |     3438 | 2024-03-21 | FaZe               | L   | 0.288      | -            | -                | -                | -         |    -4.92 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           15 |     3448 | 2024-03-21 | G2                 | L   | 0.286      | -            | -                | -                | -         |    -1.48 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           14 |     3472 | 2024-03-20 | SAW                | W   | 0.280      | -            | -                | -                | -         |     0.41 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           13 |     3488 | 2024-03-19 | ENCE               | W   | 0.273      | -            | -                | -                | -         |     1.72 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           12 |     3496 | 2024-03-18 | KOI                | W   | 0.267      | -            | -                | -                | -         |     0.24 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           11 |     3509 | 2024-03-17 | Lynn Vision        | L   | 0.261      | -            | -                | -                | -         |    -8.03 | arT, chelo, FalleN, KSCERATO, yuurih    |
|           10 |     3524 | 2024-03-17 | Legacy             | L   | 0.260      | -            | -                | -                | -         |    -8.03 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            9 |     3873 | 2024-03-03 | Complexity         | W   | 0.167      | -            | -                | -                | -         |     2.13 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            8 |     3907 | 2024-03-02 | Liquid             | W   | 0.160      | -            | -                | -                | -         |     1.66 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            7 |     3929 | 2024-03-01 | Nouns              | W   | 0.154      | -            | -                | -                | -         |     0.05 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            6 |     4062 | 2024-02-23 | 9z                 | L   | 0.108      | -            | -                | -                | -         |    -2.49 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            5 |     4076 | 2024-02-22 | 9z                 | W   | 0.102      | -            | -                | -                | -         |     0.87 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            4 |     4083 | 2024-02-22 | Imperial           | W   | 0.101      | -            | -                | -                | -         |     0.23 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            3 |     4364 | 2024-02-10 | Metizport          | L   | 0.020      | -            | -                | -                | -         |    -0.63 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            2 |     4365 | 2024-02-10 | ex-Anonymo         | W   | 0.020      | -            | -                | -                | -         |     0.00 | arT, chelo, FalleN, KSCERATO, yuurih    |
|            1 |     4369 | 2024-02-10 | Metizport          | L   | 0.019      | -            | -                | -                | -         |    -0.60 | arT, chelo, FalleN, KSCERATO, yuurih    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($91,453.40)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.28) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $40,000.00     | $40,000.00      |
| 2024-06-09 |      0.819 | $28,000.00     | $22,944.44      |
| 2024-06-02 |      0.773 | $10,000.00     | $7,727.78       |
| 2024-05-26 |      0.726 | $2,000.00      | $1,452.78       |
| 2024-05-12 |      0.633 | $12,000.00     | $7,593.33       |
| 2024-04-20 |      0.488 | $5,000.00      | $2,438.43       |
| 2024-04-14 |      0.445 | $5,000.00      | $2,224.42       |
| 2024-03-31 |      0.354 | $20,000.00     | $7,072.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
