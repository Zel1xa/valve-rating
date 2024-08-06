### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1446.9<br />
<br />
Final Rank Value (1446.9) = Starting Rank Value (1548.8) + Head To Head Adjustments (-101.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.717[<sup>1</sup>](#table2)
- Bounty Collected: 0.551[<sup>2</sup>](#table1)
- Opponent Network: 0.261[<sup>2</sup>](#table1)
- LAN Wins: 0.704[<sup>2</sup>](#table1)

The average of these factors is 0.558<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1548.8
- 400 + ( ( 0.558 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1548.8


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
|           60 |      347 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      406 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.479 (0.208)    | 0 (0.000) |     1.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1032 | 2024-06-16 | fnatic            | W   | 0.862      | 0.548        | 0.371 (0.175)    | 0.680 (0.322)    | 1 (0.862) |    13.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1043 | 2024-06-16 | KOI               | W   | 0.860      | -            | -                | -                | 1 (0.860) |     3.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1064 | 2024-06-15 | paiN              | W   | 0.855      | 0.548        | 0.324 (0.152)    | 0.839 (0.393)    | 1 (0.855) |     9.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1083 | 2024-06-15 | BESTIA            | W   | 0.853      | 0.548        | 0.096 (0.045)    | 0.776 (0.363)    | 1 (0.853) |     2.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1102 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.848      | -            | -                | -                | -         |    -7.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1312 | 2024-06-08 | Imperial          | L   | 0.809      | -            | -                | -                | -         |   -18.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1369 | 2024-06-07 | Sharks            | W   | 0.802      | 0.450        | -                | 0.546 (0.197)    | 0 (0.000) |     2.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1427 | 2024-06-06 | MIBR              | W   | 0.795      | 0.450        | 0.208 (0.074)    | 0.633 (0.227)    | -         |    11.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1496 | 2024-06-05 | RED Canids        | L   | 0.789      | -            | -                | -                | -         |   -21.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1546 | 2024-06-04 | Fluxo             | W   | 0.782      | 0.450        | 0.123 (0.043)    | 0.701 (0.247)    | -         |     2.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1627 | 2024-06-01 | G2                | L   | 0.762      | -            | -                | -                | -         |    -1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1717 | 2024-05-29 | Vitality          | W   | 0.741      | 0.624        | 0.647 (0.299)    | -                | 1 (0.741) |    21.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1757 | 2024-05-27 | Liquid            | W   | 0.729      | 0.624        | 0.383 (0.174)    | 0.437 (0.199)    | 1 (0.729) |    16.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1767 | 2024-05-27 | MOUZ              | W   | 0.728      | 0.624        | 1.000 (0.454)    | -                | 1 (0.728) |    21.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1862 | 2024-05-22 | Imperial          | L   | 0.696      | -            | -                | -                | -         |   -15.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1866 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |   -16.37 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1945 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1948 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1949 | 2024-05-20 | BESTIA            | L   | 0.681      | -            | -                | -                | -         |   -20.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1952 | 2024-05-20 | BESTIA            | W   | 0.681      | 0.450        | -                | 0.776 (0.238)    | -         |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1979 | 2024-05-19 | RED Canids        | L   | 0.674      | -            | -                | -                | -         |   -18.56 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     2004 | 2024-05-18 | Fluxo             | W   | 0.667      | -            | -                | -                | -         |     2.19 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2069 | 2024-05-16 | ODDIK             | W   | 0.655      | -            | -                | -                | -         |     0.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2077 | 2024-05-16 | Imperial          | L   | 0.654      | -            | -                | -                | -         |   -15.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2114 | 2024-05-15 | RED Canids        | W   | 0.649      | 0.450        | -                | 0.732 (0.214)    | -         |     2.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2116 | 2024-05-15 | RED Canids        | L   | 0.649      | -            | -                | -                | -         |   -18.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2123 | 2024-05-15 | Sharks            | W   | 0.648      | -            | -                | -                | -         |     1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2175 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2179 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2189 | 2024-05-14 | Galorys           | W   | 0.641      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2208 | 2024-05-13 | Galorys           | W   | 0.636      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2227 | 2024-05-12 | inSanitY          | W   | 0.629      | -            | -                | -                | -         |     0.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2232 | 2024-05-12 | paiN              | L   | 0.628      | -            | -                | -                | -         |   -13.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2259 | 2024-05-11 | KRÜ               | W   | 0.621      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2286 | 2024-05-10 | inSanitY          | W   | 0.616      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2328 | 2024-05-08 | Sharks            | W   | 0.602      | -            | -                | -                | -         |     0.87 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2370 | 2024-05-06 | Vikings KR        | W   | 0.587      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2462 | 2024-05-01 | Case              | W   | 0.555      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2463 | 2024-05-01 | Case              | W   | 0.554      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2734 | 2024-04-19 | OG                | L   | 0.476      | -            | -                | -                | -         |   -14.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2784 | 2024-04-18 | Imperial          | L   | 0.469      | -            | -                | -                | -         |   -11.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2790 | 2024-04-18 | FURIA             | W   | 0.468      | 0.589        | 0.284 (0.078)    | -                | 1 (0.468) |    10.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3113 | 2024-04-08 | HEROIC            | L   | 0.399      | -            | -                | -                | -         |    -6.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3123 | 2024-04-07 | G2                | L   | 0.397      | -            | -                | -                | -         |    -0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4082 | 2024-02-23 | FURIA             | W   | 0.102      | -            | -                | -                | -         |     2.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4085 | 2024-02-23 | BESTIA            | W   | 0.101      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4096 | 2024-02-22 | FURIA             | L   | 0.096      | -            | -                | -                | -         |    -0.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4102 | 2024-02-22 | BESTIA            | W   | 0.095      | -            | -                | -                | -         |     0.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4147 | 2024-02-20 | Solid             | W   | 0.082      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4150 | 2024-02-20 | Case              | W   | 0.082      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4154 | 2024-02-20 | Salao do Corte    | W   | 0.082      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4206 | 2024-02-18 | LA RUGONETA       | L   | 0.066      | -            | -                | -                | -         |    -2.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4248 | 2024-02-16 | Fluxo             | L   | 0.055      | -            | -                | -                | -         |    -1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4273 | 2024-02-15 | Imperial          | L   | 0.049      | -            | -                | -                | -         |    -1.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4274 | 2024-02-15 | Case              | W   | 0.049      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4278 | 2024-02-15 | KRÜ               | W   | 0.048      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4303 | 2024-02-14 | 2GAME             | W   | 0.043      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4368 | 2024-02-12 | LA RUGONETA       | W   | 0.028      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129,253.84)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.862 | $100,000.00    | $86,240.74      |
| 2024-06-09 |      0.815 | $7,500.00      | $6,111.81       |
| 2024-06-02 |      0.767 | $20,000.00     | $15,350.00      |
| 2024-05-19 |      0.674 | $4,000.00      | $2,696.67       |
| 2024-05-16 |      0.654 | $5,000.00      | $3,270.83       |
| 2024-05-12 |      0.628 | $15,000.00     | $9,420.83       |
| 2024-04-20 |      0.482 | $5,000.00      | $2,407.87       |
| 2024-04-14 |      0.439 | $4,000.00      | $1,755.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
