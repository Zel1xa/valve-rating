### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  726.7<br />
<br />
Final Rank Value (726.7) = Starting Rank Value (701.6) + Head To Head Adjustments (25.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.6
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 701.6


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
|           23 |       10 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.12 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       33 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.145 (0.040)    | 0 (0.000) |    11.58 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      438 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.77 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      469 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.09 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      924 | 2024-06-16 | dream catchers fe | W   | 0.880      | 0.250        | 0.016 (0.003)    | 0.178 (0.039)    | 0 (0.000) |    13.63 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1640 | 2024-05-26 | Crescent fe       | L   | 0.740      | -            | -                | -                | -         |   -14.25 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1846 | 2024-05-19 | Imperial fe       | L   | 0.692      | -            | -                | -                | -         |    -3.14 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1869 | 2024-05-18 | Astralis W        | W   | 0.686      | 0.281        | 0.002 (0.000)    | 0.067 (0.013)    | 0 (0.000) |     9.07 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2411 | 2024-04-27 | Imperial fe       | L   | 0.546      | -            | -                | -                | -         |    -2.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2416 | 2024-04-27 | ENCE Athena       | W   | 0.546      | 0.252        | 0.002 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     6.54 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2602 | 2024-04-19 | BIG EQUIPA        | L   | 0.494      | -            | -                | -                | -         |    -6.72 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2755 | 2024-04-15 | NAVI Javelins     | L   | 0.467      | -            | -                | -                | -         |    -5.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2768 | 2024-04-14 | Imperial fe       | L   | 0.460      | -            | -                | -                | -         |    -2.12 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2781 | 2024-04-13 | Astralis W        | W   | 0.453      | 0.303        | -                | 0.022 (0.003)    | 0 (0.000) |     4.95 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2822 | 2024-04-11 | Let Her Cook      | W   | 0.440      | 0.303        | 0.060 (0.008)    | 0.150 (0.020)    | 0 (0.000) |    10.22 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2866 | 2024-04-10 | Astralis W        | L   | 0.434      | -            | -                | -                | -         |    -8.02 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     2927 | 2024-04-09 | NAVI Javelins     | W   | 0.426      | 0.303        | 0.027 (0.003)    | 0.196 (0.025)    | 0 (0.000) |     8.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     2986 | 2024-04-07 | Imperial fe       | L   | 0.413      | -            | -                | -                | -         |    -1.85 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     2991 | 2024-04-07 | Fearless Cheetahs | W   | 0.412      | 0.262        | 0.003 (0.000)    | 0.068 (0.007)    | 0 (0.000) |     6.21 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3004 | 2024-04-06 | Astralis W        | W   | 0.405      | 0.262        | 0.002 (0.000)    | 0.067 (0.007)    | 0 (0.000) |     5.59 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3095 | 2024-04-03 | Astralis W        | W   | 0.387      | -            | -                | -                | -         |     4.59 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3338 | 2024-03-20 | ENCE Athena       | W   | 0.294      | 0.331        | 0.002 (0.000)    | 0.038 (0.004)    | -         |     3.90 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3632 | 2024-03-07 | Imperial fe       | L   | 0.207      | -            | -                | -                | -         |    -0.88 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,756.90)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.880 | $750.00        | $659.84         |
| 2024-05-26 |      0.740 | $250.00        | $185.02         |
| 2024-04-27 |      0.546 | $321.00        | $175.30         |
| 2024-04-21 |      0.507 | $1,250.00      | $633.56         |
| 2024-04-07 |      0.413 | $250.00        | $103.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
