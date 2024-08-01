### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [28](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1219.3<br />
<br />
Final Rank Value (1219.3) = Starting Rank Value (1227.9) + Head To Head Adjustments (-8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.525[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.323[<sup>2</sup>](#table1)

The average of these factors is 0.402<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1227.9
- 400 + ( ( 0.402 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1227.9


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
|           76 |      186 | 2024-07-27 | Monte          | L   | 1.000      | -            | -                | -                | -         |   -22.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           75 |      245 | 2024-07-25 | RUBY           | W   | 1.000      | 0.435        | 0.097 (0.042)    | 0.544 (0.236)    | 0 (0.000) |     4.61 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           74 |     1161 | 2024-06-08 | Imperial       | L   | 0.841      | -            | -                | -                | -         |   -12.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           73 |     1222 | 2024-06-07 | Sharks         | W   | 0.835      | 0.450        | -                | 0.572 (0.215)    | 0 (0.000) |     6.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           72 |     1284 | 2024-06-06 | MIBR           | W   | 0.828      | 0.450        | 0.201 (0.075)    | 0.637 (0.237)    | 0 (0.000) |    18.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           71 |     1356 | 2024-06-05 | RED Canids     | L   | 0.821      | -            | -                | -                | -         |   -16.95 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           70 |     1407 | 2024-06-04 | Fluxo          | W   | 0.815      | 0.450        | 0.122 (0.045)    | 0.702 (0.257)    | 0 (0.000) |     7.49 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           69 |     1489 | 2024-06-01 | G2             | L   | 0.795      | -            | -                | -                | -         |    -0.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           68 |     1579 | 2024-05-29 | Vitality       | W   | 0.774      | 0.624        | 0.590 (0.285)    | -                | 1 (0.774) |    23.73 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           67 |     1619 | 2024-05-27 | Liquid         | W   | 0.762      | 0.624        | 0.321 (0.153)    | 0.467 (0.222)    | 1 (0.762) |    21.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           66 |     1629 | 2024-05-27 | MOUZ           | W   | 0.761      | 0.624        | 1.000 (0.475)    | -                | 1 (0.761) |    23.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           65 |     1726 | 2024-05-22 | Imperial       | L   | 0.728      | -            | -                | -                | -         |    -8.14 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           64 |     1730 | 2024-05-22 | Imperial       | L   | 0.728      | -            | -                | -                | -         |    -8.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           63 |     1756 | 2024-05-22 | Corinthians    | W   | 0.725      | -            | -                | -                | 0 (0.000) |     0.51 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           62 |     1757 | 2024-05-22 | Corinthians    | W   | 0.725      | -            | -                | -                | 0 (0.000) |     0.51 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           61 |     1826 | 2024-05-20 | W7M            | W   | 0.715      | 0.450        | -                | 0.626 (0.201)    | -         |     2.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           60 |     1829 | 2024-05-20 | W7M            | W   | 0.715      | 0.450        | -                | 0.626 (0.201)    | -         |     2.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           59 |     1830 | 2024-05-20 | BESTIA         | L   | 0.714      | -            | -                | -                | -         |   -17.31 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           58 |     1833 | 2024-05-20 | BESTIA         | W   | 0.714      | 0.450        | 0.089 (0.029)    | 0.738 (0.237)    | -         |     5.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           57 |     1868 | 2024-05-19 | RED Canids     | L   | 0.707      | -            | -                | -                | -         |   -14.07 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           56 |     1893 | 2024-05-18 | Fluxo          | W   | 0.700      | 0.371        | 0.122 (0.032)    | -                | -         |     8.45 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           55 |     1959 | 2024-05-16 | ODDIK          | W   | 0.688      | 0.371        | 0.096 (0.024)    | 0.822 (0.210)    | -         |     4.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |     1967 | 2024-05-16 | Imperial       | L   | 0.687      | -            | -                | -                | -         |    -7.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |     2004 | 2024-05-15 | RED Canids     | W   | 0.682      | 0.450        | -                | 0.754 (0.231)    | -         |     7.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |     2006 | 2024-05-15 | RED Canids     | L   | 0.682      | -            | -                | -                | -         |   -14.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |     2013 | 2024-05-15 | Sharks         | W   | 0.681      | -            | -                | -                | -         |     5.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |     2071 | 2024-05-14 | Smoke          | W   | 0.675      | -            | -                | -                | -         |     2.05 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |     2075 | 2024-05-14 | Smoke          | W   | 0.675      | -            | -                | -                | -         |     2.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     2085 | 2024-05-14 | Galorys        | W   | 0.674      | -            | -                | -                | -         |     3.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     2105 | 2024-05-13 | Galorys        | W   | 0.668      | -            | -                | -                | -         |     3.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     2112 | 2024-05-13 | inSanitY       | W   | 0.667      | -            | -                | -                | -         |     4.09 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     2126 | 2024-05-12 | inSanitY       | W   | 0.662      | -            | -                | -                | -         |     4.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     2131 | 2024-05-12 | paiN           | L   | 0.661      | -            | -                | -                | -         |    -5.69 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     2158 | 2024-05-11 | KRÜ            | W   | 0.654      | -            | -                | -                | -         |     4.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     2185 | 2024-05-10 | inSanitY       | W   | 0.649      | -            | -                | -                | -         |     4.26 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     2229 | 2024-05-08 | Sharks         | W   | 0.635      | -            | -                | -                | -         |     5.38 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     2271 | 2024-05-06 | Vikings KR     | W   | 0.620      | -            | -                | -                | -         |     2.66 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     2365 | 2024-05-01 | Case           | W   | 0.588      | -            | -                | -                | -         |     3.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     2366 | 2024-05-01 | Case           | W   | 0.587      | -            | -                | -                | -         |     3.82 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           37 |     2644 | 2024-04-19 | OG             | L   | 0.509      | -            | -                | -                | -         |   -10.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           36 |     2695 | 2024-04-18 | Imperial       | L   | 0.502      | -            | -                | -                | -         |    -5.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2702 | 2024-04-18 | FURIA          | W   | 0.501      | 0.589        | 0.286 (0.084)    | -                | 1 (0.501) |    14.98 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     3028 | 2024-04-08 | HEROIC         | L   | 0.431      | -            | -                | -                | -         |    -1.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     3038 | 2024-04-07 | G2             | L   | 0.430      | -            | -                | -                | -         |    -0.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     3164 | 2024-04-03 | Galorys        | L   | 0.399      | -            | -                | -                | -         |   -10.12 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     3165 | 2024-04-03 | Galorys        | L   | 0.399      | -            | -                | -                | -         |   -10.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     3166 | 2024-04-03 | adalYamigos    | L   | 0.399      | -            | -                | -                | -         |   -12.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     3167 | 2024-04-03 | adalYamigos    | L   | 0.399      | -            | -                | -                | -         |   -12.07 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     3336 | 2024-03-26 | Solid          | W   | 0.347      | -            | -                | -                | -         |     1.67 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     3337 | 2024-03-26 | Solid          | W   | 0.347      | -            | -                | -                | -         |     1.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     3546 | 2024-03-14 | ODDIK          | L   | 0.266      | -            | -                | -                | -         |    -6.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     3547 | 2024-03-14 | ODDIK          | L   | 0.266      | -            | -                | -                | -         |    -6.40 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     3791 | 2024-03-05 | Sharks         | L   | 0.207      | -            | -                | -                | -         |    -5.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           23 |     3792 | 2024-03-05 | Sharks         | L   | 0.207      | -            | -                | -                | -         |    -5.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           22 |     3793 | 2024-03-05 | Fluxo          | L   | 0.207      | -            | -                | -                | -         |    -4.74 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     3794 | 2024-03-05 | Fluxo          | L   | 0.207      | -            | -                | -                | -         |    -4.81 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     4027 | 2024-02-23 | FURIA          | W   | 0.135      | -            | -                | -                | -         |     4.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     4030 | 2024-02-23 | BESTIA         | W   | 0.134      | -            | -                | -                | -         |     1.02 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     4043 | 2024-02-22 | FURIA          | L   | 0.128      | -            | -                | -                | -         |    -0.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     4050 | 2024-02-22 | BESTIA         | W   | 0.127      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     4096 | 2024-02-20 | Solid          | W   | 0.115      | -            | -                | -                | -         |     0.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     4099 | 2024-02-20 | Case           | W   | 0.115      | -            | -                | -                | -         |     0.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     4103 | 2024-02-20 | Salao do Corte | W   | 0.114      | -            | -                | -                | -         |     0.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     4155 | 2024-02-18 | LA RUGONETA    | L   | 0.099      | -            | -                | -                | -         |    -3.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     4197 | 2024-02-16 | Fluxo          | L   | 0.087      | -            | -                | -                | -         |    -2.06 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     4222 | 2024-02-15 | Imperial       | L   | 0.082      | -            | -                | -                | -         |    -1.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     4223 | 2024-02-15 | Case           | W   | 0.081      | -            | -                | -                | -         |     0.44 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     4227 | 2024-02-15 | KRÜ            | W   | 0.081      | -            | -                | -                | -         |     0.37 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     4252 | 2024-02-14 | 2GAME          | W   | 0.075      | -            | -                | -                | -         |     0.10 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     4304 | 2024-02-13 | paiN           | W   | 0.068      | -            | -                | -                | -         |     1.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     4305 | 2024-02-13 | paiN           | W   | 0.068      | -            | -                | -                | -         |     1.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     4306 | 2024-02-13 | MIBR           | W   | 0.068      | -            | -                | -                | -         |     1.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     4307 | 2024-02-13 | MIBR           | W   | 0.068      | -            | -                | -                | -         |     1.63 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     4325 | 2024-02-12 | LA RUGONETA    | W   | 0.061      | -            | -                | -                | -         |     0.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4409 | 2024-02-04 | Imperial       | L   | 0.008      | -            | -                | -                | -         |    -0.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4430 | 2024-02-03 | W7M            | W   | 0.002      | -            | -                | -                | -         |     0.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,996.16)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-09 |      0.848 | $7,500.00      | $6,357.64       |
| 2024-06-02 |      0.800 | $20,000.00     | $16,005.56      |
| 2024-05-19 |      0.707 | $4,000.00      | $2,827.78       |
| 2024-05-16 |      0.687 | $5,000.00      | $3,434.72       |
| 2024-05-12 |      0.661 | $15,000.00     | $9,912.50       |
| 2024-04-20 |      0.514 | $5,000.00      | $2,571.76       |
| 2024-04-14 |      0.472 | $4,000.00      | $1,886.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
