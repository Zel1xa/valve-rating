### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  721.4<br />
<br />
Final Rank Value (721.4) = Starting Rank Value (701.8) + Head To Head Adjustments (19.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.8
- 400 + ( ( 0.147 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 701.8


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
|           21 |      378 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.71 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      411 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.05 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      892 | 2024-06-16 | dream catchers fe | W   | 0.894      | 0.250        | 0.016 (0.004)    | 0.170 (0.038)    | 0 (0.000) |    13.80 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1644 | 2024-05-26 | Crescent fe       | L   | 0.755      | -            | -                | -                | -         |   -14.54 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1877 | 2024-05-19 | Imperial fe       | L   | 0.706      | -            | -                | -                | -         |    -3.13 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1900 | 2024-05-18 | ex-GUILD fe       | W   | 0.701      | 0.281        | 0.003 (0.001)    | 0.066 (0.013)    | 0 (0.000) |     9.28 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2458 | 2024-04-27 | Imperial fe       | L   | 0.561      | -            | -                | -                | -         |    -2.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2464 | 2024-04-27 | ENCE Athena       | W   | 0.560      | 0.252        | 0.002 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     6.72 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2657 | 2024-04-19 | BIG EQUIPA        | L   | 0.508      | -            | -                | -                | -         |    -6.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2813 | 2024-04-15 | NAVI Javelins     | L   | 0.481      | -            | -                | -                | -         |    -5.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2826 | 2024-04-14 | Imperial fe       | L   | 0.475      | -            | -                | -                | -         |    -2.13 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2839 | 2024-04-13 | Astralis W        | W   | 0.468      | 0.303        | 0.001 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     5.12 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2881 | 2024-04-11 | Let Her Cook      | W   | 0.455      | 0.303        | 0.061 (0.008)    | 0.147 (0.020)    | 0 (0.000) |    10.65 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2925 | 2024-04-10 | ex-GUILD fe       | L   | 0.448      | -            | -                | -                | -         |    -8.27 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     2986 | 2024-04-09 | NAVI Javelins     | W   | 0.441      | 0.303        | 0.027 (0.004)    | 0.211 (0.028)    | 0 (0.000) |     9.02 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3045 | 2024-04-07 | Imperial fe       | L   | 0.427      | -            | -                | -                | -         |    -1.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3050 | 2024-04-07 | Fearless Cheetahs | W   | 0.426      | 0.262        | 0.003 (0.000)    | 0.067 (0.007)    | 0 (0.000) |     6.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3063 | 2024-04-06 | ex-GUILD fe       | W   | 0.420      | 0.262        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     5.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3156 | 2024-04-03 | Astralis W        | W   | 0.402      | 0.331        | -                | 0.022 (0.003)    | 0 (0.000) |     4.80 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3415 | 2024-03-20 | ENCE Athena       | W   | 0.308      | 0.331        | 0.002 (0.000)    | 0.038 (0.004)    | -         |     4.13 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3718 | 2024-03-07 | Imperial fe       | L   | 0.222      | -            | -                | -                | -         |    -0.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,798.30)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.894 | $750.00        | $670.85         |
| 2024-05-26 |      0.755 | $250.00        | $188.69         |
| 2024-04-27 |      0.561 | $321.00        | $180.01         |
| 2024-04-21 |      0.522 | $1,250.00      | $651.91         |
| 2024-04-07 |      0.427 | $250.00        | $106.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
