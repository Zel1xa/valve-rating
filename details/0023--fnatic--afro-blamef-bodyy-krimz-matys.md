### Roster Details<br />
Team Name: fnatic<br />
Roster: afro, blameF, bodyy, KRIMZ, MATYS<br />
Global Rank: [23](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1273.4<br />
<br />
Final Rank Value (1273.4) = Starting Rank Value (1324.2) + Head To Head Adjustments (-50.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.653[<sup>1</sup>](#table2)
- Bounty Collected: 0.522[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.406[<sup>2</sup>](#table1)

The average of these factors is 0.477<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1324.2
- 400 + ( ( 0.477 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1324.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |      278 | 2024-08-29 | ECSTATIC          | L   | 1.000      | -            | -                | -                | -         |   -29.49 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           53 |      371 | 2024-08-27 | HEROIC            | L   | 1.000      | -            | -                | -                | -         |   -12.68 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           52 |      382 | 2024-08-27 | Cloud9            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.20 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           51 |      443 | 2024-08-26 | OG                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.72 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           50 |      458 | 2024-08-26 | 3DMAX             | L   | 1.000      | -            | -                | -                | -         |   -11.08 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           49 |      809 | 2024-08-15 | QUAZAR            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           48 |      814 | 2024-08-15 | Gaimin Gladiators | W   | 1.000      | -            | -                | -                | -         |     2.53 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           47 |      825 | 2024-08-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     3.25 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           46 |     1196 | 2024-08-03 | 3DMAX             | L   | 0.962      | -            | -                | -                | -         |    -7.26 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           45 |     1247 | 2024-08-02 | Nemiga            | W   | 0.953      | -            | -                | -                | -         |     8.05 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           44 |     1277 | 2024-08-01 | G2 Ares           | W   | 0.947      | -            | -                | -                | -         |     0.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           43 |     1343 | 2024-07-31 | Johnny Speeds     | L   | 0.939      | -            | -                | -                | -         |   -22.12 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           42 |     1434 | 2024-07-28 | Sangal            | L   | 0.921      | -            | -                | -                | -         |   -15.52 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           41 |     1446 | 2024-07-28 | SAW               | W   | 0.920      | 0.435        | 0.330 (0.132)    | 0.747 (0.299)    | -         |    16.92 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           40 |     1462 | 2024-07-27 | MOUZ NXT          | W   | 0.914      | 0.435        | -                | 0.813 (0.323)    | -         |     4.86 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           39 |     1496 | 2024-07-26 | Sampi             | W   | 0.906      | 0.435        | -                | 1.000 (0.394)    | -         |     2.25 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           38 |     1626 | 2024-07-22 | Passion UA        | W   | 0.881      | 0.500        | 0.164 (0.072)    | 1.000 (0.440)    | -         |     6.18 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           37 |     1657 | 2024-07-21 | MOUZ NXT          | W   | 0.873      | 0.500        | 0.111 (0.048)    | 0.813 (0.355)    | -         |     4.81 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           36 |     1701 | 2024-07-20 | Sangal            | W   | 0.866      | 0.500        | 0.248 (0.107)    | 0.878 (0.380)    | -         |    13.45 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           35 |     1722 | 2024-07-19 | CYBERSHOKE        | W   | 0.861      | 0.500        | -                | 0.702 (0.302)    | -         |     3.05 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           34 |     1774 | 2024-07-18 | Zero Tenacity     | L   | 0.854      | -            | -                | -                | -         |   -21.01 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           33 |     1901 | 2024-07-16 | CYBERSHOKE        | W   | 0.841      | 0.500        | -                | 0.702 (0.295)    | -         |     2.68 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           32 |     2154 | 2024-06-16 | 9z                | L   | 0.643      | -            | -                | -                | -         |    -6.94 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           31 |     2158 | 2024-06-16 | Ninjas in Pyjamas | W   | 0.642      | 0.548        | 0.232 (0.082)    | -                | 1 (0.642) |    13.82 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           30 |     2182 | 2024-06-15 | RED Canids        | W   | 0.636      | 0.548        | -                | 0.612 (0.214)    | 1 (0.636) |     3.95 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           29 |     2196 | 2024-06-15 | Imperial          | W   | 0.634      | 0.548        | 0.150 (0.052)    | -                | 1 (0.634) |     5.63 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           28 |     2221 | 2024-06-14 | RED Canids        | L   | 0.629      | -            | -                | -                | -         |   -15.93 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           27 |     2504 | 2024-06-07 | Ninjas in Pyjamas | L   | 0.581      | -            | -                | -                | -         |    -6.75 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           26 |     2560 | 2024-06-06 | BIG               | W   | 0.575      | 0.715        | 0.146 (0.060)    | -                | 1 (0.575) |     6.53 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           25 |     2586 | 2024-06-06 | FURIA             | L   | 0.574      | -            | -                | -                | -         |    -3.57 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           24 |     2601 | 2024-06-06 | Complexity        | W   | 0.572      | 0.715        | 0.337 (0.138)    | -                | 1 (0.572) |    14.22 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           23 |     2631 | 2024-06-05 | Eternal Fire      | W   | 0.568      | 0.715        | 0.972 (0.395)    | 0.700 (0.285)    | 1 (0.568) |    17.05 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           22 |     2647 | 2024-06-05 | BetBoom           | L   | 0.567      | -            | -                | -                | -         |   -10.37 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           21 |     2737 | 2024-06-02 | DMS               | L   | 0.546      | -            | -                | -                | -         |   -15.38 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           20 |     2802 | 2024-05-31 | SAW               | W   | 0.534      | -            | -                | -                | -         |    12.69 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           19 |     2803 | 2024-05-31 | Sangal            | W   | 0.533      | -            | -                | -                | -         |     7.60 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           18 |     3139 | 2024-05-18 | ENCE              | L   | 0.447      | -            | -                | -                | -         |    -8.68 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           17 |     3147 | 2024-05-18 | GamerLegion       | L   | 0.446      | -            | -                | -                | -         |   -10.98 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           16 |     3173 | 2024-05-17 | ENCE              | W   | 0.440      | -            | -                | -                | -         |     5.15 | afro, blameF, bodyy, KRIMZ, MATYS  |
|           15 |     3539 | 2024-05-03 | 9 Pandas          | L   | 0.348      | -            | -                | -                | -         |    -9.25 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           14 |     3567 | 2024-05-02 | Sashi             | L   | 0.341      | -            | -                | -                | -         |    -8.29 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           13 |     3595 | 2024-05-01 | AMKAL             | W   | 0.334      | -            | -                | -                | -         |     2.38 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           12 |     3608 | 2024-05-01 | PARIVISION        | W   | 0.332      | -            | -                | -                | -         |     2.17 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           11 |     3631 | 2024-04-30 | Nexus             | W   | 0.325      | -            | -                | -                | -         |     0.52 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|           10 |     3690 | 2024-04-27 | Virtus.pro        | L   | 0.306      | -            | -                | -                | -         |    -2.45 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            9 |     3731 | 2024-04-25 | Eternal Fire      | L   | 0.295      | -            | -                | -                | -         |    -0.44 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            8 |     3755 | 2024-04-24 | 3DMAX             | L   | 0.287      | -            | -                | -                | -         |    -0.93 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            7 |     3779 | 2024-04-23 | Virtus.pro        | W   | 0.280      | 0.889        | 0.520 (0.129)    | -                | 1 (0.280) |     6.63 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            6 |     3930 | 2024-04-18 | KOI               | L   | 0.247      | -            | -                | -                | -         |    -6.92 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            5 |     4184 | 2024-04-09 | Apeks             | L   | 0.188      | -            | -                | -                | -         |    -5.68 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            4 |     4218 | 2024-04-08 | Apeks             | W   | 0.181      | -            | -                | -                | -         |     0.23 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            3 |     4224 | 2024-04-08 | KOI               | W   | 0.180      | -            | -                | -                | -         |     0.62 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            2 |     4557 | 2024-03-23 | BetBoom           | L   | 0.073      | -            | -                | -                | -         |    -1.46 | afro, bodyy, KRIMZ, kyuubii, MATYS |
|            1 |     4593 | 2024-03-21 | 3DMAX             | W   | 0.060      | -            | -                | -                | -         |     1.72 | afro, bodyy, KRIMZ, kyuubii, MATYS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($89,155.97)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      0.921 | $10,000.00     | $9,209.72       |
| 2024-07-22 |      0.881 | $50,000.00     | $44,027.78      |
| 2024-06-16 |      0.643 | $30,000.00     | $19,288.89      |
| 2024-06-09 |      0.594 | $20,000.00     | $11,877.78      |
| 2024-05-12 |      0.407 | $7,000.00      | $2,850.56       |
| 2024-05-04 |      0.354 | $2,000.00      | $708.33         |
| 2024-05-02 |      0.341 | $3,500.00      | $1,192.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
