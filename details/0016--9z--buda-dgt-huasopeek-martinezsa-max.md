### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1449.6<br />
<br />
Final Rank Value (1449.6) = Starting Rank Value (1553.8) + Head To Head Adjustments (-104.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.274[<sup>2</sup>](#table1)
- LAN Wins: 0.710[<sup>2</sup>](#table1)

The average of these factors is 0.564<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1553.8
- 400 + ( ( 0.564 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1553.8


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
|           60 |      278 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      337 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |     1.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      963 | 2024-06-16 | fnatic            | W   | 0.876      | 0.548        | 0.371 (0.178)    | 0.708 (0.340)    | 1 (0.876) |    13.60 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |      974 | 2024-06-16 | KOI               | W   | 0.874      | -            | -                | -                | 1 (0.874) |     3.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |      995 | 2024-06-15 | paiN              | W   | 0.869      | 0.548        | 0.327 (0.156)    | 0.866 (0.413)    | 1 (0.869) |    10.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1014 | 2024-06-15 | BESTIA            | W   | 0.867      | 0.548        | 0.095 (0.045)    | 0.801 (0.381)    | 1 (0.867) |     2.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1033 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.862      | -            | -                | -                | -         |    -8.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1243 | 2024-06-08 | Imperial          | L   | 0.823      | -            | -                | -                | -         |   -19.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1300 | 2024-06-07 | Sharks            | W   | 0.816      | 0.450        | -                | 0.565 (0.207)    | 0 (0.000) |     2.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1358 | 2024-06-06 | MIBR              | W   | 0.809      | 0.450        | 0.209 (0.076)    | 0.659 (0.240)    | -         |    12.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1427 | 2024-06-05 | RED Canids        | L   | 0.803      | -            | -                | -                | -         |   -21.73 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1477 | 2024-06-04 | Fluxo             | W   | 0.796      | 0.450        | 0.124 (0.044)    | 0.723 (0.259)    | -         |     2.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1558 | 2024-06-01 | G2                | L   | 0.776      | -            | -                | -                | -         |    -1.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1648 | 2024-05-29 | Vitality          | W   | 0.755      | 0.624        | 0.649 (0.306)    | -                | 1 (0.755) |    21.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1688 | 2024-05-27 | Liquid            | W   | 0.743      | 0.624        | 0.384 (0.178)    | 0.460 (0.213)    | 1 (0.743) |    16.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1698 | 2024-05-27 | MOUZ              | W   | 0.742      | 0.624        | 1.000 (0.463)    | -                | 1 (0.742) |    21.78 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1793 | 2024-05-22 | Imperial          | L   | 0.710      | -            | -                | -                | -         |   -15.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1797 | 2024-05-22 | Imperial          | L   | 0.709      | -            | -                | -                | -         |   -16.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1876 | 2024-05-20 | W7M               | W   | 0.696      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1879 | 2024-05-20 | W7M               | W   | 0.696      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1880 | 2024-05-20 | BESTIA            | L   | 0.695      | -            | -                | -                | -         |   -20.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1883 | 2024-05-20 | BESTIA            | W   | 0.695      | 0.450        | -                | 0.801 (0.251)    | -         |     1.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1910 | 2024-05-19 | RED Canids        | L   | 0.688      | -            | -                | -                | -         |   -18.91 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1935 | 2024-05-18 | Fluxo             | W   | 0.682      | -            | -                | -                | -         |     2.26 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     2000 | 2024-05-16 | ODDIK             | W   | 0.669      | -            | -                | -                | -         |     0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2008 | 2024-05-16 | Imperial          | L   | 0.668      | -            | -                | -                | -         |   -15.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2045 | 2024-05-15 | RED Canids        | W   | 0.663      | 0.450        | -                | 0.743 (0.222)    | -         |     2.21 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2047 | 2024-05-15 | RED Canids        | L   | 0.663      | -            | -                | -                | -         |   -18.93 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2054 | 2024-05-15 | Sharks            | W   | 0.662      | -            | -                | -                | -         |     1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2106 | 2024-05-14 | Smoke             | W   | 0.656      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2110 | 2024-05-14 | Smoke             | W   | 0.656      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2120 | 2024-05-14 | Galorys           | W   | 0.655      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2139 | 2024-05-13 | Galorys           | W   | 0.650      | -            | -                | -                | -         |     0.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2158 | 2024-05-12 | inSanitY          | W   | 0.643      | -            | -                | -                | -         |     0.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2163 | 2024-05-12 | paiN              | L   | 0.642      | -            | -                | -                | -         |   -13.79 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2190 | 2024-05-11 | KRÜ               | W   | 0.635      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2217 | 2024-05-10 | inSanitY          | W   | 0.630      | -            | -                | -                | -         |     0.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2259 | 2024-05-08 | Sharks            | W   | 0.616      | -            | -                | -                | -         |     0.90 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2301 | 2024-05-06 | Vikings KR        | W   | 0.601      | -            | -                | -                | -         |     0.39 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2393 | 2024-05-01 | Case              | W   | 0.569      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2394 | 2024-05-01 | Case              | W   | 0.568      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2665 | 2024-04-19 | OG                | L   | 0.490      | -            | -                | -                | -         |   -14.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2715 | 2024-04-18 | Imperial          | L   | 0.483      | -            | -                | -                | -         |   -12.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2721 | 2024-04-18 | FURIA             | W   | 0.482      | 0.589        | 0.284 (0.081)    | -                | 1 (0.482) |    10.28 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3044 | 2024-04-08 | HEROIC            | L   | 0.413      | -            | -                | -                | -         |    -6.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3054 | 2024-04-07 | G2                | L   | 0.411      | -            | -                | -                | -         |    -1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4013 | 2024-02-23 | FURIA             | W   | 0.116      | -            | -                | -                | -         |     2.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4016 | 2024-02-23 | BESTIA            | W   | 0.115      | -            | -                | -                | -         |     0.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4027 | 2024-02-22 | FURIA             | L   | 0.110      | -            | -                | -                | -         |    -0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4033 | 2024-02-22 | BESTIA            | W   | 0.109      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4078 | 2024-02-20 | Solid             | W   | 0.096      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4081 | 2024-02-20 | Case              | W   | 0.096      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4085 | 2024-02-20 | Salao do Corte    | W   | 0.096      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4137 | 2024-02-18 | LA RUGONETA       | L   | 0.080      | -            | -                | -                | -         |    -2.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4179 | 2024-02-16 | Fluxo             | L   | 0.069      | -            | -                | -                | -         |    -2.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4204 | 2024-02-15 | Imperial          | L   | 0.063      | -            | -                | -                | -         |    -1.65 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4205 | 2024-02-15 | Case              | W   | 0.063      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4209 | 2024-02-15 | KRÜ               | W   | 0.062      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4234 | 2024-02-14 | 2GAME             | W   | 0.057      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4299 | 2024-02-12 | LA RUGONETA       | W   | 0.042      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($131,501.59)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.876 | $100,000.00    | $87,641.20      |
| 2024-06-09 |      0.829 | $7,500.00      | $6,216.84       |
| 2024-06-02 |      0.782 | $20,000.00     | $15,630.09      |
| 2024-05-19 |      0.688 | $4,000.00      | $2,752.69       |
| 2024-05-16 |      0.668 | $5,000.00      | $3,340.86       |
| 2024-05-12 |      0.642 | $15,000.00     | $9,630.90       |
| 2024-04-20 |      0.496 | $5,000.00      | $2,477.89       |
| 2024-04-14 |      0.453 | $4,000.00      | $1,811.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
