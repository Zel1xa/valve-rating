### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1236.4<br />
<br />
Final Rank Value (1236.4) = Starting Rank Value (1302.2) + Head To Head Adjustments (-65.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.627[<sup>2</sup>](#table1)

The average of these factors is 0.441<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1302.2
- 400 + ( ( 0.441 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1302.2


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
|           51 |        7 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.38 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       24 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.508 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.52 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       56 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.48 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      104 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.316 (0.045)    | -                | 0 (0.000) |    12.98 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      196 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.31 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      535 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.464 (0.155)    | -         |     2.97 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      555 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.17 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      570 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.60 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      631 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.539 (0.180)    | -         |     5.09 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      639 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.52 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      754 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.07 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      802 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.520 (0.193)    | -         |     3.94 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      850 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.85 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      887 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.996 (0.356)    | -         |    13.73 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      888 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.520 (0.186)    | -         |     3.64 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      910 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.539 (0.200)    | -         |     4.81 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      912 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.46 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      935 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      943 | 2024-07-05 | kONO            | W   | 0.993      | 0.333        | 0.028 (0.009)    | 0.574 (0.190)    | -         |     3.18 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      953 | 2024-06-30 | Young Gods      | W   | 0.961      | -            | -                | -                | -         |     1.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      975 | 2024-06-27 | Revenant        | W   | 0.939      | 0.333        | 0.027 (0.009)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      979 | 2024-06-25 | Revenant        | W   | 0.926      | 0.333        | 0.027 (0.008)    | -                | -         |     2.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      986 | 2024-06-23 | los kogutos     | W   | 0.913      | -            | -                | -                | -         |     0.25 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1053 | 2024-06-15 | Lilmix          | W   | 0.860      | -            | -                | -                | 1 (0.860) |     2.95 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1095 | 2024-06-14 | Lilmix          | W   | 0.853      | -            | -                | -                | 1 (0.853) |     2.90 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1137 | 2024-06-13 | Kappa Bar       | W   | 0.845      | -            | -                | -                | 1 (0.845) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1239 | 2024-06-09 | Alliance        | W   | 0.821      | -            | -                | -                | 1 (0.821) |     2.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1274 | 2024-06-09 | Preasy          | W   | 0.819      | -            | -                | -                | 1 (0.819) |     1.91 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1549 | 2024-06-04 | Enterprise      | L   | 0.785      | -            | -                | -                | -         |   -21.24 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1567 | 2024-06-03 | brazylijski luz | W   | 0.780      | -            | -                | -                | -         |     2.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1569 | 2024-06-03 | Zero Tenacity   | W   | 0.780      | 0.371        | 0.137 (0.040)    | 1.000 (0.289)    | -         |     8.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1659 | 2024-05-31 | UNiTY           | L   | 0.759      | -            | -                | -                | -         |   -20.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1764 | 2024-05-26 | Preasy          | W   | 0.726      | -            | -                | -                | -         |     1.53 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1868 | 2024-05-22 | Permitta        | W   | 0.699      | 0.371        | -                | 0.873 (0.226)    | -         |     2.33 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2176 | 2024-05-14 | kONO            | L   | 0.645      | -            | -                | -                | -         |   -18.73 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2192 | 2024-05-13 | UNiTY           | W   | 0.640      | -            | -                | -                | -         |     2.81 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2197 | 2024-05-13 | ECLOT           | W   | 0.639      | 0.333        | 0.062 (0.013)    | -                | -         |     7.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2208 | 2024-05-12 | Verdant         | W   | 0.635      | -            | -                | -                | -         |     2.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2221 | 2024-05-12 | Preasy          | L   | 0.632      | -            | -                | -                | -         |   -18.82 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2238 | 2024-05-11 | Lilmix          | W   | 0.628      | -            | -                | -                | 1 (0.628) |     1.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2253 | 2024-05-11 | Flying Angels   | W   | 0.626      | -            | -                | -                | 1 (0.626) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2269 | 2024-05-10 | FAVBET          | W   | 0.619      | -            | -                | -                | -         |     1.10 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2795 | 2024-04-18 | UNiTY           | W   | 0.472      | -            | -                | -                | -         |     2.07 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2859 | 2024-04-16 | Viperio         | W   | 0.460      | -            | -                | -                | -         |     0.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3105 | 2024-04-07 | Alliance        | W   | 0.401      | -            | -                | -                | -         |     1.02 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3113 | 2024-04-07 | Metizport       | L   | 0.399      | -            | -                | -                | -         |   -11.43 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3123 | 2024-04-06 | JANO            | W   | 0.393      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3722 | 2024-03-09 | Alliance        | L   | 0.207      | -            | -                | -                | -         |    -6.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3826 | 2024-03-05 | B8              | L   | 0.182      | -            | -                | -                | -         |    -4.43 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3831 | 2024-03-05 | Insilio         | W   | 0.181      | -            | -                | -                | -         |     0.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3837 | 2024-03-05 | Sashi           | W   | 0.181      | -            | -                | -                | -         |     1.65 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,332.60)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.961 | $662.00        | $636.07         |
| 2024-06-27 |      0.939 | $5,000.00      | $4,693.06       |
| 2024-06-15 |      0.860 | $11,615.00     | $9,992.66       |
| 2024-06-09 |      0.821 | $7,224.00      | $5,927.69       |
| 2024-06-06 |      0.799 | $1,000.00      | $798.61         |
| 2024-05-13 |      0.639 | $6,000.00      | $3,831.67       |
| 2024-05-11 |      0.628 | $4,170.00      | $2,617.83       |
| 2024-04-18 |      0.472 | $6,000.00      | $2,835.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
