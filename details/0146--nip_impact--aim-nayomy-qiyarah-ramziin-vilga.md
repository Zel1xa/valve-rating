### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  739.0<br />
<br />
Final Rank Value (739.0) = Starting Rank Value (704.2) + Head To Head Adjustments (34.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 704.2
- 400 + ( ( 0.148 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 704.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       38 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.136 (0.037)    | 0 (0.000) |    11.53 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       81 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |      109 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.136 (0.037)    | 0 (0.000) |    11.63 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      532 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.74 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      564 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.08 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1032 | 2024-06-16 | dream catchers fe | W   | 0.861      | 0.250        | 0.016 (0.003)    | 0.167 (0.036)    | 0 (0.000) |    13.38 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1775 | 2024-05-26 | Crescent fe       | L   | 0.722      | -            | -                | -                | -         |   -13.94 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1983 | 2024-05-19 | Imperial fe       | L   | 0.673      | -            | -                | -                | -         |    -3.11 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     2006 | 2024-05-18 | Astralis W        | W   | 0.668      | 0.281        | 0.002 (0.000)    | 0.060 (0.011)    | 0 (0.000) |     8.78 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2549 | 2024-04-27 | Imperial fe       | L   | 0.528      | -            | -                | -                | -         |    -2.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2554 | 2024-04-27 | ENCE Athena       | W   | 0.527      | 0.252        | 0.002 (0.000)    | 0.033 (0.004)    | 0 (0.000) |     6.29 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2741 | 2024-04-19 | BIG EQUIPA        | L   | 0.475      | -            | -                | -                | -         |    -6.52 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2894 | 2024-04-15 | NAVI Javelins     | L   | 0.448      | -            | -                | -                | -         |    -5.33 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2907 | 2024-04-14 | Imperial fe       | L   | 0.442      | -            | -                | -                | -         |    -2.06 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2920 | 2024-04-13 | Astralis W        | W   | 0.435      | -            | -                | -                | 0 (0.000) |     4.72 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2961 | 2024-04-11 | Let Her Cook      | W   | 0.422      | 0.303        | 0.060 (0.008)    | 0.137 (0.018)    | 0 (0.000) |     9.80 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     3005 | 2024-04-10 | Astralis W        | L   | 0.415      | -            | -                | -                | -         |    -7.71 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3066 | 2024-04-09 | NAVI Javelins     | W   | 0.408      | 0.303        | 0.026 (0.003)    | 0.179 (0.022)    | 0 (0.000) |     8.19 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3125 | 2024-04-07 | Imperial fe       | L   | 0.394      | -            | -                | -                | -         |    -1.80 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3130 | 2024-04-07 | Fearless Cheetahs | W   | 0.393      | 0.262        | 0.003 (0.000)    | 0.062 (0.006)    | 0 (0.000) |     5.88 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3143 | 2024-04-06 | Astralis W        | W   | 0.387      | 0.262        | 0.002 (0.000)    | 0.060 (0.006)    | -         |     5.29 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3234 | 2024-04-03 | Astralis W        | W   | 0.368      | -            | -                | -                | -         |     4.33 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3482 | 2024-03-20 | ENCE Athena       | W   | 0.275      | 0.331        | -                | 0.033 (0.003)    | -         |     3.62 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3779 | 2024-03-07 | Imperial fe       | L   | 0.189      | -            | -                | -                | -         |    -0.82 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,705.05)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $750.00        | $646.06         |
| 2024-05-26 |      0.722 | $250.00        | $180.42         |
| 2024-04-27 |      0.528 | $321.00        | $169.40         |
| 2024-04-21 |      0.488 | $1,250.00      | $610.59         |
| 2024-04-07 |      0.394 | $250.00        | $98.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />