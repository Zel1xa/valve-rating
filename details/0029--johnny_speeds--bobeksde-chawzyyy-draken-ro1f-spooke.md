### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1257.6<br />
<br />
Final Rank Value (1257.6) = Starting Rank Value (1301.3) + Head To Head Adjustments (-43.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.629[<sup>2</sup>](#table1)

The average of these factors is 0.441<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1301.3
- 400 + ( ( 0.441 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1301.3


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
|           50 |        7 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.506 (0.072)    | 1.000 (0.143)    | 0 (0.000) |    23.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       39 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |       87 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.317 (0.045)    | -                | 0 (0.000) |    13.03 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      178 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      518 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | -         |     2.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      538 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.14 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      553 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      614 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.537 (0.179)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      622 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.57 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      737 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.07 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      785 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.522 (0.194)    | -         |     3.95 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      833 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      870 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.962 (0.344)    | -         |    13.78 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      871 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | -         |     3.65 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      893 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.537 (0.199)    | -         |     4.81 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      895 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.45 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      918 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      926 | 2024-07-05 | kONO            | W   | 0.999      | 0.333        | 0.028 (0.009)    | 0.536 (0.178)    | -         |     3.23 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      936 | 2024-06-30 | Young Gods      | W   | 0.967      | -            | -                | -                | -         |     1.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      958 | 2024-06-27 | Revenant        | W   | 0.944      | 0.333        | 0.027 (0.009)    | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      962 | 2024-06-25 | Revenant        | W   | 0.932      | 0.333        | 0.027 (0.008)    | -                | -         |     2.41 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      969 | 2024-06-23 | los kogutos     | W   | 0.918      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1036 | 2024-06-15 | Lilmix          | W   | 0.866      | -            | -                | -                | 1 (0.866) |     2.99 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1078 | 2024-06-14 | Lilmix          | W   | 0.859      | -            | -                | -                | 1 (0.859) |     2.93 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1120 | 2024-06-13 | Kappa Bar       | W   | 0.851      | -            | -                | -                | 1 (0.851) |     0.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1222 | 2024-06-09 | Alliance        | W   | 0.826      | -            | -                | -                | 1 (0.826) |     2.79 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1257 | 2024-06-09 | Preasy          | W   | 0.824      | -            | -                | -                | 1 (0.824) |     1.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1532 | 2024-06-04 | Enterprise      | L   | 0.791      | -            | -                | -                | -         |   -21.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1550 | 2024-06-03 | brazylijski luz | W   | 0.786      | -            | -                | -                | -         |     2.14 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1552 | 2024-06-03 | Zero Tenacity   | W   | 0.785      | 0.371        | 0.137 (0.040)    | 1.000 (0.291)    | -         |     8.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1642 | 2024-05-31 | UNiTY           | L   | 0.764      | -            | -                | -                | -         |   -20.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1747 | 2024-05-26 | Preasy          | W   | 0.732      | -            | -                | -                | -         |     1.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1851 | 2024-05-22 | Permitta        | W   | 0.704      | 0.371        | -                | 0.876 (0.229)    | -         |     2.35 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2159 | 2024-05-14 | kONO            | L   | 0.651      | -            | -                | -                | -         |   -18.88 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2175 | 2024-05-13 | UNiTY           | W   | 0.646      | -            | -                | -                | -         |     2.85 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2180 | 2024-05-13 | ECLOT           | W   | 0.644      | 0.333        | 0.062 (0.013)    | -                | -         |     7.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2191 | 2024-05-12 | Verdant         | W   | 0.640      | -            | -                | -                | -         |     2.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2204 | 2024-05-12 | Preasy          | L   | 0.638      | -            | -                | -                | -         |   -18.98 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2221 | 2024-05-11 | Lilmix          | W   | 0.633      | -            | -                | -                | 1 (0.633) |     1.80 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2236 | 2024-05-11 | Flying Angels   | W   | 0.632      | -            | -                | -                | 1 (0.632) |     0.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2252 | 2024-05-10 | FAVBET          | W   | 0.624      | -            | -                | -                | -         |     1.12 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2778 | 2024-04-18 | UNiTY           | W   | 0.478      | -            | -                | -                | -         |     2.11 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2842 | 2024-04-16 | Viperio         | W   | 0.465      | -            | -                | -                | -         |     0.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3088 | 2024-04-07 | Alliance        | W   | 0.407      | -            | -                | -                | -         |     1.05 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3096 | 2024-04-07 | Metizport       | L   | 0.405      | -            | -                | -                | -         |   -11.57 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3106 | 2024-04-06 | JANO            | W   | 0.399      | -            | -                | -                | -         |     0.38 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3705 | 2024-03-09 | Alliance        | L   | 0.213      | -            | -                | -                | -         |    -6.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3809 | 2024-03-05 | B8              | L   | 0.187      | -            | -                | -                | -         |    -4.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3814 | 2024-03-05 | Insilio         | W   | 0.187      | -            | -                | -                | -         |     0.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3820 | 2024-03-05 | Sashi           | W   | 0.187      | -            | -                | -                | -         |     1.71 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,570.85)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.967 | $662.00        | $639.86         |
| 2024-06-27 |      0.944 | $5,000.00      | $4,721.64       |
| 2024-06-15 |      0.866 | $11,615.00     | $10,059.07      |
| 2024-06-09 |      0.826 | $7,224.00      | $5,969.00       |
| 2024-06-06 |      0.804 | $1,000.00      | $804.33         |
| 2024-05-13 |      0.644 | $6,000.00      | $3,865.97       |
| 2024-05-11 |      0.633 | $4,170.00      | $2,641.68       |
| 2024-04-18 |      0.478 | $6,000.00      | $2,869.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
