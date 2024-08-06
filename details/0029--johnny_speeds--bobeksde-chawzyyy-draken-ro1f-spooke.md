### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1243.7<br />
<br />
Final Rank Value (1243.7) = Starting Rank Value (1302.9) + Head To Head Adjustments (-59.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.402[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.624[<sup>2</sup>](#table1)

The average of these factors is 0.439<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1302.9
- 400 + ( ( 0.439 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1302.9


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
|           53 |        0 | 2024-08-06 | Metizport       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.50 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           52 |       17 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       25 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.36 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       42 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.510 (0.073)    | 1.000 (0.143)    | 0 (0.000) |    23.61 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       74 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | -         |     2.49 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      123 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.315 (0.045)    | -                | -         |    12.99 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      214 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.28 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      554 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.447 (0.149)    | -         |     3.01 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      574 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      589 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      650 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.523 (0.174)    | -         |     5.10 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      658 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.51 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      773 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      821 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.502 (0.186)    | -         |     3.95 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      869 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.81 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      906 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.958 (0.343)    | -         |    13.72 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      907 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.502 (0.180)    | -         |     3.65 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      929 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.523 (0.194)    | -         |     4.82 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      931 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.44 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      954 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      962 | 2024-07-05 | kONO            | W   | 0.987      | 0.333        | 0.028 (0.009)    | 0.553 (0.182)    | -         |     3.20 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      972 | 2024-06-30 | Young Gods      | W   | 0.955      | -            | -                | -                | -         |     1.37 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      994 | 2024-06-27 | Revenant        | W   | 0.932      | 0.333        | 0.027 (0.009)    | -                | -         |     2.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      998 | 2024-06-25 | Revenant        | W   | 0.920      | 0.333        | 0.027 (0.008)    | -                | -         |     2.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     1005 | 2024-06-23 | los kogutos     | W   | 0.907      | -            | -                | -                | -         |     0.24 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1072 | 2024-06-15 | Lilmix          | W   | 0.854      | -            | -                | -                | 1 (0.854) |     2.94 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1114 | 2024-06-14 | Lilmix          | W   | 0.847      | -            | -                | -                | 1 (0.847) |     2.89 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1156 | 2024-06-13 | Kappa Bar       | W   | 0.839      | -            | -                | -                | 1 (0.839) |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1258 | 2024-06-09 | Alliance        | W   | 0.814      | -            | -                | -                | 1 (0.814) |     2.73 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1293 | 2024-06-09 | Preasy          | W   | 0.813      | -            | -                | -                | 1 (0.813) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1568 | 2024-06-04 | Enterprise      | L   | 0.779      | -            | -                | -                | -         |   -21.03 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1586 | 2024-06-03 | brazylijski luz | W   | 0.774      | -            | -                | -                | -         |     2.07 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1588 | 2024-06-03 | Zero Tenacity   | W   | 0.773      | 0.371        | 0.143 (0.041)    | 1.000 (0.287)    | -         |     8.24 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1678 | 2024-05-31 | UNiTY           | L   | 0.752      | -            | -                | -                | -         |   -20.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1783 | 2024-05-26 | Preasy          | W   | 0.720      | -            | -                | -                | -         |     1.47 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1887 | 2024-05-22 | Permitta        | W   | 0.693      | 0.371        | -                | 0.919 (0.236)    | -         |     2.39 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2195 | 2024-05-14 | kONO            | L   | 0.639      | -            | -                | -                | -         |   -18.53 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2211 | 2024-05-13 | UNiTY           | W   | 0.634      | -            | -                | -                | -         |     2.77 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2216 | 2024-05-13 | ECLOT           | W   | 0.632      | 0.333        | 0.061 (0.013)    | -                | -         |     7.42 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2227 | 2024-05-12 | Verdant         | W   | 0.629      | -            | -                | -                | -         |     2.52 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2240 | 2024-05-12 | Preasy          | L   | 0.626      | -            | -                | -                | -         |   -18.69 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2257 | 2024-05-11 | Lilmix          | W   | 0.622      | -            | -                | -                | 1 (0.622) |     1.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2272 | 2024-05-11 | Flying Angels   | W   | 0.620      | -            | -                | -                | 1 (0.620) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2288 | 2024-05-10 | FAVBET          | W   | 0.613      | -            | -                | -                | -         |     1.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2814 | 2024-04-18 | UNiTY           | W   | 0.466      | -            | -                | -                | -         |     2.03 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2878 | 2024-04-16 | Viperio         | W   | 0.454      | -            | -                | -                | -         |     0.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3124 | 2024-04-07 | Alliance        | W   | 0.395      | -            | -                | -                | -         |     1.00 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3132 | 2024-04-07 | Metizport       | L   | 0.393      | -            | -                | -                | -         |   -10.89 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3142 | 2024-04-06 | JANO            | W   | 0.387      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3741 | 2024-03-09 | Alliance        | L   | 0.201      | -            | -                | -                | -         |    -5.84 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3845 | 2024-03-05 | B8              | L   | 0.176      | -            | -                | -                | -         |    -4.28 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3850 | 2024-03-05 | Insilio         | W   | 0.175      | -            | -                | -                | -         |     0.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3856 | 2024-03-05 | Sashi           | W   | 0.175      | -            | -                | -                | -         |     1.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,077.94)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.955 | $662.00        | $632.03         |
| 2024-06-27 |      0.932 | $5,000.00      | $4,662.50       |
| 2024-06-15 |      0.854 | $11,615.00     | $9,921.68       |
| 2024-06-09 |      0.814 | $7,224.00      | $5,883.55       |
| 2024-06-06 |      0.792 | $1,000.00      | $792.50         |
| 2024-05-13 |      0.632 | $6,000.00      | $3,795.00       |
| 2024-05-11 |      0.622 | $4,170.00      | $2,592.35       |
| 2024-04-18 |      0.466 | $6,000.00      | $2,798.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
