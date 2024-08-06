### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [145](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  739.0<br />
<br />
Final Rank Value (739.0) = Starting Rank Value (704.2) + Head To Head Adjustments (34.8)<br />

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
|           24 |       40 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.136 (0.037)    | 0 (0.000) |    11.53 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       81 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |      107 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.136 (0.037)    | 0 (0.000) |    11.63 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      530 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.74 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      562 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.09 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1030 | 2024-06-16 | dream catchers fe | W   | 0.861      | 0.250        | 0.016 (0.003)    | 0.167 (0.036)    | 0 (0.000) |    13.37 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1773 | 2024-05-26 | Crescent fe       | L   | 0.721      | -            | -                | -                | -         |   -13.93 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1981 | 2024-05-19 | Imperial fe       | L   | 0.673      | -            | -                | -                | -         |    -3.10 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     2004 | 2024-05-18 | Astralis W        | W   | 0.667      | 0.281        | 0.002 (0.000)    | 0.060 (0.011)    | 0 (0.000) |     8.78 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2547 | 2024-04-27 | Imperial fe       | L   | 0.527      | -            | -                | -                | -         |    -2.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2552 | 2024-04-27 | ENCE Athena       | W   | 0.527      | 0.252        | 0.002 (0.000)    | 0.033 (0.004)    | 0 (0.000) |     6.29 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2739 | 2024-04-19 | BIG EQUIPA        | L   | 0.474      | -            | -                | -                | -         |    -6.51 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2892 | 2024-04-15 | NAVI Javelins     | L   | 0.448      | -            | -                | -                | -         |    -5.32 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2905 | 2024-04-14 | Imperial fe       | L   | 0.441      | -            | -                | -                | -         |    -2.06 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2918 | 2024-04-13 | Astralis W        | W   | 0.434      | -            | -                | -                | 0 (0.000) |     4.72 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2959 | 2024-04-11 | Let Her Cook      | W   | 0.421      | 0.303        | 0.060 (0.008)    | 0.137 (0.017)    | 0 (0.000) |     9.79 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     3003 | 2024-04-10 | Astralis W        | L   | 0.414      | -            | -                | -                | -         |    -7.70 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3064 | 2024-04-09 | NAVI Javelins     | W   | 0.407      | 0.303        | 0.026 (0.003)    | 0.179 (0.022)    | 0 (0.000) |     8.17 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3123 | 2024-04-07 | Imperial fe       | L   | 0.394      | -            | -                | -                | -         |    -1.80 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3128 | 2024-04-07 | Fearless Cheetahs | W   | 0.393      | 0.262        | 0.003 (0.000)    | 0.062 (0.006)    | 0 (0.000) |     5.87 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3141 | 2024-04-06 | Astralis W        | W   | 0.386      | 0.262        | 0.002 (0.000)    | 0.060 (0.006)    | -         |     5.28 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3232 | 2024-04-03 | Astralis W        | W   | 0.368      | -            | -                | -                | -         |     4.32 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3480 | 2024-03-20 | ENCE Athena       | W   | 0.275      | 0.331        | -                | 0.033 (0.003)    | -         |     3.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3777 | 2024-03-07 | Imperial fe       | L   | 0.188      | -            | -                | -                | -         |    -0.82 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,703.22)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.861 | $750.00        | $645.57         |
| 2024-05-26 |      0.721 | $250.00        | $180.26         |
| 2024-04-27 |      0.527 | $321.00        | $169.19         |
| 2024-04-21 |      0.488 | $1,250.00      | $609.78         |
| 2024-04-07 |      0.394 | $250.00        | $98.41          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
