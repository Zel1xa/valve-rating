### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, roman, story<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1186.0<br />
<br />
Final Rank Value (1186.0) = Starting Rank Value (1179.4) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.508[<sup>1</sup>](#table2)
- Bounty Collected: 0.506[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.379<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1179.4
- 400 + ( ( 0.379 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1179.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       50 | 2024-07-31 | brazylijski luz   | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | 0 (0.000) |     4.56 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           53 |      168 | 2024-07-28 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -8.81 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           52 |      181 | 2024-07-27 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |    12.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           51 |      255 | 2024-07-25 | BC.Game           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.25 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           50 |      284 | 2024-07-24 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -23.34 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           49 |      445 | 2024-07-19 | RUSH B            | W   | 1.000      | 0.500        | -                | 0.308 (0.154)    | -         |     5.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           48 |      561 | 2024-07-17 | Sangal            | W   | 1.000      | 0.500        | 0.221 (0.110)    | 0.823 (0.412)    | -         |    16.49 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           47 |      677 | 2024-07-15 | SINNERS           | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.768 (0.384)    | -         |     7.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           46 |     1009 | 2024-06-13 | Astralis          | L   | 0.871      | -            | -                | -                | -         |    -1.45 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           45 |     1035 | 2024-06-12 | FaZe              | L   | 0.865      | -            | -                | -                | -         |    -1.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           44 |     1077 | 2024-06-10 | 3DMAX             | L   | 0.852      | -            | -                | -                | -         |    -5.68 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           43 |     1086 | 2024-06-10 | RUSH B            | W   | 0.852      | -            | -                | -                | -         |     5.61 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           42 |     1089 | 2024-06-10 | Aurora            | W   | 0.851      | 0.143        | 0.431 (0.052)    | 0.798 (0.097)    | -         |    21.36 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           41 |     1122 | 2024-06-09 | SINNERS           | L   | 0.846      | -            | -                | -                | -         |   -17.97 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           40 |     1128 | 2024-06-09 | Monte             | W   | 0.845      | -            | -                | -                | -         |     7.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           39 |     1135 | 2024-06-09 | 9 Pandas          | L   | 0.845      | -            | -                | -                | -         |   -16.60 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           38 |     1141 | 2024-06-09 | PARIVISION        | W   | 0.845      | -            | -                | -                | -         |    10.12 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           37 |     1373 | 2024-06-05 | Sangal            | L   | 0.820      | -            | -                | -                | -         |   -15.16 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           36 |     1423 | 2024-06-04 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -22.30 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           35 |     1473 | 2024-06-02 | Zero Tenacity     | L   | 0.799      | -            | -                | -                | -         |   -16.39 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           34 |     1538 | 2024-05-31 | Sangal            | W   | 0.786      | 0.143        | 0.221 (0.025)    | -                | -         |     8.52 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           33 |     1544 | 2024-05-31 | fnatic            | L   | 0.786      | -            | -                | -                | -         |    -8.91 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           32 |     1549 | 2024-05-31 | FAVBET            | W   | 0.785      | -            | -                | -                | -         |     2.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           31 |     1950 | 2024-05-17 | Aurora            | L   | 0.691      | -            | -                | -                | -         |    -2.98 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           30 |     1972 | 2024-05-16 | Eternal Fire      | L   | 0.687      | -            | -                | -                | -         |    -1.51 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           29 |     1987 | 2024-05-16 | Aurora            | W   | 0.684      | 0.769        | 0.431 (0.227)    | 0.798 (0.420)    | -         |    19.06 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           28 |     2443 | 2024-04-28 | Virtus.pro        | L   | 0.566      | -            | -                | -                | -         |    -1.17 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           27 |     2459 | 2024-04-27 | Eternal Fire      | W   | 0.560      | 0.889        | 0.757 (0.377)    | 0.461 (0.229)    | 1 (0.560) |    16.64 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           26 |     2492 | 2024-04-26 | Imperial          | W   | 0.552      | 0.889        | 0.239 (0.117)    | 0.719 (0.353)    | 1 (0.552) |    11.31 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           25 |     2540 | 2024-04-24 | Virtus.pro        | L   | 0.539      | -            | -                | -                | -         |    -0.95 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           24 |     2566 | 2024-04-23 | 3DMAX             | L   | 0.532      | -            | -                | -                | -         |    -1.31 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           23 |     2806 | 2024-04-16 | Sampi             | L   | 0.485      | -            | -                | -                | -         |   -12.52 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           22 |     2925 | 2024-04-10 | 9 Pandas          | W   | 0.447      | 0.500        | 0.083 (0.019)    | 0.577 (0.129)    | -         |     3.54 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           21 |     2980 | 2024-04-09 | 3DMAX             | L   | 0.440      | -            | -                | -                | -         |    -0.94 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           20 |     3086 | 2024-04-05 | PGE Turow         | W   | 0.411      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           19 |     3121 | 2024-04-04 | Betera            | W   | 0.406      | -            | -                | -                | -         |     0.85 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           18 |     3170 | 2024-04-03 | PERA              | W   | 0.399      | -            | -                | -                | -         |     2.26 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           17 |     3422 | 2024-03-20 | FURIA             | L   | 0.307      | -            | -                | -                | -         |    -0.46 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           16 |     3439 | 2024-03-19 | paiN              | L   | 0.299      | -            | -                | -                | -         |    -2.58 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           15 |     3447 | 2024-03-18 | Cloud9            | L   | 0.293      | -            | -                | -                | -         |    -6.21 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           14 |     3460 | 2024-03-17 | GamerLegion       | W   | 0.288      | -            | -                | -                | 1 (0.288) |     0.92 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           13 |     3477 | 2024-03-17 | KOI               | W   | 0.286      | -            | -                | -                | 1 (0.286) |     1.80 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           12 |     3572 | 2024-03-13 | System5           | W   | 0.260      | -            | -                | -                | -         |     0.44 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           11 |     3656 | 2024-03-10 | OG                | W   | 0.240      | -            | -                | -                | -         |     1.99 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           10 |     3698 | 2024-03-08 | Cloud9            | W   | 0.227      | -            | -                | -                | -         |     2.33 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            9 |     3732 | 2024-03-07 | Liquid            | W   | 0.219      | 0.535        | 0.321 (0.038)    | -                | -         |     5.98 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            8 |     3789 | 2024-03-05 | Monte             | W   | 0.207      | -            | -                | -                | -         |     1.82 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            7 |     3959 | 2024-02-26 | RUSH B            | W   | 0.154      | -            | -                | -                | -         |     0.65 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            6 |     4181 | 2024-02-17 | fnatic            | W   | 0.092      | -            | -                | -                | 1 (0.092) |     2.17 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            5 |     4203 | 2024-02-16 | Enterprise        | W   | 0.087      | -            | -                | -                | 1 (0.087) |     0.53 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            4 |     4238 | 2024-02-15 | Ninjas in Pyjamas | W   | 0.079      | -            | -                | -                | 1 (0.079) |     0.03 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            3 |     4276 | 2024-02-14 | 9 Pandas          | L   | 0.073      | -            | -                | -                | -         |    -1.67 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            2 |     4287 | 2024-02-14 | Virtus.pro        | L   | 0.071      | -            | -                | -                | -         |    -0.11 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|            1 |     4423 | 2024-02-04 | Rhyno             | W   | 0.006      | -            | -                | -                | -         |     0.04 | arrozdoce, ewjerkz, MUTiRiS, roman, story |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,203.72)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.892 | $10,000.00     | $8,922.22       |
| 2024-06-09 |      0.846 | $6,500.00      | $5,499.27       |
| 2024-05-12 |      0.659 | $12,000.00     | $7,910.00       |
| 2024-03-20 |      0.307 | $10,000.00     | $3,065.28       |
| 2024-03-10 |      0.240 | $20,000.00     | $4,806.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
