### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1232.7<br />
<br />
Final Rank Value (1232.7) = Starting Rank Value (1217.5) + Head To Head Adjustments (15.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.535[<sup>1</sup>](#table2)
- Bounty Collected: 0.526[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.313[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1217.5
- 400 + ( ( 0.400 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1217.5


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
|           55 |      244 | 2024-07-27 | Monte          | L   | 1.000      | -            | -                | -                | -         |   -23.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |      303 | 2024-07-25 | RUBY           | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.520 (0.226)    | 0 (0.000) |     4.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1175 | 2024-06-08 | Imperial       | L   | 0.828      | -            | -                | -                | -         |   -13.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1228 | 2024-06-07 | Sharks         | W   | 0.821      | 0.450        | -                | 0.583 (0.215)    | 0 (0.000) |     5.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1286 | 2024-06-06 | MIBR           | W   | 0.815      | 0.450        | 0.210 (0.077)    | 0.682 (0.250)    | 0 (0.000) |    19.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1355 | 2024-06-05 | RED Canids     | L   | 0.808      | -            | -                | -                | -         |   -18.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1405 | 2024-06-04 | Fluxo          | W   | 0.802      | 0.450        | 0.125 (0.045)    | 0.746 (0.269)    | 0 (0.000) |     6.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1484 | 2024-06-01 | G2             | L   | 0.781      | -            | -                | -                | -         |    -0.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1573 | 2024-05-29 | Vitality       | W   | 0.761      | 0.624        | 0.650 (0.309)    | -                | 1 (0.761) |    23.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1613 | 2024-05-27 | Liquid         | W   | 0.749      | 0.624        | 0.316 (0.148)    | 0.478 (0.223)    | 1 (0.749) |    20.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1623 | 2024-05-27 | MOUZ           | W   | 0.747      | 0.624        | 1.000 (0.466)    | -                | 1 (0.747) |    22.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1717 | 2024-05-22 | Imperial       | L   | 0.715      | -            | -                | -                | -         |    -9.92 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1721 | 2024-05-22 | Imperial       | L   | 0.715      | -            | -                | -                | -         |   -10.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1800 | 2024-05-20 | W7M            | W   | 0.702      | -            | -                | -                | 0 (0.000) |     1.91 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1803 | 2024-05-20 | W7M            | W   | 0.701      | -            | -                | -                | 0 (0.000) |     1.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1804 | 2024-05-20 | BESTIA         | L   | 0.701      | -            | -                | -                | -         |   -17.77 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1807 | 2024-05-20 | BESTIA         | W   | 0.701      | 0.450        | 0.091 (0.029)    | 0.756 (0.238)    | -         |     4.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1833 | 2024-05-19 | RED Canids     | L   | 0.694      | -            | -                | -                | -         |   -15.12 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1858 | 2024-05-18 | Fluxo          | W   | 0.687      | 0.371        | 0.125 (0.032)    | -                | -         |     7.05 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     1923 | 2024-05-16 | ODDIK          | W   | 0.675      | 0.371        | 0.098 (0.025)    | 0.857 (0.214)    | -         |     3.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     1931 | 2024-05-16 | Imperial       | L   | 0.674      | -            | -                | -                | -         |    -9.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     1968 | 2024-05-15 | RED Canids     | W   | 0.669      | 0.450        | -                | 0.733 (0.221)    | -         |     5.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     1970 | 2024-05-15 | RED Canids     | L   | 0.668      | -            | -                | -                | -         |   -15.46 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     1977 | 2024-05-15 | Sharks         | W   | 0.668      | -            | -                | -                | -         |     4.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2029 | 2024-05-14 | Smoke          | W   | 0.662      | -            | -                | -                | -         |     1.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2033 | 2024-05-14 | Smoke          | W   | 0.661      | -            | -                | -                | -         |     1.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2043 | 2024-05-14 | Galorys        | W   | 0.660      | -            | -                | -                | -         |     2.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2062 | 2024-05-13 | Galorys        | W   | 0.655      | -            | -                | -                | -         |     2.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2081 | 2024-05-12 | inSanitY       | W   | 0.649      | -            | -                | -                | -         |     3.30 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2086 | 2024-05-12 | paiN           | L   | 0.648      | -            | -                | -                | -         |    -6.80 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2113 | 2024-05-11 | KRÜ            | W   | 0.641      | -            | -                | -                | -         |     3.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2140 | 2024-05-10 | inSanitY       | W   | 0.635      | -            | -                | -                | -         |     3.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2181 | 2024-05-08 | Sharks         | W   | 0.622      | -            | -                | -                | -         |     4.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2223 | 2024-05-06 | Vikings KR     | W   | 0.607      | -            | -                | -                | -         |     1.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2315 | 2024-05-01 | Case           | W   | 0.574      | 0.450        | -                | 0.750 (0.194)    | -         |     2.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2316 | 2024-05-01 | Case           | W   | 0.574      | 0.450        | -                | 0.750 (0.194)    | -         |     2.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2586 | 2024-04-19 | OG             | L   | 0.496      | -            | -                | -                | -         |   -11.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2636 | 2024-04-18 | Imperial       | L   | 0.489      | -            | -                | -                | -         |    -6.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2642 | 2024-04-18 | FURIA          | W   | 0.487      | 0.589        | 0.284 (0.081)    | -                | 1 (0.487) |    14.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     2965 | 2024-04-08 | HEROIC         | L   | 0.418      | -            | -                | -                | -         |    -1.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     2975 | 2024-04-07 | G2             | L   | 0.417      | -            | -                | -                | -         |    -0.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     3926 | 2024-02-23 | FURIA          | W   | 0.122      | -            | -                | -                | -         |     3.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     3929 | 2024-02-23 | BESTIA         | W   | 0.121      | -            | -                | -                | -         |     0.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     3940 | 2024-02-22 | FURIA          | L   | 0.115      | -            | -                | -                | -         |    -0.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     3946 | 2024-02-22 | BESTIA         | W   | 0.114      | -            | -                | -                | -         |     0.89 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     3991 | 2024-02-20 | Solid          | W   | 0.102      | -            | -                | -                | -         |     0.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     3994 | 2024-02-20 | Case           | W   | 0.101      | -            | -                | -                | -         |     0.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     3998 | 2024-02-20 | Salao do Corte | W   | 0.101      | -            | -                | -                | -         |     0.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4050 | 2024-02-18 | LA RUGONETA    | L   | 0.086      | -            | -                | -                | -         |    -2.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4091 | 2024-02-16 | Fluxo          | L   | 0.074      | -            | -                | -                | -         |    -1.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4116 | 2024-02-15 | Imperial       | L   | 0.068      | -            | -                | -                | -         |    -1.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4117 | 2024-02-15 | Case           | W   | 0.068      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4121 | 2024-02-15 | KRÜ            | W   | 0.068      | -            | -                | -                | -         |     0.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4146 | 2024-02-14 | 2GAME          | W   | 0.062      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4211 | 2024-02-12 | LA RUGONETA    | W   | 0.048      | -            | -                | -                | -         |     0.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,192.29)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-09 |      0.834 | $7,500.00      | $6,257.99       |
| 2024-06-02 |      0.787 | $20,000.00     | $15,739.81      |
| 2024-05-19 |      0.694 | $4,000.00      | $2,774.63       |
| 2024-05-16 |      0.674 | $5,000.00      | $3,368.29       |
| 2024-05-12 |      0.648 | $15,000.00     | $9,713.19       |
| 2024-04-20 |      0.501 | $5,000.00      | $2,505.32       |
| 2024-04-14 |      0.458 | $4,000.00      | $1,833.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
