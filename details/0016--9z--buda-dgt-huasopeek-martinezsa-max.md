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
Final Rank Value (1446.9) = Starting Rank Value (1548.7) + Head To Head Adjustments (-101.8)<br />

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
|           60 |      351 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      410 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.479 (0.208)    | 0 (0.000) |     1.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1036 | 2024-06-16 | fnatic            | W   | 0.862      | 0.548        | 0.371 (0.175)    | 0.680 (0.321)    | 1 (0.862) |    13.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1047 | 2024-06-16 | KOI               | W   | 0.860      | -            | -                | -                | 1 (0.860) |     3.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1068 | 2024-06-15 | paiN              | W   | 0.855      | 0.548        | 0.324 (0.152)    | 0.839 (0.393)    | 1 (0.855) |     9.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1087 | 2024-06-15 | BESTIA            | W   | 0.853      | 0.548        | 0.096 (0.045)    | 0.776 (0.363)    | 1 (0.853) |     2.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1106 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.848      | -            | -                | -                | -         |    -7.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1316 | 2024-06-08 | Imperial          | L   | 0.808      | -            | -                | -                | -         |   -18.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1373 | 2024-06-07 | Sharks            | W   | 0.802      | 0.450        | -                | 0.546 (0.197)    | 0 (0.000) |     2.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1431 | 2024-06-06 | MIBR              | W   | 0.795      | 0.450        | 0.207 (0.074)    | 0.633 (0.226)    | -         |    11.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1500 | 2024-06-05 | RED Canids        | L   | 0.788      | -            | -                | -                | -         |   -21.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1550 | 2024-06-04 | Fluxo             | W   | 0.782      | 0.450        | 0.123 (0.043)    | 0.701 (0.247)    | -         |     2.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1631 | 2024-06-01 | G2                | L   | 0.761      | -            | -                | -                | -         |    -1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1721 | 2024-05-29 | Vitality          | W   | 0.741      | 0.624        | 0.647 (0.299)    | -                | 1 (0.741) |    21.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1761 | 2024-05-27 | Liquid            | W   | 0.729      | 0.624        | 0.383 (0.174)    | 0.437 (0.199)    | 1 (0.729) |    16.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1771 | 2024-05-27 | MOUZ              | W   | 0.728      | 0.624        | 1.000 (0.454)    | -                | 1 (0.728) |    21.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1866 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |   -15.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1870 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |   -16.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1949 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1952 | 2024-05-20 | W7M               | W   | 0.682      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1953 | 2024-05-20 | BESTIA            | L   | 0.681      | -            | -                | -                | -         |   -20.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1956 | 2024-05-20 | BESTIA            | W   | 0.681      | 0.450        | -                | 0.776 (0.238)    | -         |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1983 | 2024-05-19 | RED Canids        | L   | 0.674      | -            | -                | -                | -         |   -18.55 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     2008 | 2024-05-18 | Fluxo             | W   | 0.667      | -            | -                | -                | -         |     2.19 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2073 | 2024-05-16 | ODDIK             | W   | 0.655      | -            | -                | -                | -         |     0.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2081 | 2024-05-16 | Imperial          | L   | 0.654      | -            | -                | -                | -         |   -15.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2118 | 2024-05-15 | RED Canids        | W   | 0.649      | 0.450        | -                | 0.732 (0.214)    | -         |     2.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2120 | 2024-05-15 | RED Canids        | L   | 0.649      | -            | -                | -                | -         |   -18.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2127 | 2024-05-15 | Sharks            | W   | 0.648      | -            | -                | -                | -         |     1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2179 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2183 | 2024-05-14 | Smoke             | W   | 0.642      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2193 | 2024-05-14 | Galorys           | W   | 0.641      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2212 | 2024-05-13 | Galorys           | W   | 0.635      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2231 | 2024-05-12 | inSanitY          | W   | 0.629      | -            | -                | -                | -         |     0.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2236 | 2024-05-12 | paiN              | L   | 0.628      | -            | -                | -                | -         |   -13.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2263 | 2024-05-11 | KRÜ               | W   | 0.621      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2290 | 2024-05-10 | inSanitY          | W   | 0.616      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2332 | 2024-05-08 | Sharks            | W   | 0.602      | -            | -                | -                | -         |     0.87 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2374 | 2024-05-06 | Vikings KR        | W   | 0.587      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2466 | 2024-05-01 | Case              | W   | 0.554      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2467 | 2024-05-01 | Case              | W   | 0.554      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2738 | 2024-04-19 | OG                | L   | 0.476      | -            | -                | -                | -         |   -14.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2788 | 2024-04-18 | Imperial          | L   | 0.469      | -            | -                | -                | -         |   -11.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2794 | 2024-04-18 | FURIA             | W   | 0.468      | 0.589        | 0.284 (0.078)    | -                | 1 (0.468) |    10.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3117 | 2024-04-08 | HEROIC            | L   | 0.398      | -            | -                | -                | -         |    -6.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3127 | 2024-04-07 | G2                | L   | 0.397      | -            | -                | -                | -         |    -0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4086 | 2024-02-23 | FURIA             | W   | 0.102      | -            | -                | -                | -         |     2.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4089 | 2024-02-23 | BESTIA            | W   | 0.101      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4100 | 2024-02-22 | FURIA             | L   | 0.095      | -            | -                | -                | -         |    -0.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4106 | 2024-02-22 | BESTIA            | W   | 0.094      | -            | -                | -                | -         |     0.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4151 | 2024-02-20 | Solid             | W   | 0.082      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4154 | 2024-02-20 | Case              | W   | 0.082      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4158 | 2024-02-20 | Salao do Corte    | W   | 0.081      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4210 | 2024-02-18 | LA RUGONETA       | L   | 0.066      | -            | -                | -                | -         |    -2.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4252 | 2024-02-16 | Fluxo             | L   | 0.054      | -            | -                | -                | -         |    -1.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4277 | 2024-02-15 | Imperial          | L   | 0.049      | -            | -                | -                | -         |    -1.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4278 | 2024-02-15 | Case              | W   | 0.048      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4282 | 2024-02-15 | KRÜ               | W   | 0.048      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4307 | 2024-02-14 | 2GAME             | W   | 0.042      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4372 | 2024-02-12 | LA RUGONETA       | W   | 0.028      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129,209.26)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.862 | $100,000.00    | $86,212.96      |
| 2024-06-09 |      0.815 | $7,500.00      | $6,109.72       |
| 2024-06-02 |      0.767 | $20,000.00     | $15,344.44      |
| 2024-05-19 |      0.674 | $4,000.00      | $2,695.56       |
| 2024-05-16 |      0.654 | $5,000.00      | $3,269.44       |
| 2024-05-12 |      0.628 | $15,000.00     | $9,416.67       |
| 2024-04-20 |      0.481 | $5,000.00      | $2,406.48       |
| 2024-04-14 |      0.438 | $4,000.00      | $1,753.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
