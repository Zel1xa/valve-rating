### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1449.3<br />
<br />
Final Rank Value (1449.3) = Starting Rank Value (1553.0) + Head To Head Adjustments (-103.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.709[<sup>2</sup>](#table1)

The average of these factors is 0.564<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1553.0
- 400 + ( ( 0.564 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1553.0


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
|           60 |      306 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      365 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.501 (0.218)    | 0 (0.000) |     1.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      991 | 2024-06-16 | fnatic            | W   | 0.873      | 0.548        | 0.371 (0.177)    | 0.708 (0.339)    | 1 (0.873) |    13.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1002 | 2024-06-16 | KOI               | W   | 0.871      | -            | -                | -                | 1 (0.871) |     3.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1023 | 2024-06-15 | paiN              | W   | 0.865      | 0.548        | 0.326 (0.155)    | 0.868 (0.412)    | 1 (0.865) |    10.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1042 | 2024-06-15 | BESTIA            | W   | 0.863      | 0.548        | 0.095 (0.045)    | 0.802 (0.380)    | 1 (0.863) |     2.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1061 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.858      | -            | -                | -                | -         |    -7.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1271 | 2024-06-08 | Imperial          | L   | 0.819      | -            | -                | -                | -         |   -19.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1328 | 2024-06-07 | Sharks            | W   | 0.813      | 0.450        | -                | 0.566 (0.207)    | 0 (0.000) |     2.20 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1386 | 2024-06-06 | MIBR              | W   | 0.806      | 0.450        | 0.209 (0.076)    | 0.659 (0.239)    | -         |    12.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1455 | 2024-06-05 | RED Canids        | L   | 0.799      | -            | -                | -                | -         |   -21.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1505 | 2024-06-04 | Fluxo             | W   | 0.793      | 0.450        | 0.124 (0.044)    | 0.725 (0.259)    | -         |     2.43 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1586 | 2024-06-01 | G2                | L   | 0.772      | -            | -                | -                | -         |    -1.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1676 | 2024-05-29 | Vitality          | W   | 0.752      | 0.624        | 0.648 (0.304)    | -                | 1 (0.752) |    21.41 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1716 | 2024-05-27 | Liquid            | W   | 0.740      | 0.624        | 0.384 (0.177)    | 0.459 (0.212)    | 1 (0.740) |    16.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1726 | 2024-05-27 | MOUZ              | W   | 0.738      | 0.624        | 1.000 (0.461)    | -                | 1 (0.738) |    21.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1821 | 2024-05-22 | Imperial          | L   | 0.706      | -            | -                | -                | -         |   -15.72 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1825 | 2024-05-22 | Imperial          | L   | 0.706      | -            | -                | -                | -         |   -16.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1904 | 2024-05-20 | W7M               | W   | 0.693      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1907 | 2024-05-20 | W7M               | W   | 0.693      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1908 | 2024-05-20 | BESTIA            | L   | 0.692      | -            | -                | -                | -         |   -20.46 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1911 | 2024-05-20 | BESTIA            | W   | 0.692      | 0.450        | -                | 0.802 (0.250)    | -         |     1.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1938 | 2024-05-19 | RED Canids        | L   | 0.685      | -            | -                | -                | -         |   -18.82 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1963 | 2024-05-18 | Fluxo             | W   | 0.678      | -            | -                | -                | -         |     2.25 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2028 | 2024-05-16 | ODDIK             | W   | 0.666      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2036 | 2024-05-16 | Imperial          | L   | 0.665      | -            | -                | -                | -         |   -15.93 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2073 | 2024-05-15 | RED Canids        | W   | 0.660      | 0.450        | -                | 0.758 (0.225)    | -         |     2.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2075 | 2024-05-15 | RED Canids        | L   | 0.659      | -            | -                | -                | -         |   -18.84 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2082 | 2024-05-15 | Sharks            | W   | 0.659      | -            | -                | -                | -         |     1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2134 | 2024-05-14 | Smoke             | W   | 0.653      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2138 | 2024-05-14 | Smoke             | W   | 0.652      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2148 | 2024-05-14 | Galorys           | W   | 0.651      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2167 | 2024-05-13 | Galorys           | W   | 0.646      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2186 | 2024-05-12 | inSanitY          | W   | 0.640      | -            | -                | -                | -         |     0.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2191 | 2024-05-12 | paiN              | L   | 0.639      | -            | -                | -                | -         |   -13.73 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2218 | 2024-05-11 | KRÜ               | W   | 0.632      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2245 | 2024-05-10 | inSanitY          | W   | 0.626      | -            | -                | -                | -         |     0.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2287 | 2024-05-08 | Sharks            | W   | 0.613      | -            | -                | -                | -         |     0.89 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2329 | 2024-05-06 | Vikings KR        | W   | 0.598      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2421 | 2024-05-01 | Case              | W   | 0.565      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2422 | 2024-05-01 | Case              | W   | 0.565      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2693 | 2024-04-19 | OG                | L   | 0.487      | -            | -                | -                | -         |   -14.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2743 | 2024-04-18 | Imperial          | L   | 0.480      | -            | -                | -                | -         |   -12.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2749 | 2024-04-18 | FURIA             | W   | 0.478      | 0.589        | 0.284 (0.080)    | -                | 1 (0.478) |    10.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3072 | 2024-04-08 | HEROIC            | L   | 0.409      | -            | -                | -                | -         |    -6.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3082 | 2024-04-07 | G2                | L   | 0.408      | -            | -                | -                | -         |    -1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4041 | 2024-02-23 | FURIA             | W   | 0.113      | -            | -                | -                | -         |     2.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4044 | 2024-02-23 | BESTIA            | W   | 0.112      | -            | -                | -                | -         |     0.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4055 | 2024-02-22 | FURIA             | L   | 0.106      | -            | -                | -                | -         |    -0.92 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4061 | 2024-02-22 | BESTIA            | W   | 0.105      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4106 | 2024-02-20 | Solid             | W   | 0.093      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4109 | 2024-02-20 | Case              | W   | 0.092      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4113 | 2024-02-20 | Salao do Corte    | W   | 0.092      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4165 | 2024-02-18 | LA RUGONETA       | L   | 0.077      | -            | -                | -                | -         |    -2.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4207 | 2024-02-16 | Fluxo             | L   | 0.065      | -            | -                | -                | -         |    -1.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4232 | 2024-02-15 | Imperial          | L   | 0.060      | -            | -                | -                | -         |    -1.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4233 | 2024-02-15 | Case              | W   | 0.059      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4237 | 2024-02-15 | KRÜ               | W   | 0.059      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4262 | 2024-02-14 | 2GAME             | W   | 0.053      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4327 | 2024-02-12 | LA RUGONETA       | W   | 0.039      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($130,948.01)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.873 | $100,000.00    | $87,296.30      |
| 2024-06-09 |      0.825 | $7,500.00      | $6,190.97       |
| 2024-06-02 |      0.778 | $20,000.00     | $15,561.11      |
| 2024-05-19 |      0.685 | $4,000.00      | $2,738.89       |
| 2024-05-16 |      0.665 | $5,000.00      | $3,323.61       |
| 2024-05-12 |      0.639 | $15,000.00     | $9,579.17       |
| 2024-04-20 |      0.492 | $5,000.00      | $2,460.65       |
| 2024-04-14 |      0.449 | $4,000.00      | $1,797.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
