### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1447.0<br />
<br />
Final Rank Value (1447.0) = Starting Rank Value (1548.7) + Head To Head Adjustments (-101.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.717[<sup>1</sup>](#table2)
- Bounty Collected: 0.551[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.704[<sup>2</sup>](#table1)

The average of these factors is 0.558<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1548.7
- 400 + ( ( 0.558 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1548.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |      352 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      411 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.479 (0.208)    | 0 (0.000) |     1.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1037 | 2024-06-16 | fnatic            | W   | 0.862      | 0.548        | 0.371 (0.175)    | 0.680 (0.321)    | 1 (0.862) |    13.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1048 | 2024-06-16 | KOI               | W   | 0.860      | -            | -                | -                | 1 (0.860) |     3.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1069 | 2024-06-15 | paiN              | W   | 0.854      | 0.548        | 0.324 (0.152)    | 0.839 (0.393)    | 1 (0.854) |     9.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1088 | 2024-06-15 | BESTIA            | W   | 0.852      | 0.548        | 0.096 (0.045)    | 0.776 (0.363)    | 1 (0.852) |     2.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1107 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.847      | -            | -                | -                | -         |    -7.79 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1317 | 2024-06-08 | Imperial          | L   | 0.808      | -            | -                | -                | -         |   -18.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1374 | 2024-06-07 | Sharks            | W   | 0.802      | 0.450        | -                | 0.547 (0.197)    | 0 (0.000) |     2.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1432 | 2024-06-06 | MIBR              | W   | 0.795      | 0.450        | 0.207 (0.074)    | 0.633 (0.226)    | -         |    11.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1501 | 2024-06-05 | RED Canids        | L   | 0.788      | -            | -                | -                | -         |   -21.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1551 | 2024-06-04 | Fluxo             | W   | 0.782      | 0.450        | 0.123 (0.043)    | 0.701 (0.247)    | -         |     2.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1632 | 2024-06-01 | G2                | L   | 0.761      | -            | -                | -                | -         |    -1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1722 | 2024-05-29 | Vitality          | W   | 0.741      | 0.624        | 0.647 (0.299)    | -                | 1 (0.741) |    21.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1762 | 2024-05-27 | Liquid            | W   | 0.729      | 0.624        | 0.383 (0.174)    | 0.437 (0.199)    | 1 (0.729) |    16.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1772 | 2024-05-27 | MOUZ              | W   | 0.727      | 0.624        | 1.000 (0.454)    | -                | 1 (0.727) |    21.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1867 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |   -15.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1871 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |   -16.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1950 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1953 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1954 | 2024-05-20 | BESTIA            | L   | 0.681      | -            | -                | -                | -         |   -20.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1957 | 2024-05-20 | BESTIA            | W   | 0.681      | 0.450        | -                | 0.776 (0.238)    | -         |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1984 | 2024-05-19 | RED Canids        | L   | 0.674      | -            | -                | -                | -         |   -18.55 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     2009 | 2024-05-18 | Fluxo             | W   | 0.667      | -            | -                | -                | -         |     2.19 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2074 | 2024-05-16 | ODDIK             | W   | 0.655      | -            | -                | -                | -         |     0.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2082 | 2024-05-16 | Imperial          | L   | 0.654      | -            | -                | -                | -         |   -15.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2119 | 2024-05-15 | RED Canids        | W   | 0.649      | 0.450        | -                | 0.732 (0.214)    | -         |     2.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2121 | 2024-05-15 | RED Canids        | L   | 0.648      | -            | -                | -                | -         |   -18.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2128 | 2024-05-15 | Sharks            | W   | 0.648      | -            | -                | -                | -         |     1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2180 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2184 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2194 | 2024-05-14 | Galorys           | W   | 0.640      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2213 | 2024-05-13 | Galorys           | W   | 0.635      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2232 | 2024-05-12 | inSanitY          | W   | 0.629      | -            | -                | -                | -         |     0.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2237 | 2024-05-12 | paiN              | L   | 0.628      | -            | -                | -                | -         |   -13.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2264 | 2024-05-11 | KRÜ               | W   | 0.621      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2291 | 2024-05-10 | inSanitY          | W   | 0.615      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2333 | 2024-05-08 | Sharks            | W   | 0.602      | -            | -                | -                | -         |     0.87 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2375 | 2024-05-06 | Vikings KR        | W   | 0.587      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2467 | 2024-05-01 | Case              | W   | 0.554      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2468 | 2024-05-01 | Case              | W   | 0.554      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2739 | 2024-04-19 | OG                | L   | 0.476      | -            | -                | -                | -         |   -14.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2789 | 2024-04-18 | Imperial          | L   | 0.469      | -            | -                | -                | -         |   -11.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2795 | 2024-04-18 | FURIA             | W   | 0.467      | 0.589        | 0.284 (0.078)    | -                | 1 (0.467) |    10.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3118 | 2024-04-08 | HEROIC            | L   | 0.398      | -            | -                | -                | -         |    -6.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3128 | 2024-04-07 | G2                | L   | 0.397      | -            | -                | -                | -         |    -0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4087 | 2024-02-23 | FURIA             | W   | 0.102      | -            | -                | -                | -         |     2.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4090 | 2024-02-23 | BESTIA            | W   | 0.101      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4101 | 2024-02-22 | FURIA             | L   | 0.095      | -            | -                | -                | -         |    -0.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4107 | 2024-02-22 | BESTIA            | W   | 0.094      | -            | -                | -                | -         |     0.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4152 | 2024-02-20 | Solid             | W   | 0.082      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4155 | 2024-02-20 | Case              | W   | 0.082      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4159 | 2024-02-20 | Salao do Corte    | W   | 0.081      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4211 | 2024-02-18 | LA RUGONETA       | L   | 0.066      | -            | -                | -                | -         |    -2.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4253 | 2024-02-16 | Fluxo             | L   | 0.054      | -            | -                | -                | -         |    -1.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4278 | 2024-02-15 | Imperial          | L   | 0.049      | -            | -                | -                | -         |    -1.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4279 | 2024-02-15 | Case              | W   | 0.048      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4283 | 2024-02-15 | KRÜ               | W   | 0.048      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4308 | 2024-02-14 | 2GAME             | W   | 0.042      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4373 | 2024-02-12 | LA RUGONETA       | W   | 0.028      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129,186.97)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.862 | $100,000.00    | $86,199.07      |
| 2024-06-09 |      0.814 | $7,500.00      | $6,108.68       |
| 2024-06-02 |      0.767 | $20,000.00     | $15,341.67      |
| 2024-05-19 |      0.674 | $4,000.00      | $2,695.00       |
| 2024-05-16 |      0.654 | $5,000.00      | $3,268.75       |
| 2024-05-12 |      0.628 | $15,000.00     | $9,414.58       |
| 2024-04-20 |      0.481 | $5,000.00      | $2,405.79       |
| 2024-04-14 |      0.438 | $4,000.00      | $1,753.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
