### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1237.9<br />
<br />
Final Rank Value (1237.9) = Starting Rank Value (1302.3) + Head To Head Adjustments (-64.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.626[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1302.3
- 400 + ( ( 0.440 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1302.3


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
|           52 |        6 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.83 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       14 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       31 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.508 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.56 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       63 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      112 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.316 (0.045)    | -                | -         |    13.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      203 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      543 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.458 (0.153)    | -         |     2.99 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      563 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.12 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      578 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.67 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      639 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.533 (0.178)    | -         |     5.12 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      647 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.53 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      762 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      810 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.514 (0.190)    | -         |     3.95 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      858 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.80 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      895 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.983 (0.352)    | -         |    13.78 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      896 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.514 (0.184)    | -         |     3.66 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      918 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.533 (0.197)    | -         |     4.84 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      920 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      943 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      951 | 2024-07-05 | kONO            | W   | 0.992      | 0.333        | 0.028 (0.009)    | 0.566 (0.187)    | -         |     3.20 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      961 | 2024-06-30 | Young Gods      | W   | 0.960      | -            | -                | -                | -         |     1.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      983 | 2024-06-27 | Revenant        | W   | 0.938      | 0.333        | 0.027 (0.009)    | -                | -         |     2.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      987 | 2024-06-25 | Revenant        | W   | 0.925      | 0.333        | 0.027 (0.008)    | -                | -         |     2.42 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      994 | 2024-06-23 | los kogutos     | W   | 0.912      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1061 | 2024-06-15 | Lilmix          | W   | 0.859      | -            | -                | -                | 1 (0.859) |     2.97 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1103 | 2024-06-14 | Lilmix          | W   | 0.852      | -            | -                | -                | 1 (0.852) |     2.91 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1145 | 2024-06-13 | Kappa Bar       | W   | 0.844      | -            | -                | -                | 1 (0.844) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1247 | 2024-06-09 | Alliance        | W   | 0.819      | -            | -                | -                | 1 (0.819) |     2.76 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1282 | 2024-06-09 | Preasy          | W   | 0.818      | -            | -                | -                | 1 (0.818) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1557 | 2024-06-04 | Enterprise      | L   | 0.784      | -            | -                | -                | -         |   -21.16 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1575 | 2024-06-03 | brazylijski luz | W   | 0.779      | -            | -                | -                | -         |     2.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1577 | 2024-06-03 | Zero Tenacity   | W   | 0.778      | 0.371        | 0.143 (0.041)    | 1.000 (0.288)    | -         |     8.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1667 | 2024-05-31 | UNiTY           | L   | 0.757      | -            | -                | -                | -         |   -20.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1772 | 2024-05-26 | Preasy          | W   | 0.725      | -            | -                | -                | -         |     1.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1876 | 2024-05-22 | Permitta        | W   | 0.698      | 0.371        | -                | 0.863 (0.223)    | -         |     2.34 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2184 | 2024-05-14 | kONO            | L   | 0.644      | -            | -                | -                | -         |   -18.69 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2200 | 2024-05-13 | UNiTY           | W   | 0.639      | -            | -                | -                | -         |     2.82 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2205 | 2024-05-13 | ECLOT           | W   | 0.637      | 0.333        | 0.062 (0.013)    | -                | -         |     7.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2216 | 2024-05-12 | Verdant         | W   | 0.634      | -            | -                | -                | -         |     2.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2229 | 2024-05-12 | Preasy          | L   | 0.631      | -            | -                | -                | -         |   -18.83 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2246 | 2024-05-11 | Lilmix          | W   | 0.627      | -            | -                | -                | 1 (0.627) |     1.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2261 | 2024-05-11 | Flying Angels   | W   | 0.625      | -            | -                | -                | 1 (0.625) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2277 | 2024-05-10 | FAVBET          | W   | 0.618      | -            | -                | -                | -         |     1.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2803 | 2024-04-18 | UNiTY           | W   | 0.471      | -            | -                | -                | -         |     2.07 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2867 | 2024-04-16 | Viperio         | W   | 0.459      | -            | -                | -                | -         |     0.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3113 | 2024-04-07 | Alliance        | W   | 0.400      | -            | -                | -                | -         |     1.02 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3121 | 2024-04-07 | Metizport       | L   | 0.398      | -            | -                | -                | -         |   -11.40 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3131 | 2024-04-06 | JANO            | W   | 0.392      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3730 | 2024-03-09 | Alliance        | L   | 0.206      | -            | -                | -                | -         |    -5.98 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3834 | 2024-03-05 | B8              | L   | 0.181      | -            | -                | -                | -         |    -4.41 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3839 | 2024-03-05 | Insilio         | W   | 0.180      | -            | -                | -                | -         |     0.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3845 | 2024-03-05 | Sashi           | W   | 0.180      | -            | -                | -                | -         |     1.64 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,286.29)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.960 | $662.00        | $635.34         |
| 2024-06-27 |      0.938 | $5,000.00      | $4,687.50       |
| 2024-06-15 |      0.859 | $11,615.00     | $9,979.76       |
| 2024-06-09 |      0.819 | $7,224.00      | $5,919.67       |
| 2024-06-06 |      0.797 | $1,000.00      | $797.50         |
| 2024-05-13 |      0.637 | $6,000.00      | $3,825.00       |
| 2024-05-11 |      0.627 | $4,170.00      | $2,613.20       |
| 2024-04-18 |      0.471 | $6,000.00      | $2,828.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
