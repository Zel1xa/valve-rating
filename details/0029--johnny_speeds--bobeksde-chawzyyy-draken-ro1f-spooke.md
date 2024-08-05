### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1257.5<br />
<br />
Final Rank Value (1257.5) = Starting Rank Value (1301.1) + Head To Head Adjustments (-43.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.628[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1301.1
- 400 + ( ( 0.440 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1301.1


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
|           50 |       10 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.507 (0.072)    | 1.000 (0.143)    | 0 (0.000) |    23.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       42 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |       91 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.317 (0.045)    | -                | 0 (0.000) |    13.01 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      182 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      522 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | -         |     2.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      542 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.15 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      557 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      618 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.539 (0.180)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      626 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.57 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      741 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.06 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      789 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.522 (0.193)    | -         |     3.95 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      837 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.12 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      874 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.961 (0.344)    | -         |    13.77 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      875 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | -         |     3.65 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      897 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.539 (0.200)    | -         |     4.82 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      899 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.45 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      922 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      930 | 2024-07-05 | kONO            | W   | 0.996      | 0.333        | 0.028 (0.009)    | 0.536 (0.178)    | -         |     3.21 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      940 | 2024-06-30 | Young Gods      | W   | 0.964      | -            | -                | -                | -         |     1.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      962 | 2024-06-27 | Revenant        | W   | 0.942      | 0.333        | 0.027 (0.009)    | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      966 | 2024-06-25 | Revenant        | W   | 0.929      | 0.333        | 0.027 (0.008)    | -                | -         |     2.40 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      973 | 2024-06-23 | los kogutos     | W   | 0.916      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1040 | 2024-06-15 | Lilmix          | W   | 0.864      | -            | -                | -                | 1 (0.864) |     2.98 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1082 | 2024-06-14 | Lilmix          | W   | 0.857      | -            | -                | -                | 1 (0.857) |     2.92 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1124 | 2024-06-13 | Kappa Bar       | W   | 0.849      | -            | -                | -                | 1 (0.849) |     0.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1226 | 2024-06-09 | Alliance        | W   | 0.824      | -            | -                | -                | 1 (0.824) |     2.78 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1261 | 2024-06-09 | Preasy          | W   | 0.822      | -            | -                | -                | 1 (0.822) |     1.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1536 | 2024-06-04 | Enterprise      | L   | 0.789      | -            | -                | -                | -         |   -21.30 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1554 | 2024-06-03 | brazylijski luz | W   | 0.784      | -            | -                | -                | -         |     2.13 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1556 | 2024-06-03 | Zero Tenacity   | W   | 0.783      | 0.371        | 0.137 (0.040)    | 1.000 (0.290)    | -         |     8.34 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1646 | 2024-05-31 | UNiTY           | L   | 0.762      | -            | -                | -                | -         |   -20.46 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1751 | 2024-05-26 | Preasy          | W   | 0.729      | -            | -                | -                | -         |     1.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1855 | 2024-05-22 | Permitta        | W   | 0.702      | 0.371        | -                | 0.876 (0.228)    | -         |     2.35 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2163 | 2024-05-14 | kONO            | L   | 0.649      | -            | -                | -                | -         |   -18.81 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2179 | 2024-05-13 | UNiTY           | W   | 0.643      | -            | -                | -                | -         |     2.84 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2184 | 2024-05-13 | ECLOT           | W   | 0.642      | 0.333        | 0.062 (0.013)    | -                | -         |     7.55 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2195 | 2024-05-12 | Verdant         | W   | 0.638      | -            | -                | -                | -         |     2.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2208 | 2024-05-12 | Preasy          | L   | 0.636      | -            | -                | -                | -         |   -18.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2225 | 2024-05-11 | Lilmix          | W   | 0.631      | -            | -                | -                | 1 (0.631) |     1.79 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2240 | 2024-05-11 | Flying Angels   | W   | 0.629      | -            | -                | -                | 1 (0.629) |     0.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2256 | 2024-05-10 | FAVBET          | W   | 0.622      | -            | -                | -                | -         |     1.11 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2782 | 2024-04-18 | UNiTY           | W   | 0.476      | -            | -                | -                | -         |     2.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2846 | 2024-04-16 | Viperio         | W   | 0.463      | -            | -                | -                | -         |     0.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3092 | 2024-04-07 | Alliance        | W   | 0.404      | -            | -                | -                | -         |     1.04 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3100 | 2024-04-07 | Metizport       | L   | 0.403      | -            | -                | -                | -         |   -11.51 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3110 | 2024-04-06 | JANO            | W   | 0.397      | -            | -                | -                | -         |     0.38 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3709 | 2024-03-09 | Alliance        | L   | 0.210      | -            | -                | -                | -         |    -6.11 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3813 | 2024-03-05 | B8              | L   | 0.185      | -            | -                | -                | -         |    -4.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3818 | 2024-03-05 | Insilio         | W   | 0.185      | -            | -                | -                | -         |     0.53 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3824 | 2024-03-05 | Sashi           | W   | 0.184      | -            | -                | -                | -         |     1.69 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,471.50)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.964 | $662.00        | $638.28         |
| 2024-06-27 |      0.942 | $5,000.00      | $4,709.72       |
| 2024-06-15 |      0.864 | $11,615.00     | $10,031.38      |
| 2024-06-09 |      0.824 | $7,224.00      | $5,951.77       |
| 2024-06-06 |      0.802 | $1,000.00      | $801.94         |
| 2024-05-13 |      0.642 | $6,000.00      | $3,851.67       |
| 2024-05-11 |      0.631 | $4,170.00      | $2,631.73       |
| 2024-04-18 |      0.476 | $6,000.00      | $2,855.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
