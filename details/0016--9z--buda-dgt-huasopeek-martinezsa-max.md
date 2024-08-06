### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1448.1<br />
<br />
Final Rank Value (1448.1) = Starting Rank Value (1550.5) + Head To Head Adjustments (-102.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.268[<sup>2</sup>](#table1)
- LAN Wins: 0.706[<sup>2</sup>](#table1)

The average of these factors is 0.561<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1550.5
- 400 + ( ( 0.561 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1550.5


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
|           60 |      330 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      389 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.491 (0.214)    | 0 (0.000) |     1.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1015 | 2024-06-16 | fnatic            | W   | 0.866      | 0.548        | 0.371 (0.176)    | 0.696 (0.331)    | 1 (0.866) |    13.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1026 | 2024-06-16 | KOI               | W   | 0.864      | -            | -                | -                | 1 (0.864) |     3.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1047 | 2024-06-15 | paiN              | W   | 0.859      | 0.548        | 0.325 (0.153)    | 0.857 (0.403)    | 1 (0.859) |    10.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1066 | 2024-06-15 | BESTIA            | W   | 0.857      | 0.548        | 0.096 (0.045)    | 0.792 (0.372)    | 1 (0.857) |     2.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1085 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.852      | -            | -                | -                | -         |    -7.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1295 | 2024-06-08 | Imperial          | L   | 0.813      | -            | -                | -                | -         |   -18.92 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1352 | 2024-06-07 | Sharks            | W   | 0.806      | 0.450        | -                | 0.558 (0.202)    | 0 (0.000) |     2.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1410 | 2024-06-06 | MIBR              | W   | 0.799      | 0.450        | 0.208 (0.075)    | 0.648 (0.233)    | -         |    11.91 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1479 | 2024-06-05 | RED Canids        | L   | 0.792      | -            | -                | -                | -         |   -21.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1529 | 2024-06-04 | Fluxo             | W   | 0.786      | 0.450        | 0.123 (0.044)    | 0.716 (0.253)    | -         |     2.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1610 | 2024-06-01 | G2                | L   | 0.766      | -            | -                | -                | -         |    -1.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1700 | 2024-05-29 | Vitality          | W   | 0.745      | 0.624        | 0.647 (0.301)    | -                | 1 (0.745) |    21.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1740 | 2024-05-27 | Liquid            | W   | 0.733      | 0.624        | 0.383 (0.175)    | 0.449 (0.205)    | 1 (0.733) |    16.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1750 | 2024-05-27 | MOUZ              | W   | 0.732      | 0.624        | 1.000 (0.457)    | -                | 1 (0.732) |    21.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1845 | 2024-05-22 | Imperial          | L   | 0.699      | -            | -                | -                | -         |   -15.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1849 | 2024-05-22 | Imperial          | L   | 0.699      | -            | -                | -                | -         |   -16.43 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1928 | 2024-05-20 | W7M               | W   | 0.686      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1931 | 2024-05-20 | W7M               | W   | 0.686      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1932 | 2024-05-20 | BESTIA            | L   | 0.685      | -            | -                | -                | -         |   -20.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1935 | 2024-05-20 | BESTIA            | W   | 0.685      | 0.450        | -                | 0.792 (0.244)    | -         |     1.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1962 | 2024-05-19 | RED Canids        | L   | 0.678      | -            | -                | -                | -         |   -18.65 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1987 | 2024-05-18 | Fluxo             | W   | 0.671      | -            | -                | -                | -         |     2.21 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2052 | 2024-05-16 | ODDIK             | W   | 0.659      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2060 | 2024-05-16 | Imperial          | L   | 0.658      | -            | -                | -                | -         |   -15.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2097 | 2024-05-15 | RED Canids        | W   | 0.653      | 0.450        | -                | 0.748 (0.220)    | -         |     2.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2099 | 2024-05-15 | RED Canids        | L   | 0.653      | -            | -                | -                | -         |   -18.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2106 | 2024-05-15 | Sharks            | W   | 0.652      | -            | -                | -                | -         |     1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2158 | 2024-05-14 | Smoke             | W   | 0.646      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2162 | 2024-05-14 | Smoke             | W   | 0.646      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2172 | 2024-05-14 | Galorys           | W   | 0.645      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2191 | 2024-05-13 | Galorys           | W   | 0.639      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2210 | 2024-05-12 | inSanitY          | W   | 0.633      | -            | -                | -                | -         |     0.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2215 | 2024-05-12 | paiN              | L   | 0.632      | -            | -                | -                | -         |   -13.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2242 | 2024-05-11 | KRÜ               | W   | 0.625      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2269 | 2024-05-10 | inSanitY          | W   | 0.620      | -            | -                | -                | -         |     0.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2311 | 2024-05-08 | Sharks            | W   | 0.606      | -            | -                | -                | -         |     0.88 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2353 | 2024-05-06 | Vikings KR        | W   | 0.591      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2445 | 2024-05-01 | Case              | W   | 0.559      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2446 | 2024-05-01 | Case              | W   | 0.558      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2717 | 2024-04-19 | OG                | L   | 0.480      | -            | -                | -                | -         |   -14.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2767 | 2024-04-18 | Imperial          | L   | 0.473      | -            | -                | -                | -         |   -12.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2773 | 2024-04-18 | FURIA             | W   | 0.472      | 0.589        | 0.284 (0.079)    | -                | 1 (0.472) |    10.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3096 | 2024-04-08 | HEROIC            | L   | 0.402      | -            | -                | -                | -         |    -6.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3106 | 2024-04-07 | G2                | L   | 0.401      | -            | -                | -                | -         |    -0.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4065 | 2024-02-23 | FURIA             | W   | 0.106      | -            | -                | -                | -         |     2.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4068 | 2024-02-23 | BESTIA            | W   | 0.105      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4079 | 2024-02-22 | FURIA             | L   | 0.100      | -            | -                | -                | -         |    -0.85 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4085 | 2024-02-22 | BESTIA            | W   | 0.098      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4130 | 2024-02-20 | Solid             | W   | 0.086      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4133 | 2024-02-20 | Case              | W   | 0.086      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4137 | 2024-02-20 | Salao do Corte    | W   | 0.086      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4189 | 2024-02-18 | LA RUGONETA       | L   | 0.070      | -            | -                | -                | -         |    -2.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4231 | 2024-02-16 | Fluxo             | L   | 0.059      | -            | -                | -                | -         |    -1.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4256 | 2024-02-15 | Imperial          | L   | 0.053      | -            | -                | -                | -         |    -1.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4257 | 2024-02-15 | Case              | W   | 0.053      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4261 | 2024-02-15 | KRÜ               | W   | 0.052      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4286 | 2024-02-14 | 2GAME             | W   | 0.047      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4351 | 2024-02-12 | LA RUGONETA       | W   | 0.032      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129,878.01)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.866 | $100,000.00    | $86,629.63      |
| 2024-06-09 |      0.819 | $7,500.00      | $6,140.97       |
| 2024-06-02 |      0.771 | $20,000.00     | $15,427.78      |
| 2024-05-19 |      0.678 | $4,000.00      | $2,712.22       |
| 2024-05-16 |      0.658 | $5,000.00      | $3,290.28       |
| 2024-05-12 |      0.632 | $15,000.00     | $9,479.17       |
| 2024-04-20 |      0.485 | $5,000.00      | $2,427.31       |
| 2024-04-14 |      0.443 | $4,000.00      | $1,770.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
