### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1261.7<br />
<br />
Final Rank Value (1261.7) = Starting Rank Value (1303.9) + Head To Head Adjustments (-42.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.522[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.207[<sup>2</sup>](#table1)
- LAN Wins: 0.624[<sup>2</sup>](#table1)

The average of these factors is 0.439<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1303.9
- 400 + ( ( 0.439 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1303.9


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
|           54 |        1 | 2024-08-06 | BLEED           | W   | 1.000      | 0.143        | 0.126 (0.018)    | -                | 0 (0.000) |    17.43 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           53 |        3 | 2024-08-06 | Metizport       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.42 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           52 |       21 | 2024-08-05 | Into the Breach | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.83 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           51 |       28 | 2024-08-05 | 9 Pandas        | L   | 1.000      | -            | -                | -                | -         |   -22.38 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           50 |       44 | 2024-08-04 | 3DMAX           | W   | 1.000      | 0.143        | 0.510 (0.073)    | 1.000 (0.143)    | -         |    23.59 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           49 |       74 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | -         |     2.48 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |      121 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.314 (0.045)    | -                | -         |    12.96 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      212 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | -         |    24.25 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      552 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.447 (0.149)    | -         |     3.00 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      572 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.09 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      587 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.66 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      648 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.523 (0.174)    | -         |     5.11 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      656 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      771 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.10 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      819 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.502 (0.186)    | -         |     4.00 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      867 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -24.84 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      904 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.958 (0.343)    | -         |    13.69 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      905 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.502 (0.180)    | -         |     3.70 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      927 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | -                | 0.523 (0.194)    | -         |     4.82 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      929 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.45 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      952 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.54 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      960 | 2024-07-05 | kONO            | W   | 0.986      | 0.333        | 0.028 (0.009)    | 0.553 (0.182)    | -         |     3.19 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      970 | 2024-06-30 | Young Gods      | W   | 0.954      | -            | -                | -                | -         |     1.36 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      992 | 2024-06-27 | Revenant        | W   | 0.932      | 0.333        | 0.027 (0.009)    | -                | -         |     2.48 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      996 | 2024-06-25 | Revenant        | W   | 0.919      | 0.333        | 0.027 (0.008)    | -                | -         |     2.38 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     1003 | 2024-06-23 | los kogutos     | W   | 0.906      | -            | -                | -                | -         |     0.24 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1070 | 2024-06-15 | Lilmix          | W   | 0.854      | -            | -                | -                | 1 (0.854) |     2.93 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1112 | 2024-06-14 | Lilmix          | W   | 0.847      | -            | -                | -                | 1 (0.847) |     2.87 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1154 | 2024-06-13 | Kappa Bar       | W   | 0.839      | -            | -                | -                | 1 (0.839) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1256 | 2024-06-09 | Alliance        | W   | 0.814      | -            | -                | -                | 1 (0.814) |     2.72 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1291 | 2024-06-09 | Preasy          | W   | 0.812      | -            | -                | -                | 1 (0.812) |     0.56 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1566 | 2024-06-04 | Enterprise      | L   | 0.779      | -            | -                | -                | -         |   -21.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1584 | 2024-06-03 | brazylijski luz | W   | 0.774      | -            | -                | -                | -         |     2.06 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1586 | 2024-06-03 | Zero Tenacity   | W   | 0.773      | 0.371        | 0.143 (0.041)    | 1.000 (0.286)    | -         |     8.20 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1676 | 2024-05-31 | UNiTY           | L   | 0.752      | -            | -                | -                | -         |   -20.25 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1781 | 2024-05-26 | Preasy          | W   | 0.719      | -            | -                | -                | -         |     1.47 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1885 | 2024-05-22 | Permitta        | W   | 0.692      | 0.371        | -                | 0.919 (0.236)    | -         |     2.38 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2193 | 2024-05-14 | kONO            | L   | 0.639      | -            | -                | -                | -         |   -18.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2209 | 2024-05-13 | UNiTY           | W   | 0.633      | -            | -                | -                | -         |     2.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2214 | 2024-05-13 | ECLOT           | W   | 0.632      | 0.333        | 0.061 (0.013)    | -                | -         |     7.40 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2225 | 2024-05-12 | Verdant         | W   | 0.628      | -            | -                | -                | -         |     2.51 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2238 | 2024-05-12 | Preasy          | L   | 0.625      | -            | -                | -                | -         |   -18.67 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2255 | 2024-05-11 | Lilmix          | W   | 0.621      | -            | -                | -                | 1 (0.621) |     1.74 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2270 | 2024-05-11 | Flying Angels   | W   | 0.619      | -            | -                | -                | 1 (0.619) |     0.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2286 | 2024-05-10 | FAVBET          | W   | 0.612      | -            | -                | -                | -         |     1.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2812 | 2024-04-18 | UNiTY           | W   | 0.466      | -            | -                | -                | -         |     2.02 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2876 | 2024-04-16 | Viperio         | W   | 0.453      | -            | -                | -                | -         |     0.35 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3122 | 2024-04-07 | Alliance        | W   | 0.394      | -            | -                | -                | -         |     0.99 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3130 | 2024-04-07 | Metizport       | L   | 0.392      | -            | -                | -                | -         |   -10.88 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3140 | 2024-04-06 | JANO            | W   | 0.387      | -            | -                | -                | -         |     0.37 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3739 | 2024-03-09 | Alliance        | L   | 0.200      | -            | -                | -                | -         |    -5.83 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3843 | 2024-03-05 | B8              | L   | 0.175      | -            | -                | -                | -         |    -4.27 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3848 | 2024-03-05 | Insilio         | W   | 0.175      | -            | -                | -                | -         |     0.50 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3854 | 2024-03-05 | Sashi           | W   | 0.174      | -            | -                | -                | -         |     1.58 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,050.93)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.954 | $662.00        | $631.60         |
| 2024-06-27 |      0.932 | $5,000.00      | $4,659.26       |
| 2024-06-15 |      0.854 | $11,615.00     | $9,914.16       |
| 2024-06-09 |      0.814 | $7,224.00      | $5,878.86       |
| 2024-06-06 |      0.792 | $1,000.00      | $791.85         |
| 2024-05-13 |      0.632 | $6,000.00      | $3,791.11       |
| 2024-05-11 |      0.621 | $4,170.00      | $2,589.65       |
| 2024-04-18 |      0.466 | $6,000.00      | $2,794.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
