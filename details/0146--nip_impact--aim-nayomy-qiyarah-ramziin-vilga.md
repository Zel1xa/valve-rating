### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  725.8<br />
<br />
Final Rank Value (725.8) = Starting Rank Value (700.8) + Head To Head Adjustments (25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.8
- 400 + ( ( 0.147 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 700.8


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
|           23 |       12 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.14 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       40 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.140 (0.038)    | 0 (0.000) |    11.60 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      461 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.75 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      493 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.11 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      960 | 2024-06-16 | dream catchers fe | W   | 0.878      | 0.250        | 0.016 (0.003)    | 0.172 (0.038)    | 0 (0.000) |    13.61 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1703 | 2024-05-26 | Crescent fe       | L   | 0.738      | -            | -                | -                | -         |   -14.21 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1911 | 2024-05-19 | Imperial fe       | L   | 0.690      | -            | -                | -                | -         |    -3.15 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1934 | 2024-05-18 | Astralis W        | W   | 0.684      | 0.281        | 0.002 (0.000)    | 0.064 (0.012)    | 0 (0.000) |     9.05 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2477 | 2024-04-27 | Imperial fe       | L   | 0.544      | -            | -                | -                | -         |    -2.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2482 | 2024-04-27 | ENCE Athena       | W   | 0.544      | 0.252        | 0.002 (0.000)    | 0.036 (0.005)    | 0 (0.000) |     6.53 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2668 | 2024-04-19 | BIG EQUIPA        | L   | 0.492      | -            | -                | -                | -         |    -6.70 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2821 | 2024-04-15 | NAVI Javelins     | L   | 0.465      | -            | -                | -                | -         |    -5.48 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2834 | 2024-04-14 | Imperial fe       | L   | 0.458      | -            | -                | -                | -         |    -2.12 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2847 | 2024-04-13 | Astralis W        | W   | 0.452      | 0.303        | -                | 0.021 (0.003)    | 0 (0.000) |     4.94 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2888 | 2024-04-11 | Let Her Cook      | W   | 0.438      | 0.303        | 0.060 (0.008)    | 0.145 (0.019)    | 0 (0.000) |    10.18 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2932 | 2024-04-10 | Astralis W        | L   | 0.432      | -            | -                | -                | -         |    -7.99 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     2993 | 2024-04-09 | NAVI Javelins     | W   | 0.424      | 0.303        | 0.026 (0.003)    | 0.190 (0.024)    | 0 (0.000) |     8.57 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3052 | 2024-04-07 | Imperial fe       | L   | 0.411      | -            | -                | -                | -         |    -1.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3057 | 2024-04-07 | Fearless Cheetahs | W   | 0.410      | 0.262        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     6.19 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3070 | 2024-04-06 | Astralis W        | W   | 0.404      | 0.262        | 0.002 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     5.57 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3161 | 2024-04-03 | Astralis W        | W   | 0.385      | -            | -                | -                | -         |     4.57 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3409 | 2024-03-20 | ENCE Athena       | W   | 0.292      | 0.331        | 0.002 (0.000)    | 0.036 (0.003)    | -         |     3.88 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3705 | 2024-03-07 | Imperial fe       | L   | 0.205      | -            | -                | -                | -         |    -0.88 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,752.07)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $750.00        | $658.56         |
| 2024-05-26 |      0.738 | $250.00        | $184.59         |
| 2024-04-27 |      0.544 | $321.00        | $174.75         |
| 2024-04-21 |      0.505 | $1,250.00      | $631.42         |
| 2024-04-07 |      0.411 | $250.00        | $102.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
