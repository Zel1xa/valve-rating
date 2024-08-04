### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [16](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1446.8<br />
<br />
Final Rank Value (1446.8) = Starting Rank Value (1552.6) + Head To Head Adjustments (-105.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.718[<sup>1</sup>](#table2)
- Bounty Collected: 0.552[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.711[<sup>2</sup>](#table1)

The average of these factors is 0.564<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1552.6
- 400 + ( ( 0.564 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1552.6


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
|           60 |      270 | 2024-07-27 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -28.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |      329 | 2024-07-25 | RUBY              | W   | 1.000      | 0.435        | 0.095 (0.041)    | 0.502 (0.218)    | 0 (0.000) |     1.27 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |      955 | 2024-06-16 | fnatic            | W   | 0.877      | 0.548        | 0.371 (0.178)    | 0.708 (0.341)    | 1 (0.877) |    13.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |      966 | 2024-06-16 | KOI               | W   | 0.875      | -            | -                | -                | 1 (0.875) |     3.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |      987 | 2024-06-15 | paiN              | W   | 0.870      | 0.548        | 0.327 (0.156)    | 0.866 (0.413)    | 1 (0.870) |    10.33 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |     1006 | 2024-06-15 | BESTIA            | W   | 0.868      | 0.548        | 0.095 (0.045)    | 0.801 (0.381)    | 1 (0.868) |     2.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1025 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.863      | -            | -                | -                | -         |    -8.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     1235 | 2024-06-08 | Imperial          | L   | 0.823      | -            | -                | -                | -         |   -18.99 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     1292 | 2024-06-07 | Sharks            | W   | 0.817      | 0.450        | -                | 0.565 (0.208)    | 0 (0.000) |     2.25 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     1350 | 2024-06-06 | MIBR              | W   | 0.810      | 0.450        | 0.209 (0.076)    | 0.659 (0.240)    | -         |    12.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     1419 | 2024-06-05 | RED Canids        | L   | 0.803      | -            | -                | -                | -         |   -21.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     1469 | 2024-06-04 | Fluxo             | W   | 0.797      | 0.450        | 0.124 (0.045)    | 0.723 (0.259)    | -         |     2.48 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1550 | 2024-06-01 | G2                | L   | 0.776      | -            | -                | -                | -         |    -1.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1640 | 2024-05-29 | Vitality          | W   | 0.756      | 0.624        | 0.649 (0.306)    | -                | 1 (0.756) |    21.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1680 | 2024-05-27 | Liquid            | W   | 0.744      | 0.624        | 0.315 (0.146)    | 0.460 (0.214)    | 1 (0.744) |    14.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1690 | 2024-05-27 | MOUZ              | W   | 0.743      | 0.624        | 1.000 (0.463)    | -                | 1 (0.743) |    21.79 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     1785 | 2024-05-22 | Imperial          | L   | 0.710      | -            | -                | -                | -         |   -15.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     1789 | 2024-05-22 | Imperial          | L   | 0.710      | -            | -                | -                | -         |   -16.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     1868 | 2024-05-20 | W7M               | W   | 0.697      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     1871 | 2024-05-20 | W7M               | W   | 0.697      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     1872 | 2024-05-20 | BESTIA            | L   | 0.696      | -            | -                | -                | -         |   -20.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     1875 | 2024-05-20 | BESTIA            | W   | 0.696      | 0.450        | -                | 0.801 (0.251)    | -         |     1.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     1902 | 2024-05-19 | RED Canids        | L   | 0.689      | -            | -                | -                | -         |   -18.91 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           37 |     1927 | 2024-05-18 | Fluxo             | W   | 0.682      | -            | -                | -                | -         |     2.28 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           36 |     1992 | 2024-05-16 | ODDIK             | W   | 0.670      | -            | -                | -                | -         |     0.97 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2000 | 2024-05-16 | Imperial          | L   | 0.669      | -            | -                | -                | -         |   -15.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2037 | 2024-05-15 | RED Canids        | W   | 0.664      | 0.450        | -                | 0.743 (0.222)    | -         |     2.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2039 | 2024-05-15 | RED Canids        | L   | 0.664      | -            | -                | -                | -         |   -18.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2046 | 2024-05-15 | Sharks            | W   | 0.663      | -            | -                | -                | -         |     1.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2098 | 2024-05-14 | Smoke             | W   | 0.657      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2102 | 2024-05-14 | Smoke             | W   | 0.657      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2112 | 2024-05-14 | Galorys           | W   | 0.656      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     2131 | 2024-05-13 | Galorys           | W   | 0.650      | -            | -                | -                | -         |     0.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     2150 | 2024-05-12 | inSanitY          | W   | 0.644      | -            | -                | -                | -         |     0.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     2155 | 2024-05-12 | paiN              | L   | 0.643      | -            | -                | -                | -         |   -13.77 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     2182 | 2024-05-11 | KRÜ               | W   | 0.636      | -            | -                | -                | -         |     0.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     2209 | 2024-05-10 | inSanitY          | W   | 0.631      | -            | -                | -                | -         |     0.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     2251 | 2024-05-08 | Sharks            | W   | 0.617      | -            | -                | -                | -         |     0.90 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     2293 | 2024-05-06 | Vikings KR        | W   | 0.602      | -            | -                | -                | -         |     0.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     2385 | 2024-05-01 | Case              | W   | 0.569      | -            | -                | -                | -         |     0.57 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     2386 | 2024-05-01 | Case              | W   | 0.569      | -            | -                | -                | -         |     0.58 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     2657 | 2024-04-19 | OG                | L   | 0.491      | -            | -                | -                | -         |   -14.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     2707 | 2024-04-18 | Imperial          | L   | 0.484      | -            | -                | -                | -         |   -12.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     2713 | 2024-04-18 | FURIA             | W   | 0.483      | 0.589        | 0.284 (0.081)    | -                | 1 (0.483) |    10.30 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3036 | 2024-04-08 | HEROIC            | L   | 0.413      | -            | -                | -                | -         |    -6.41 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3046 | 2024-04-07 | G2                | L   | 0.412      | -            | -                | -                | -         |    -1.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4005 | 2024-02-23 | FURIA             | W   | 0.117      | -            | -                | -                | -         |     2.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4008 | 2024-02-23 | BESTIA            | W   | 0.116      | -            | -                | -                | -         |     0.19 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4019 | 2024-02-22 | FURIA             | L   | 0.110      | -            | -                | -                | -         |    -0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4025 | 2024-02-22 | BESTIA            | W   | 0.109      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4070 | 2024-02-20 | Solid             | W   | 0.097      | -            | -                | -                | -         |     0.08 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4073 | 2024-02-20 | Case              | W   | 0.097      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4077 | 2024-02-20 | Salao do Corte    | W   | 0.096      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4129 | 2024-02-18 | LA RUGONETA       | L   | 0.081      | -            | -                | -                | -         |    -2.55 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4171 | 2024-02-16 | Fluxo             | L   | 0.069      | -            | -                | -                | -         |    -2.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4196 | 2024-02-15 | Imperial          | L   | 0.064      | -            | -                | -                | -         |    -1.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4197 | 2024-02-15 | Case              | W   | 0.063      | -            | -                | -                | -         |     0.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4201 | 2024-02-15 | KRÜ               | W   | 0.063      | -            | -                | -                | -         |     0.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4226 | 2024-02-14 | 2GAME             | W   | 0.057      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4291 | 2024-02-12 | LA RUGONETA       | W   | 0.043      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($131,616.76)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.877 | $100,000.00    | $87,712.96      |
| 2024-06-09 |      0.830 | $7,500.00      | $6,222.22       |
| 2024-06-02 |      0.782 | $20,000.00     | $15,644.44      |
| 2024-05-19 |      0.689 | $4,000.00      | $2,755.56       |
| 2024-05-16 |      0.669 | $5,000.00      | $3,344.44       |
| 2024-05-12 |      0.643 | $15,000.00     | $9,641.67       |
| 2024-04-20 |      0.496 | $5,000.00      | $2,481.48       |
| 2024-04-14 |      0.453 | $4,000.00      | $1,813.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
