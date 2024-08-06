### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1447.1<br />
<br />
Final Rank Value (1447.1) = Starting Rank Value (1549.2) + Head To Head Adjustments (-102.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.717[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.705[<sup>2</sup>](#table1)

The average of these factors is 0.559<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1549.2
- 400 + ( ( 0.559 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1549.2


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
|           60 |      338 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      397 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.480 (0.208)    | 0 (0.000) |     1.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1023 | 2024-06-16 | fnatic            | W   | 0.864      | 0.548        | 0.371 (0.175)    | 0.680 (0.322)    | 1 (0.864) |    13.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1034 | 2024-06-16 | KOI               | W   | 0.861      | -            | -                | -                | 1 (0.861) |     3.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1055 | 2024-06-15 | paiN              | W   | 0.856      | 0.548        | 0.324 (0.152)    | 0.838 (0.393)    | 1 (0.856) |     9.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1074 | 2024-06-15 | BESTIA            | W   | 0.854      | 0.548        | 0.096 (0.045)    | 0.775 (0.363)    | 1 (0.854) |     2.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1093 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.849      | -            | -                | -                | -         |    -7.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1303 | 2024-06-08 | Imperial          | L   | 0.810      | -            | -                | -                | -         |   -18.88 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1360 | 2024-06-07 | Sharks            | W   | 0.803      | 0.450        | -                | 0.546 (0.197)    | 0 (0.000) |     2.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1418 | 2024-06-06 | MIBR              | W   | 0.796      | 0.450        | 0.208 (0.074)    | 0.633 (0.227)    | -         |    11.84 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1487 | 2024-06-05 | RED Canids        | L   | 0.790      | -            | -                | -                | -         |   -21.43 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1537 | 2024-06-04 | Fluxo             | W   | 0.783      | 0.450        | 0.123 (0.043)    | 0.701 (0.247)    | -         |     2.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1618 | 2024-06-01 | G2                | L   | 0.763      | -            | -                | -                | -         |    -1.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1708 | 2024-05-29 | Vitality          | W   | 0.743      | 0.624        | 0.647 (0.300)    | -                | 1 (0.743) |    21.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1748 | 2024-05-27 | Liquid            | W   | 0.730      | 0.624        | 0.383 (0.175)    | 0.438 (0.200)    | 1 (0.730) |    16.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1758 | 2024-05-27 | MOUZ              | W   | 0.729      | 0.624        | 1.000 (0.455)    | -                | 1 (0.729) |    21.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1853 | 2024-05-22 | Imperial          | L   | 0.697      | -            | -                | -                | -         |   -15.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1857 | 2024-05-22 | Imperial          | L   | 0.696      | -            | -                | -                | -         |   -16.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1936 | 2024-05-20 | W7M               | W   | 0.683      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1939 | 2024-05-20 | W7M               | W   | 0.683      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1940 | 2024-05-20 | BESTIA            | L   | 0.683      | -            | -                | -                | -         |   -20.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1943 | 2024-05-20 | BESTIA            | W   | 0.682      | 0.450        | -                | 0.775 (0.238)    | -         |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1970 | 2024-05-19 | RED Canids        | L   | 0.675      | -            | -                | -                | -         |   -18.59 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1995 | 2024-05-18 | Fluxo             | W   | 0.669      | -            | -                | -                | -         |     2.19 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2060 | 2024-05-16 | ODDIK             | W   | 0.656      | -            | -                | -                | -         |     0.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2068 | 2024-05-16 | Imperial          | L   | 0.655      | -            | -                | -                | -         |   -15.78 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2105 | 2024-05-15 | RED Canids        | W   | 0.650      | 0.450        | -                | 0.732 (0.214)    | -         |     2.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2107 | 2024-05-15 | RED Canids        | L   | 0.650      | -            | -                | -                | -         |   -18.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2114 | 2024-05-15 | Sharks            | W   | 0.649      | -            | -                | -                | -         |     1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2166 | 2024-05-14 | Smoke             | W   | 0.643      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2170 | 2024-05-14 | Smoke             | W   | 0.643      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2180 | 2024-05-14 | Galorys           | W   | 0.642      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2199 | 2024-05-13 | Galorys           | W   | 0.637      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2218 | 2024-05-12 | inSanitY          | W   | 0.630      | -            | -                | -                | -         |     0.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2223 | 2024-05-12 | paiN              | L   | 0.629      | -            | -                | -                | -         |   -13.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2250 | 2024-05-11 | KRÜ               | W   | 0.623      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2277 | 2024-05-10 | inSanitY          | W   | 0.617      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2319 | 2024-05-08 | Sharks            | W   | 0.603      | -            | -                | -                | -         |     0.88 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2361 | 2024-05-06 | Vikings KR        | W   | 0.588      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2453 | 2024-05-01 | Case              | W   | 0.556      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2454 | 2024-05-01 | Case              | W   | 0.556      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2725 | 2024-04-19 | OG                | L   | 0.477      | -            | -                | -                | -         |   -14.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2775 | 2024-04-18 | Imperial          | L   | 0.470      | -            | -                | -                | -         |   -12.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2781 | 2024-04-18 | FURIA             | W   | 0.469      | 0.589        | 0.284 (0.078)    | -                | 1 (0.469) |    10.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3104 | 2024-04-08 | HEROIC            | L   | 0.400      | -            | -                | -                | -         |    -6.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3114 | 2024-04-07 | G2                | L   | 0.398      | -            | -                | -                | -         |    -0.98 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4073 | 2024-02-23 | FURIA             | W   | 0.103      | -            | -                | -                | -         |     2.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4076 | 2024-02-23 | BESTIA            | W   | 0.102      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4087 | 2024-02-22 | FURIA             | L   | 0.097      | -            | -                | -                | -         |    -0.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4093 | 2024-02-22 | BESTIA            | W   | 0.096      | -            | -                | -                | -         |     0.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4138 | 2024-02-20 | Solid             | W   | 0.083      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4141 | 2024-02-20 | Case              | W   | 0.083      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4145 | 2024-02-20 | Salao do Corte    | W   | 0.083      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4197 | 2024-02-18 | LA RUGONETA       | L   | 0.068      | -            | -                | -                | -         |    -2.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4239 | 2024-02-16 | Fluxo             | L   | 0.056      | -            | -                | -                | -         |    -1.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4264 | 2024-02-15 | Imperial          | L   | 0.050      | -            | -                | -                | -         |    -1.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4265 | 2024-02-15 | Case              | W   | 0.050      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4269 | 2024-02-15 | KRÜ               | W   | 0.049      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4294 | 2024-02-14 | 2GAME             | W   | 0.044      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4359 | 2024-02-12 | LA RUGONETA       | W   | 0.029      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129,432.18)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.864 | $100,000.00    | $86,351.85      |
| 2024-06-09 |      0.816 | $7,500.00      | $6,120.14       |
| 2024-06-02 |      0.769 | $20,000.00     | $15,372.22      |
| 2024-05-19 |      0.675 | $4,000.00      | $2,701.11       |
| 2024-05-16 |      0.655 | $5,000.00      | $3,276.39       |
| 2024-05-12 |      0.629 | $15,000.00     | $9,437.50       |
| 2024-04-20 |      0.483 | $5,000.00      | $2,413.43       |
| 2024-04-14 |      0.440 | $4,000.00      | $1,759.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
