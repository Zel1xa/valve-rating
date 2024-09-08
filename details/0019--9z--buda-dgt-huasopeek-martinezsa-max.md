### Roster Details<br />
Team Name: 9z<br />
Roster: buda, dgt, HUASOPEEK, MartinezSa, max<br />
Global Rank: [19](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1380.4<br />
<br />
Final Rank Value (1380.4) = Starting Rank Value (1485.4) + Head To Head Adjustments (-105.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.694[<sup>1</sup>](#table2)
- Bounty Collected: 0.530[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.787[<sup>2</sup>](#table1)

The average of these factors is 0.561<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1485.4
- 400 + ( ( 0.561 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1485.4


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
|           57 |       25 | 2024-09-07 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -5.93 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           56 |       53 | 2024-09-06 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -14.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           55 |       84 | 2024-09-05 | Wildcard          | W   | 1.000      | 0.889        | 0.100 (0.089)    | 0.608 (0.540)    | 1 (1.000) |     6.32 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           54 |      143 | 2024-09-03 | MIBR              | L   | 1.000      | -            | -                | -                | -         |   -20.72 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           53 |      481 | 2024-08-26 | Falcons           | L   | 1.000      | -            | -                | -                | -         |   -11.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           52 |      508 | 2024-08-25 | paiN              | L   | 1.000      | -            | -                | -                | -         |   -10.11 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           51 |      535 | 2024-08-24 | Falcons           | W   | 1.000      | 0.143        | 0.297 (0.042)    | -                | 1 (1.000) |    17.98 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           50 |      949 | 2024-08-11 | paiN              | L   | 1.000      | -            | -                | -                | -         |   -10.86 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           49 |      974 | 2024-08-10 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -10.16 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           48 |     1008 | 2024-08-09 | MIBR              | W   | 1.000      | -            | -                | -                | 1 (1.000) |    10.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           47 |     1079 | 2024-08-07 | 3DMAX             | W   | 0.986      | 0.143        | 0.509 (0.072)    | -                | 1 (0.986) |    18.36 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           46 |     1466 | 2024-07-27 | Monte             | L   | 0.913      | -            | -                | -                | -         |   -26.79 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           45 |     1525 | 2024-07-25 | RUBY              | W   | 0.901      | 0.435        | -                | 0.390 (0.153)    | -         |     1.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           44 |     2154 | 2024-06-16 | fnatic            | W   | 0.643      | 0.548        | 0.294 (0.103)    | 0.679 (0.239)    | 1 (0.643) |     6.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           43 |     2165 | 2024-06-16 | KOI               | W   | 0.641      | -            | -                | -                | 1 (0.641) |     1.56 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           42 |     2186 | 2024-06-15 | paiN              | W   | 0.635      | 0.548        | 0.420 (0.146)    | 0.935 (0.326)    | 1 (0.635) |    13.52 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           41 |     2205 | 2024-06-15 | BESTIA            | W   | 0.633      | 0.548        | -                | 0.807 (0.280)    | 1 (0.633) |     1.76 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           40 |     2224 | 2024-06-14 | Ninjas in Pyjamas | L   | 0.628      | -            | -                | -                | -         |    -9.59 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           39 |     2434 | 2024-06-08 | Imperial          | L   | 0.589      | -            | -                | -                | -         |   -15.80 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           38 |     2491 | 2024-06-07 | Sharks            | W   | 0.583      | 0.450        | -                | 0.537 (0.141)    | -         |     2.01 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           37 |     2549 | 2024-06-06 | MIBR              | W   | 0.576      | 0.450        | 0.156 (0.040)    | 0.644 (0.167)    | -         |     8.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           36 |     2618 | 2024-06-05 | RED Canids        | L   | 0.569      | -            | -                | -                | -         |   -16.18 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           35 |     2668 | 2024-06-04 | Fluxo             | W   | 0.563      | 0.450        | -                | 0.649 (0.164)    | -         |     1.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           34 |     2749 | 2024-06-01 | G2                | L   | 0.542      | -            | -                | -                | -         |    -0.93 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           33 |     2839 | 2024-05-29 | Vitality          | W   | 0.522      | 0.624        | 1.000 (0.326)    | 0.418 (0.136)    | 1 (0.522) |    15.43 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           32 |     2879 | 2024-05-27 | Liquid            | W   | 0.510      | 0.624        | 0.370 (0.118)    | -                | 1 (0.510) |    11.29 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           31 |     2889 | 2024-05-27 | MOUZ              | W   | 0.508      | 0.624        | 1.000 (0.317)    | -                | -         |    14.98 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           30 |     2984 | 2024-05-22 | Imperial          | L   | 0.476      | -            | -                | -                | -         |   -12.68 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           29 |     2988 | 2024-05-22 | Imperial          | L   | 0.476      | -            | -                | -                | -         |   -12.94 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           28 |     3067 | 2024-05-20 | W7M               | W   | 0.463      | -            | -                | -                | -         |     0.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           27 |     3070 | 2024-05-20 | W7M               | W   | 0.463      | -            | -                | -                | -         |     0.35 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           26 |     3071 | 2024-05-20 | BESTIA            | L   | 0.462      | -            | -                | -                | -         |   -13.70 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           25 |     3074 | 2024-05-20 | BESTIA            | W   | 0.462      | 0.450        | -                | 0.807 (0.168)    | -         |     0.83 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           24 |     3101 | 2024-05-19 | RED Canids        | L   | 0.455      | -            | -                | -                | -         |   -13.09 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           23 |     3126 | 2024-05-18 | Fluxo             | W   | 0.448      | -            | -                | -                | -         |     1.22 | buda, HUASOPEEK, Luken, MartinezSa, max |
|           22 |     3191 | 2024-05-16 | ODDIK             | W   | 0.436      | -            | -                | -                | -         |     1.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           21 |     3199 | 2024-05-16 | Imperial          | L   | 0.435      | -            | -                | -                | -         |   -12.03 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           20 |     3236 | 2024-05-15 | RED Canids        | W   | 0.430      | -            | -                | -                | -         |     1.00 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           19 |     3238 | 2024-05-15 | RED Canids        | L   | 0.429      | -            | -                | -                | -         |   -12.62 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           18 |     3245 | 2024-05-15 | Sharks            | W   | 0.429      | -            | -                | -                | -         |     1.13 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           17 |     3297 | 2024-05-14 | Players           | W   | 0.423      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           16 |     3301 | 2024-05-14 | Players           | W   | 0.422      | -            | -                | -                | -         |     0.17 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           15 |     3311 | 2024-05-14 | Galorys           | W   | 0.421      | -            | -                | -                | -         |     0.24 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           14 |     3330 | 2024-05-13 | Galorys           | W   | 0.416      | -            | -                | -                | -         |     0.23 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           13 |     3349 | 2024-05-12 | inSanitY          | W   | 0.410      | -            | -                | -                | -         |     0.47 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           12 |     3354 | 2024-05-12 | paiN              | L   | 0.409      | -            | -                | -                | -         |    -3.92 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           11 |     3381 | 2024-05-11 | KRÜ               | W   | 0.402      | -            | -                | -                | -         |     0.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|           10 |     3408 | 2024-05-10 | inSanitY          | W   | 0.396      | -            | -                | -                | -         |     0.45 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            9 |     3450 | 2024-05-08 | Sharks            | W   | 0.383      | -            | -                | -                | -         |     1.04 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            8 |     3492 | 2024-05-06 | Vikings KR        | W   | 0.368      | -            | -                | -                | -         |     0.22 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            7 |     3584 | 2024-05-01 | Case              | W   | 0.335      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            6 |     3585 | 2024-05-01 | Case              | W   | 0.335      | -            | -                | -                | -         |     0.53 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            5 |     3856 | 2024-04-19 | OG                | L   | 0.257      | -            | -                | -                | -         |    -7.64 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            4 |     3906 | 2024-04-18 | Imperial          | L   | 0.250      | -            | -                | -                | -         |    -7.15 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            3 |     3912 | 2024-04-18 | FURIA             | W   | 0.248      | 0.589        | 0.319 (0.047)    | -                | -         |     5.42 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            2 |     4235 | 2024-04-08 | HEROIC            | L   | 0.179      | -            | -                | -                | -         |    -3.51 | buda, dgt, HUASOPEEK, MartinezSa, max   |
|            1 |     4245 | 2024-04-07 | G2                | L   | 0.178      | -            | -                | -                | -         |    -0.34 | buda, dgt, HUASOPEEK, MartinezSa, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,997.64)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.36) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-08-18 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-07-28 |      0.921 | $2,000.00      | $1,841.94       |
| 2024-06-16 |      0.643 | $100,000.00    | $64,296.30      |
| 2024-06-09 |      0.595 | $7,500.00      | $4,465.97       |
| 2024-06-02 |      0.548 | $20,000.00     | $10,961.11      |
| 2024-05-19 |      0.455 | $4,000.00      | $1,818.89       |
| 2024-05-16 |      0.435 | $5,000.00      | $2,173.61       |
| 2024-05-12 |      0.409 | $15,000.00     | $6,129.17       |
| 2024-04-20 |      0.262 | $5,000.00      | $1,310.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
