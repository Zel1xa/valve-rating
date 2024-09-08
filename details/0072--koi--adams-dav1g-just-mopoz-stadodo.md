### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  921.5<br />
<br />
Final Rank Value (921.5) = Starting Rank Value (951.9) + Head To Head Adjustments (-30.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.440[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.131[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 951.9
- 400 + ( ( 0.285 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 951.9


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
|           44 |       36 | 2024-09-06 | Wildcard          | L   | 1.000      | -            | -                | -                | -         |    -6.93 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |       91 | 2024-09-05 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -0.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |      142 | 2024-09-03 | G2                | L   | 1.000      | -            | -                | -                | -         |    -0.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |      547 | 2024-08-23 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -10.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |      558 | 2024-08-23 | UNiTY             | L   | 1.000      | -            | -                | -                | -         |   -16.01 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |      589 | 2024-08-22 | SINNERS           | L   | 1.000      | -            | -                | -                | -         |    -9.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |      626 | 2024-08-21 | Monte             | W   | 1.000      | 0.143        | 0.023 (0.003)    | 0.697 (0.100)    | 0 (0.000) |    18.05 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |      668 | 2024-08-21 | ENCE              | W   | 1.000      | 0.143        | 0.130 (0.019)    | 0.330 (0.047)    | 0 (0.000) |    24.71 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |      712 | 2024-08-19 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -12.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |      721 | 2024-08-19 | Gaimin Gladiators | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.495 (0.071)    | 0 (0.000) |    13.21 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |      821 | 2024-08-15 | HOTU              | L   | 1.000      | -            | -                | -                | -         |   -23.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |      869 | 2024-08-13 | B8                | L   | 1.000      | -            | -                | -                | -         |   -10.24 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |      921 | 2024-08-12 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |    -9.60 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     1111 | 2024-08-06 | Sashi             | L   | 0.981      | -            | -                | -                | -         |   -11.30 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     1325 | 2024-07-31 | Zero Tenacity     | L   | 0.941      | -            | -                | -                | -         |    -9.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     1487 | 2024-07-26 | EYEBALLERS        | W   | 0.907      | 0.500        | -                | 0.407 (0.185)    | 0 (0.000) |     4.72 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     1762 | 2024-07-18 | Monte             | L   | 0.855      | -            | -                | -                | -         |   -15.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     1898 | 2024-07-16 | Insilio           | W   | 0.841      | 0.500        | 0.023 (0.010)    | 0.654 (0.275)    | 0 (0.000) |    11.16 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     2165 | 2024-06-16 | 9z                | L   | 0.641      | -            | -                | -                | -         |    -1.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     2215 | 2024-06-14 | RED Canids        | W   | 0.630      | 0.548        | 0.049 (0.017)    | 0.612 (0.212)    | 1 (0.630) |    12.18 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     2220 | 2024-06-14 | Imperial          | W   | 0.629      | 0.548        | 0.150 (0.052)    | 0.606 (0.209)    | 1 (0.629) |    14.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     2386 | 2024-06-09 | Sangal            | L   | 0.594      | -            | -                | -                | -         |    -2.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     2574 | 2024-06-06 | SINNERS           | W   | 0.574      | 0.500        | 0.081 (0.023)    | 1.000 (0.287)    | 0 (0.000) |    11.32 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     2635 | 2024-06-05 | 3DMAX             | W   | 0.568      | 0.500        | 0.509 (0.144)    | 0.951 (0.270)    | 0 (0.000) |    17.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     2764 | 2024-06-01 | ENCE              | L   | 0.541      | -            | -                | -                | -         |    -3.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     2770 | 2024-06-01 | Zero Tenacity     | L   | 0.540      | -            | -                | -                | -         |    -5.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     3440 | 2024-05-09 | B8                | L   | 0.386      | -            | -                | -                | -         |    -4.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     3603 | 2024-05-01 | Zero Tenacity     | L   | 0.333      | -            | -                | -                | -         |    -3.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     3919 | 2024-04-18 | ex-Guild Eagles   | L   | 0.248      | -            | -                | -                | -         |    -6.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     3930 | 2024-04-18 | fnatic            | W   | 0.247      | 0.143        | 0.294 (0.010)    | -                | 0 (0.000) |     6.92 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     4004 | 2024-04-16 | BLEED             | L   | 0.234      | -            | -                | -                | -         |    -4.71 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     4135 | 2024-04-10 | RUSH B            | W   | 0.195      | -            | -                | -                | -         |     2.22 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     4190 | 2024-04-09 | Aurora            | W   | 0.188      | 0.500        | 0.290 (0.027)    | 0.603 (0.057)    | -         |     5.52 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     4196 | 2024-04-09 | Apeks             | L   | 0.187      | -            | -                | -                | -         |    -4.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     4223 | 2024-04-08 | GUN5              | W   | 0.181      | -            | -                | -                | -         |     0.25 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     4224 | 2024-04-08 | fnatic            | L   | 0.180      | -            | -                | -                | -         |    -0.62 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     4327 | 2024-04-04 | NOM               | W   | 0.154      | -            | -                | -                | -         |     0.44 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     4361 | 2024-04-03 | 9INE              | W   | 0.148      | -            | -                | -                | -         |     0.37 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     4399 | 2024-04-02 | TSM               | W   | 0.141      | -            | -                | -                | -         |     0.65 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     4466 | 2024-03-28 | EYEBALLERS        | L   | 0.107      | -            | -                | -                | -         |    -2.34 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     4638 | 2024-03-18 | FURIA             | L   | 0.041      | -            | -                | -                | -         |    -0.03 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     4653 | 2024-03-17 | ENCE              | L   | 0.035      | -            | -                | -                | -         |    -0.19 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     4669 | 2024-03-17 | SAW               | L   | 0.034      | -            | -                | -                | -         |    -0.04 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     4761 | 2024-03-13 | Sangal            | W   | 0.008      | -            | -                | -                | -         |     0.23 | adamS, dav1g, JUST, mopoz, stadodo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,175.74)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-09-06 |      1.000 | $500.00        | $500.00         |
| 2024-06-16 |      0.643 | $7,000.00      | $4,500.74       |
| 2024-06-09 |      0.594 | $12,000.00     | $7,129.17       |
| 2024-03-20 |      0.055 | $10,000.00     | $545.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
