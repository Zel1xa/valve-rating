### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1448.4<br />
<br />
Final Rank Value (1448.4) = Starting Rank Value (1551.2) + Head To Head Adjustments (-102.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.553[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.707[<sup>2</sup>](#table1)

The average of these factors is 0.561<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1551.2
- 400 + ( ( 0.561 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1551.2


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
|           60 |      327 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      386 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.492 (0.214)    | 0 (0.000) |     1.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1012 | 2024-06-16 | fnatic            | W   | 0.869      | 0.548        | 0.371 (0.176)    | 0.697 (0.332)    | 1 (0.869) |    13.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1023 | 2024-06-16 | KOI               | W   | 0.866      | -            | -                | -                | 1 (0.866) |     3.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |     1044 | 2024-06-15 | paiN              | W   | 0.861      | 0.548        | 0.325 (0.153)    | 0.856 (0.404)    | 1 (0.861) |    10.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1063 | 2024-06-15 | BESTIA            | W   | 0.859      | 0.548        | 0.096 (0.045)    | 0.792 (0.373)    | 1 (0.859) |     2.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1082 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.854      | -            | -                | -                | -         |    -7.89 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1292 | 2024-06-08 | Imperial          | L   | 0.815      | -            | -                | -                | -         |   -18.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1349 | 2024-06-07 | Sharks            | W   | 0.808      | 0.450        | -                | 0.558 (0.203)    | 0 (0.000) |     2.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1407 | 2024-06-06 | MIBR              | W   | 0.801      | 0.450        | 0.208 (0.075)    | 0.649 (0.234)    | -         |    11.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1476 | 2024-06-05 | RED Canids        | L   | 0.795      | -            | -                | -                | -         |   -21.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1526 | 2024-06-04 | Fluxo             | W   | 0.788      | 0.450        | 0.123 (0.044)    | 0.716 (0.254)    | -         |     2.41 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1607 | 2024-06-01 | G2                | L   | 0.768      | -            | -                | -                | -         |    -1.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1697 | 2024-05-29 | Vitality          | W   | 0.748      | 0.624        | 0.648 (0.302)    | -                | 1 (0.748) |    21.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1737 | 2024-05-27 | Liquid            | W   | 0.735      | 0.624        | 0.383 (0.176)    | 0.450 (0.207)    | 1 (0.735) |    16.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1747 | 2024-05-27 | MOUZ              | W   | 0.734      | 0.624        | 1.000 (0.458)    | -                | 1 (0.734) |    21.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1842 | 2024-05-22 | Imperial          | L   | 0.702      | -            | -                | -                | -         |   -15.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1846 | 2024-05-22 | Imperial          | L   | 0.701      | -            | -                | -                | -         |   -16.46 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1925 | 2024-05-20 | W7M               | W   | 0.688      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1928 | 2024-05-20 | W7M               | W   | 0.688      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1929 | 2024-05-20 | BESTIA            | L   | 0.688      | -            | -                | -                | -         |   -20.33 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1932 | 2024-05-20 | BESTIA            | W   | 0.687      | 0.450        | -                | 0.792 (0.245)    | -         |     1.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1959 | 2024-05-19 | RED Canids        | L   | 0.680      | -            | -                | -                | -         |   -18.71 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1984 | 2024-05-18 | Fluxo             | W   | 0.674      | -            | -                | -                | -         |     2.22 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2049 | 2024-05-16 | ODDIK             | W   | 0.661      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2057 | 2024-05-16 | Imperial          | L   | 0.660      | -            | -                | -                | -         |   -15.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2094 | 2024-05-15 | RED Canids        | W   | 0.655      | 0.450        | -                | 0.748 (0.221)    | -         |     2.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2096 | 2024-05-15 | RED Canids        | L   | 0.655      | -            | -                | -                | -         |   -18.71 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2103 | 2024-05-15 | Sharks            | W   | 0.654      | -            | -                | -                | -         |     1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2155 | 2024-05-14 | Smoke             | W   | 0.648      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2159 | 2024-05-14 | Smoke             | W   | 0.648      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2169 | 2024-05-14 | Galorys           | W   | 0.647      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2188 | 2024-05-13 | Galorys           | W   | 0.642      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2207 | 2024-05-12 | inSanitY          | W   | 0.635      | -            | -                | -                | -         |     0.75 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2212 | 2024-05-12 | paiN              | L   | 0.634      | -            | -                | -                | -         |   -13.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2239 | 2024-05-11 | KRÜ               | W   | 0.628      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2266 | 2024-05-10 | inSanitY          | W   | 0.622      | -            | -                | -                | -         |     0.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2308 | 2024-05-08 | Sharks            | W   | 0.608      | -            | -                | -                | -         |     0.89 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2350 | 2024-05-06 | Vikings KR        | W   | 0.593      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2442 | 2024-05-01 | Case              | W   | 0.561      | -            | -                | -                | -         |     0.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2443 | 2024-05-01 | Case              | W   | 0.561      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2714 | 2024-04-19 | OG                | L   | 0.482      | -            | -                | -                | -         |   -14.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2764 | 2024-04-18 | Imperial          | L   | 0.475      | -            | -                | -                | -         |   -12.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2770 | 2024-04-18 | FURIA             | W   | 0.474      | 0.589        | 0.284 (0.079)    | -                | 1 (0.474) |    10.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3093 | 2024-04-08 | HEROIC            | L   | 0.405      | -            | -                | -                | -         |    -6.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3103 | 2024-04-07 | G2                | L   | 0.403      | -            | -                | -                | -         |    -1.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4062 | 2024-02-23 | FURIA             | W   | 0.108      | -            | -                | -                | -         |     2.49 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4065 | 2024-02-23 | BESTIA            | W   | 0.107      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4076 | 2024-02-22 | FURIA             | L   | 0.102      | -            | -                | -                | -         |    -0.87 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4082 | 2024-02-22 | BESTIA            | W   | 0.101      | -            | -                | -                | -         |     0.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4127 | 2024-02-20 | Solid             | W   | 0.088      | -            | -                | -                | -         |     0.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4130 | 2024-02-20 | Case              | W   | 0.088      | -            | -                | -                | -         |     0.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4134 | 2024-02-20 | Salao do Corte    | W   | 0.088      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4186 | 2024-02-18 | LA RUGONETA       | L   | 0.072      | -            | -                | -                | -         |    -2.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4228 | 2024-02-16 | Fluxo             | L   | 0.061      | -            | -                | -                | -         |    -1.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4253 | 2024-02-15 | Imperial          | L   | 0.055      | -            | -                | -                | -         |    -1.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4254 | 2024-02-15 | Case              | W   | 0.055      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4258 | 2024-02-15 | KRÜ               | W   | 0.054      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4283 | 2024-02-14 | 2GAME             | W   | 0.049      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4348 | 2024-02-12 | LA RUGONETA       | W   | 0.034      | -            | -                | -                | -         |     0.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($130,234.68)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.869 | $100,000.00    | $86,851.85      |
| 2024-06-09 |      0.821 | $7,500.00      | $6,157.64       |
| 2024-06-02 |      0.774 | $20,000.00     | $15,472.22      |
| 2024-05-19 |      0.680 | $4,000.00      | $2,721.11       |
| 2024-05-16 |      0.660 | $5,000.00      | $3,301.39       |
| 2024-05-12 |      0.634 | $15,000.00     | $9,512.50       |
| 2024-04-20 |      0.488 | $5,000.00      | $2,438.43       |
| 2024-04-14 |      0.445 | $4,000.00      | $1,779.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
