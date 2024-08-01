### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1219.4<br />
<br />
Final Rank Value (1219.4) = Starting Rank Value (1228.3) + Head To Head Adjustments (-9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.525[<sup>2</sup>](#table1)
- Opponent Network: 0.223[<sup>2</sup>](#table1)
- LAN Wins: 0.323[<sup>2</sup>](#table1)

The average of these factors is 0.402<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1228.3
- 400 + ( ( 0.402 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1228.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           76 |      182 | 2024-07-27 | Monte          | L   | 1.000      | -            | -                | -                | -         |   -22.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           75 |      241 | 2024-07-25 | RUBY           | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.544 (0.236)    | 0 (0.000) |     4.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           74 |     1157 | 2024-06-08 | Imperial       | L   | 0.843      | -            | -                | -                | -         |   -12.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           73 |     1218 | 2024-06-07 | Sharks         | W   | 0.836      | 0.450        | -                | 0.572 (0.215)    | 0 (0.000) |     6.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           72 |     1280 | 2024-06-06 | MIBR           | W   | 0.829      | 0.450        | 0.201 (0.075)    | 0.637 (0.238)    | 0 (0.000) |    18.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           71 |     1352 | 2024-06-05 | RED Canids     | L   | 0.823      | -            | -                | -                | -         |   -16.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           70 |     1403 | 2024-06-04 | Fluxo          | W   | 0.816      | 0.450        | 0.122 (0.045)    | 0.701 (0.258)    | 0 (0.000) |     7.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           69 |     1485 | 2024-06-01 | G2             | L   | 0.796      | -            | -                | -                | -         |    -0.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           68 |     1575 | 2024-05-29 | Vitality       | W   | 0.776      | 0.624        | 0.591 (0.286)    | -                | 1 (0.776) |    23.78 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           67 |     1615 | 2024-05-27 | Liquid         | W   | 0.763      | 0.624        | 0.322 (0.153)    | 0.429 (0.204)    | 1 (0.763) |    20.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           66 |     1625 | 2024-05-27 | MOUZ           | W   | 0.762      | 0.624        | 1.000 (0.476)    | -                | 1 (0.762) |    23.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           65 |     1722 | 2024-05-22 | Imperial       | L   | 0.730      | -            | -                | -                | -         |    -8.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           64 |     1726 | 2024-05-22 | Imperial       | L   | 0.729      | -            | -                | -                | -         |    -8.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           63 |     1752 | 2024-05-22 | Corinthians    | W   | 0.727      | -            | -                | -                | 0 (0.000) |     0.51 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           62 |     1753 | 2024-05-22 | Corinthians    | W   | 0.727      | -            | -                | -                | 0 (0.000) |     0.51 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           61 |     1822 | 2024-05-20 | W7M            | W   | 0.716      | 0.450        | -                | 0.625 (0.202)    | -         |     2.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           60 |     1825 | 2024-05-20 | W7M            | W   | 0.716      | 0.450        | -                | 0.625 (0.202)    | -         |     2.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |     1826 | 2024-05-20 | BESTIA         | L   | 0.716      | -            | -                | -                | -         |   -17.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1829 | 2024-05-20 | BESTIA         | W   | 0.715      | 0.450        | 0.089 (0.029)    | 0.738 (0.238)    | -         |     5.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1864 | 2024-05-19 | RED Canids     | L   | 0.708      | -            | -                | -                | -         |   -14.08 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           56 |     1889 | 2024-05-18 | Fluxo          | W   | 0.702      | 0.371        | 0.122 (0.032)    | -                | -         |     8.49 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           55 |     1955 | 2024-05-16 | ODDIK          | W   | 0.689      | 0.371        | 0.096 (0.025)    | 0.822 (0.210)    | -         |     4.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1963 | 2024-05-16 | Imperial       | L   | 0.688      | -            | -                | -                | -         |    -7.30 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     2000 | 2024-05-15 | RED Canids     | W   | 0.683      | 0.450        | -                | 0.753 (0.232)    | -         |     7.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     2002 | 2024-05-15 | RED Canids     | L   | 0.683      | -            | -                | -                | -         |   -14.33 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     2009 | 2024-05-15 | Sharks         | W   | 0.682      | -            | -                | -                | -         |     5.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     2067 | 2024-05-14 | Smoke          | W   | 0.676      | -            | -                | -                | -         |     2.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     2071 | 2024-05-14 | Smoke          | W   | 0.676      | -            | -                | -                | -         |     2.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     2081 | 2024-05-14 | Galorys        | W   | 0.675      | -            | -                | -                | -         |     3.84 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     2101 | 2024-05-13 | Galorys        | W   | 0.670      | -            | -                | -                | -         |     3.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     2108 | 2024-05-13 | inSanitY       | W   | 0.668      | -            | -                | -                | -         |     4.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     2122 | 2024-05-12 | inSanitY       | W   | 0.663      | -            | -                | -                | -         |     4.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     2127 | 2024-05-12 | paiN           | L   | 0.662      | -            | -                | -                | -         |    -5.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     2154 | 2024-05-11 | KRÜ            | W   | 0.656      | -            | -                | -                | -         |     4.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     2181 | 2024-05-10 | inSanitY       | W   | 0.650      | -            | -                | -                | -         |     4.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     2225 | 2024-05-08 | Sharks         | W   | 0.636      | -            | -                | -                | -         |     5.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     2267 | 2024-05-06 | Vikings KR     | W   | 0.621      | -            | -                | -                | -         |     2.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     2361 | 2024-05-01 | Case           | W   | 0.589      | -            | -                | -                | -         |     3.71 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     2362 | 2024-05-01 | Case           | W   | 0.589      | -            | -                | -                | -         |     3.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           37 |     2640 | 2024-04-19 | OG             | L   | 0.510      | -            | -                | -                | -         |   -10.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           36 |     2691 | 2024-04-18 | Imperial       | L   | 0.503      | -            | -                | -                | -         |    -5.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2698 | 2024-04-18 | FURIA          | W   | 0.502      | 0.589        | 0.286 (0.085)    | -                | 1 (0.502) |    15.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     3024 | 2024-04-08 | HEROIC         | L   | 0.433      | -            | -                | -                | -         |    -1.30 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     3034 | 2024-04-07 | G2             | L   | 0.431      | -            | -                | -                | -         |    -0.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     3160 | 2024-04-03 | Galorys        | L   | 0.401      | -            | -                | -                | -         |   -10.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     3161 | 2024-04-03 | Galorys        | L   | 0.401      | -            | -                | -                | -         |   -10.37 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     3162 | 2024-04-03 | adalYamigos    | L   | 0.401      | -            | -                | -                | -         |   -12.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     3163 | 2024-04-03 | adalYamigos    | L   | 0.401      | -            | -                | -                | -         |   -12.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     3332 | 2024-03-26 | Solid          | W   | 0.348      | -            | -                | -                | -         |     1.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     3333 | 2024-03-26 | Solid          | W   | 0.348      | -            | -                | -                | -         |     1.71 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     3542 | 2024-03-14 | ODDIK          | L   | 0.268      | -            | -                | -                | -         |    -6.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     3543 | 2024-03-14 | ODDIK          | L   | 0.268      | -            | -                | -                | -         |    -6.43 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     3787 | 2024-03-05 | Sharks         | L   | 0.208      | -            | -                | -                | -         |    -5.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     3788 | 2024-03-05 | Sharks         | L   | 0.208      | -            | -                | -                | -         |    -5.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     3789 | 2024-03-05 | Fluxo          | L   | 0.208      | -            | -                | -                | -         |    -4.77 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     3790 | 2024-03-05 | Fluxo          | L   | 0.208      | -            | -                | -                | -         |    -4.84 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     4023 | 2024-02-23 | FURIA          | W   | 0.137      | -            | -                | -                | -         |     4.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     4026 | 2024-02-23 | BESTIA         | W   | 0.135      | -            | -                | -                | -         |     1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     4039 | 2024-02-22 | FURIA          | L   | 0.130      | -            | -                | -                | -         |    -0.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     4046 | 2024-02-22 | BESTIA         | W   | 0.129      | -            | -                | -                | -         |     0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     4092 | 2024-02-20 | Solid          | W   | 0.116      | -            | -                | -                | -         |     0.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     4095 | 2024-02-20 | Case           | W   | 0.116      | -            | -                | -                | -         |     0.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4099 | 2024-02-20 | Salao do Corte | W   | 0.116      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4151 | 2024-02-18 | LA RUGONETA    | L   | 0.101      | -            | -                | -                | -         |    -3.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4193 | 2024-02-16 | Fluxo          | L   | 0.089      | -            | -                | -                | -         |    -2.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4218 | 2024-02-15 | Imperial       | L   | 0.083      | -            | -                | -                | -         |    -1.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4219 | 2024-02-15 | Case           | W   | 0.083      | -            | -                | -                | -         |     0.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4223 | 2024-02-15 | KRÜ            | W   | 0.083      | -            | -                | -                | -         |     0.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4248 | 2024-02-14 | 2GAME          | W   | 0.077      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4300 | 2024-02-13 | paiN           | W   | 0.070      | -            | -                | -                | -         |     1.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4301 | 2024-02-13 | paiN           | W   | 0.070      | -            | -                | -                | -         |     1.49 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4302 | 2024-02-13 | MIBR           | W   | 0.070      | -            | -                | -                | -         |     1.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4303 | 2024-02-13 | MIBR           | W   | 0.070      | -            | -                | -                | -         |     1.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4321 | 2024-02-12 | LA RUGONETA    | W   | 0.062      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4405 | 2024-02-04 | Imperial       | L   | 0.009      | -            | -                | -                | -         |    -0.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4426 | 2024-02-03 | W7M            | W   | 0.004      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,080.19)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-09 |      0.849 | $7,500.00      | $6,368.06       |
| 2024-06-02 |      0.802 | $20,000.00     | $16,033.33      |
| 2024-05-19 |      0.708 | $4,000.00      | $2,833.33       |
| 2024-05-16 |      0.688 | $5,000.00      | $3,441.67       |
| 2024-05-12 |      0.662 | $15,000.00     | $9,933.33       |
| 2024-04-20 |      0.516 | $5,000.00      | $2,578.70       |
| 2024-04-14 |      0.473 | $4,000.00      | $1,891.76       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
