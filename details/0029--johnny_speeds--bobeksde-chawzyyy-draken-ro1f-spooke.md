### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1228.8<br />
<br />
Final Rank Value (1228.8) = Starting Rank Value (1292.7) + Head To Head Adjustments (-63.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.629[<sup>2</sup>](#table1)

The average of these factors is 0.437<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1292.7
- 400 + ( ( 0.437 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1292.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |        9 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.56 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |       57 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.317 (0.045)    | -                | 0 (0.000) |    12.80 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      147 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    24.40 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      486 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | -         |     3.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      506 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.05 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      521 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      582 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.537 (0.179)    | -         |     5.22 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      590 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.52 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      705 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.14 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      753 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.522 (0.194)    | -         |     4.03 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      801 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.00 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      838 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.962 (0.345)    | -         |    13.90 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      839 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | -         |     3.73 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      861 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.537 (0.199)    | -         |     4.93 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      863 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.37 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      886 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.60 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      894 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | -         |     3.34 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      904 | 2024-06-30 | Young Gods      | W   | 0.968      | -            | -                | -                | -         |     1.44 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      926 | 2024-06-27 | Revenant        | W   | 0.946      | 0.333        | 0.027 (0.009)    | -                | -         |     2.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      930 | 2024-06-25 | Revenant        | W   | 0.934      | 0.333        | 0.027 (0.008)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      937 | 2024-06-23 | los kogutos     | W   | 0.920      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1004 | 2024-06-15 | Lilmix          | W   | 0.868      | 0.377        | 0.023 (0.007)    | -                | 1 (0.868) |     3.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1046 | 2024-06-14 | Lilmix          | W   | 0.861      | -            | -                | -                | 1 (0.861) |     3.04 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1088 | 2024-06-13 | Kappa Bar       | W   | 0.853      | -            | -                | -                | 1 (0.853) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1190 | 2024-06-09 | Alliance        | W   | 0.828      | -            | -                | -                | 1 (0.828) |     2.89 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1225 | 2024-06-09 | Preasy          | W   | 0.826      | -            | -                | -                | 1 (0.826) |     2.00 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1500 | 2024-06-04 | Enterprise      | L   | 0.793      | -            | -                | -                | -         |   -21.30 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1518 | 2024-06-03 | brazylijski luz | W   | 0.788      | -            | -                | -                | -         |     2.20 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1520 | 2024-06-03 | Zero Tenacity   | W   | 0.787      | 0.371        | 0.137 (0.040)    | 1.000 (0.292)    | -         |     8.63 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1610 | 2024-05-31 | UNiTY           | L   | 0.766      | -            | -                | -                | -         |   -20.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1715 | 2024-05-26 | Preasy          | W   | 0.734      | -            | -                | -                | -         |     1.61 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1819 | 2024-05-22 | Permitta        | W   | 0.706      | 0.371        | -                | 0.876 (0.229)    | -         |     2.42 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2127 | 2024-05-14 | kONO            | L   | 0.653      | -            | -                | -                | -         |   -18.86 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2143 | 2024-05-13 | UNiTY           | W   | 0.647      | -            | -                | -                | -         |     2.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2148 | 2024-05-13 | ECLOT           | W   | 0.646      | 0.333        | 0.062 (0.013)    | 0.559 (0.120)    | -         |     7.72 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2159 | 2024-05-12 | Verdant         | W   | 0.642      | -            | -                | -                | -         |     2.68 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2172 | 2024-05-12 | Preasy          | L   | 0.640      | -            | -                | -                | -         |   -18.99 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2189 | 2024-05-11 | Lilmix          | W   | 0.635      | -            | -                | -                | 1 (0.635) |     1.88 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2204 | 2024-05-11 | Flying Angels   | W   | 0.633      | -            | -                | -                | 1 (0.633) |     0.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2220 | 2024-05-10 | FAVBET          | W   | 0.626      | -            | -                | -                | -         |     1.17 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2746 | 2024-04-18 | UNiTY           | W   | 0.480      | -            | -                | -                | -         |     2.17 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2810 | 2024-04-16 | Viperio         | W   | 0.467      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3056 | 2024-04-07 | Alliance        | W   | 0.408      | -            | -                | -                | -         |     1.09 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3064 | 2024-04-07 | Metizport       | L   | 0.407      | -            | -                | -                | -         |   -11.18 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3074 | 2024-04-06 | JANO            | W   | 0.401      | -            | -                | -                | -         |     0.40 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3673 | 2024-03-09 | Alliance        | L   | 0.214      | -            | -                | -                | -         |    -6.21 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3777 | 2024-03-05 | B8              | L   | 0.189      | -            | -                | -                | -         |    -4.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3782 | 2024-03-05 | Insilio         | W   | 0.189      | -            | -                | -                | -         |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3788 | 2024-03-05 | Sashi           | W   | 0.189      | -            | -                | -                | -         |     1.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,645.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.968 | $662.00        | $641.04         |
| 2024-06-27 |      0.946 | $5,000.00      | $4,730.56       |
| 2024-06-15 |      0.868 | $11,615.00     | $10,079.78      |
| 2024-06-09 |      0.828 | $7,224.00      | $5,981.87       |
| 2024-06-06 |      0.806 | $1,000.00      | $806.11         |
| 2024-05-13 |      0.646 | $6,000.00      | $3,876.67       |
| 2024-05-11 |      0.635 | $4,170.00      | $2,649.11       |
| 2024-04-18 |      0.480 | $6,000.00      | $2,880.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
