### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  720.9<br />
<br />
Final Rank Value (720.9) = Starting Rank Value (701.4) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.4
- 400 + ( ( 0.146 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 701.4


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
|           21 |      384 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.70 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      417 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.06 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      898 | 2024-06-16 | dream catchers fe | W   | 0.893      | 0.250        | 0.016 (0.004)    | 0.170 (0.038)    | 0 (0.000) |    13.79 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1650 | 2024-05-26 | Crescent fe       | L   | 0.753      | -            | -                | -                | -         |   -14.50 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1883 | 2024-05-19 | Imperial fe       | L   | 0.705      | -            | -                | -                | -         |    -3.13 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1906 | 2024-05-18 | ex-GUILD fe       | W   | 0.699      | 0.281        | 0.003 (0.001)    | 0.066 (0.013)    | 0 (0.000) |     9.26 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2464 | 2024-04-27 | Imperial fe       | L   | 0.559      | -            | -                | -                | -         |    -2.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2470 | 2024-04-27 | ENCE Athena       | W   | 0.559      | 0.252        | 0.002 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     6.71 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2663 | 2024-04-19 | BIG EQUIPA        | L   | 0.507      | -            | -                | -                | -         |    -6.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2819 | 2024-04-15 | NAVI Javelins     | L   | 0.480      | -            | -                | -                | -         |    -5.38 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2832 | 2024-04-14 | Imperial fe       | L   | 0.473      | -            | -                | -                | -         |    -2.12 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2845 | 2024-04-13 | Astralis W        | W   | 0.466      | 0.303        | 0.001 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     5.11 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2887 | 2024-04-11 | Let Her Cook      | W   | 0.453      | 0.303        | 0.061 (0.008)    | 0.146 (0.020)    | 0 (0.000) |    10.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2931 | 2024-04-10 | ex-GUILD fe       | L   | 0.447      | -            | -                | -                | -         |    -8.24 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     2992 | 2024-04-09 | NAVI Javelins     | W   | 0.439      | 0.303        | 0.027 (0.004)    | 0.210 (0.028)    | 0 (0.000) |     8.98 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3051 | 2024-04-07 | Imperial fe       | L   | 0.426      | -            | -                | -                | -         |    -1.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3056 | 2024-04-07 | Fearless Cheetahs | W   | 0.425      | 0.262        | 0.003 (0.000)    | 0.067 (0.007)    | 0 (0.000) |     6.47 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3069 | 2024-04-06 | ex-GUILD fe       | W   | 0.418      | 0.262        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     5.81 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3162 | 2024-04-03 | Astralis W        | W   | 0.400      | 0.331        | -                | 0.022 (0.003)    | 0 (0.000) |     4.78 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3421 | 2024-03-20 | ENCE Athena       | W   | 0.307      | 0.331        | 0.002 (0.000)    | 0.038 (0.004)    | -         |     4.11 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3724 | 2024-03-07 | Imperial fe       | L   | 0.220      | -            | -                | -                | -         |    -0.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,793.60)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.893 | $750.00        | $669.60         |
| 2024-05-26 |      0.753 | $250.00        | $188.27         |
| 2024-04-27 |      0.559 | $321.00        | $179.48         |
| 2024-04-21 |      0.520 | $1,250.00      | $649.83         |
| 2024-04-07 |      0.426 | $250.00        | $106.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
