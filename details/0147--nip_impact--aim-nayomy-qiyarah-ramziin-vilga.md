### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  738.7<br />
<br />
Final Rank Value (738.7) = Starting Rank Value (703.7) + Head To Head Adjustments (35.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.7
- 400 + ( ( 0.148 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 703.7


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
|           24 |       27 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.139 (0.038)    | 0 (0.000) |    11.50 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       70 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       98 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.139 (0.038)    | 0 (0.000) |    11.60 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      521 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.77 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      553 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.08 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1021 | 2024-06-16 | dream catchers fe | W   | 0.866      | 0.250        | 0.016 (0.003)    | 0.170 (0.037)    | 0 (0.000) |    13.43 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1764 | 2024-05-26 | Crescent fe       | L   | 0.727      | -            | -                | -                | -         |   -14.05 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1972 | 2024-05-19 | Imperial fe       | L   | 0.678      | -            | -                | -                | -         |    -3.13 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1995 | 2024-05-18 | Astralis W        | W   | 0.673      | 0.281        | 0.002 (0.000)    | 0.062 (0.012)    | 0 (0.000) |     8.85 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2538 | 2024-04-27 | Imperial fe       | L   | 0.533      | -            | -                | -                | -         |    -2.47 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2543 | 2024-04-27 | ENCE Athena       | W   | 0.532      | 0.252        | 0.002 (0.000)    | 0.034 (0.005)    | 0 (0.000) |     6.35 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2730 | 2024-04-19 | BIG EQUIPA        | L   | 0.480      | -            | -                | -                | -         |    -6.59 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2883 | 2024-04-15 | NAVI Javelins     | L   | 0.453      | -            | -                | -                | -         |    -5.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2896 | 2024-04-14 | Imperial fe       | L   | 0.447      | -            | -                | -                | -         |    -2.09 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2909 | 2024-04-13 | Astralis W        | W   | 0.440      | -            | -                | -                | 0 (0.000) |     4.78 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2950 | 2024-04-11 | Let Her Cook      | W   | 0.427      | 0.303        | 0.060 (0.008)    | 0.141 (0.018)    | 0 (0.000) |     9.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2994 | 2024-04-10 | Astralis W        | L   | 0.420      | -            | -                | -                | -         |    -7.81 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3055 | 2024-04-09 | NAVI Javelins     | W   | 0.413      | 0.303        | 0.026 (0.003)    | 0.184 (0.023)    | 0 (0.000) |     8.29 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3114 | 2024-04-07 | Imperial fe       | L   | 0.399      | -            | -                | -                | -         |    -1.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3119 | 2024-04-07 | Fearless Cheetahs | W   | 0.398      | 0.262        | 0.003 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     5.96 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3132 | 2024-04-06 | Astralis W        | W   | 0.392      | 0.262        | 0.002 (0.000)    | 0.062 (0.006)    | -         |     5.36 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3223 | 2024-04-03 | Astralis W        | W   | 0.373      | -            | -                | -                | -         |     4.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3471 | 2024-03-20 | ENCE Athena       | W   | 0.280      | 0.331        | -                | 0.034 (0.003)    | -         |     3.68 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3768 | 2024-03-07 | Imperial fe       | L   | 0.194      | -            | -                | -                | -         |    -0.84 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,719.15)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.866 | $750.00        | $649.81         |
| 2024-05-26 |      0.727 | $250.00        | $181.67         |
| 2024-04-27 |      0.533 | $321.00        | $171.01         |
| 2024-04-21 |      0.493 | $1,250.00      | $616.84         |
| 2024-04-07 |      0.399 | $250.00        | $99.83          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
