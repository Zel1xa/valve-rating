### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, chawzyyy, draken, Ro1f, spooke<br />
Global Rank: [29](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1229.1<br />
<br />
Final Rank Value (1229.1) = Starting Rank Value (1292.6) + Head To Head Adjustments (-63.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.387[<sup>2</sup>](#table1)
- Opponent Network: 0.208[<sup>2</sup>](#table1)
- LAN Wins: 0.629[<sup>2</sup>](#table1)

The average of these factors is 0.437<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1292.6
- 400 + ( ( 0.437 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1292.6


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
|           49 |       17 | 2024-08-03 | Cloud9          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.55 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           48 |       65 | 2024-08-02 | Nemiga          | W   | 1.000      | 0.143        | 0.317 (0.045)    | -                | 0 (0.000) |    12.82 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           47 |      155 | 2024-07-31 | fnatic          | W   | 1.000      | 0.143        | 0.371 (0.053)    | -                | 0 (0.000) |    24.44 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           46 |      494 | 2024-07-20 | Nexus           | W   | 1.000      | 0.333        | -                | 0.465 (0.155)    | -         |     3.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           45 |      514 | 2024-07-20 | Illuminar       | L   | 1.000      | -            | -                | -                | -         |   -26.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           44 |      529 | 2024-07-19 | Preasy          | W   | 1.000      | -            | -                | -                | -         |     2.67 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           43 |      590 | 2024-07-18 | 9INE            | W   | 1.000      | 0.333        | -                | 0.537 (0.179)    | -         |     5.23 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           42 |      598 | 2024-07-18 | Passion UA      | L   | 1.000      | -            | -                | -                | -         |   -23.48 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           41 |      713 | 2024-07-16 | Young Ninjas    | W   | 1.000      | -            | -                | -                | -         |     2.13 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           40 |      761 | 2024-07-15 | Endpoint        | W   | 1.000      | 0.371        | -                | 0.522 (0.194)    | -         |     4.04 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           39 |      809 | 2024-07-12 | TSM             | L   | 1.000      | -            | -                | -                | -         |   -25.00 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           38 |      846 | 2024-07-10 | Sashi           | W   | 1.000      | 0.358        | 0.184 (0.066)    | 0.962 (0.344)    | -         |    13.98 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           37 |      847 | 2024-07-10 | Endpoint        | W   | 1.000      | 0.358        | -                | 0.522 (0.187)    | -         |     3.74 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           36 |      869 | 2024-07-09 | 9INE            | W   | 1.000      | 0.371        | 0.022 (0.008)    | 0.537 (0.199)    | -         |     4.95 | bobeksde, chawzyyy, Ro1f, SHiNE, spooke   |
|           35 |      871 | 2024-07-09 | Revenant        | L   | 1.000      | -            | -                | -                | -         |   -28.37 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           34 |      894 | 2024-07-07 | lajtbitexe      | W   | 1.000      | -            | -                | -                | -         |     1.60 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           33 |      902 | 2024-07-05 | kONO            | W   | 1.000      | 0.333        | 0.028 (0.009)    | 0.536 (0.179)    | -         |     3.33 | bobeksde, chawzyyy, draken, Ro1f, spooke  |
|           32 |      912 | 2024-06-30 | Young Gods      | W   | 0.968      | -            | -                | -                | -         |     1.44 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      934 | 2024-06-27 | Revenant        | W   | 0.945      | 0.333        | 0.027 (0.009)    | -                | -         |     2.59 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      938 | 2024-06-25 | Revenant        | W   | 0.933      | 0.333        | 0.027 (0.008)    | -                | -         |     2.48 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      945 | 2024-06-23 | los kogutos     | W   | 0.919      | -            | -                | -                | -         |     0.26 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           28 |     1012 | 2024-06-15 | Lilmix          | W   | 0.867      | 0.377        | 0.023 (0.007)    | -                | 1 (0.867) |     3.09 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     1054 | 2024-06-14 | Lilmix          | W   | 0.860      | -            | -                | -                | 1 (0.860) |     3.03 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|           26 |     1096 | 2024-06-13 | Kappa Bar       | W   | 0.852      | -            | -                | -                | 1 (0.852) |     0.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1198 | 2024-06-09 | Alliance        | W   | 0.827      | -            | -                | -                | 1 (0.827) |     2.89 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1233 | 2024-06-09 | Preasy          | W   | 0.825      | -            | -                | -                | 1 (0.825) |     2.00 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1508 | 2024-06-04 | Enterprise      | L   | 0.792      | -            | -                | -                | -         |   -21.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1526 | 2024-06-03 | brazylijski luz | W   | 0.787      | -            | -                | -                | -         |     2.21 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1528 | 2024-06-03 | Zero Tenacity   | W   | 0.786      | 0.371        | 0.137 (0.040)    | 1.000 (0.291)    | -         |     8.63 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     1618 | 2024-05-31 | UNiTY           | L   | 0.765      | -            | -                | -                | -         |   -20.49 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     1723 | 2024-05-26 | Preasy          | W   | 0.733      | -            | -                | -                | -         |     1.60 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     1827 | 2024-05-22 | Permitta        | W   | 0.705      | 0.371        | -                | 0.876 (0.229)    | -         |     2.44 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           17 |     2135 | 2024-05-14 | kONO            | L   | 0.652      | -            | -                | -                | -         |   -18.84 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     2151 | 2024-05-13 | UNiTY           | W   | 0.647      | -            | -                | -                | -         |     2.92 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     2156 | 2024-05-13 | ECLOT           | W   | 0.645      | 0.333        | 0.062 (0.013)    | 0.559 (0.120)    | -         |     7.75 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     2167 | 2024-05-12 | Verdant         | W   | 0.642      | -            | -                | -                | -         |     2.68 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     2180 | 2024-05-12 | Preasy          | L   | 0.639      | -            | -                | -                | -         |   -18.97 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2197 | 2024-05-11 | Lilmix          | W   | 0.635      | -            | -                | -                | 1 (0.635) |     1.87 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2212 | 2024-05-11 | Flying Angels   | W   | 0.633      | -            | -                | -                | 1 (0.633) |     0.29 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2228 | 2024-05-10 | FAVBET          | W   | 0.625      | -            | -                | -                | -         |     1.18 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2754 | 2024-04-18 | UNiTY           | W   | 0.479      | -            | -                | -                | -         |     2.16 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2818 | 2024-04-16 | Viperio         | W   | 0.467      | -            | -                | -                | -         |     0.39 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     3064 | 2024-04-07 | Alliance        | W   | 0.408      | -            | -                | -                | -         |     1.09 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            6 |     3072 | 2024-04-07 | Metizport       | L   | 0.406      | -            | -                | -                | -         |   -11.15 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            5 |     3082 | 2024-04-06 | JANO            | W   | 0.400      | -            | -                | -                | -         |     0.40 | bobeksde, chawzyyy, draken, Lekr0, spooke |
|            4 |     3681 | 2024-03-09 | Alliance        | L   | 0.214      | -            | -                | -                | -         |    -6.19 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3785 | 2024-03-05 | B8              | L   | 0.188      | -            | -                | -                | -         |    -4.54 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3790 | 2024-03-05 | Insilio         | W   | 0.188      | -            | -                | -                | -         |     0.57 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3796 | 2024-03-05 | Sashi           | W   | 0.188      | -            | -                | -                | -         |     1.78 | chawzyyy, draken, Lekr0, Ro1f, spooke     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,615.23)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-09 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-30 |      0.968 | $662.00        | $640.56         |
| 2024-06-27 |      0.945 | $5,000.00      | $4,726.97       |
| 2024-06-15 |      0.867 | $11,615.00     | $10,071.44      |
| 2024-06-09 |      0.827 | $7,224.00      | $5,976.69       |
| 2024-06-06 |      0.805 | $1,000.00      | $805.39         |
| 2024-05-13 |      0.645 | $6,000.00      | $3,872.36       |
| 2024-05-11 |      0.635 | $4,170.00      | $2,646.12       |
| 2024-04-18 |      0.479 | $6,000.00      | $2,875.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
