### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  738.7<br />
<br />
Final Rank Value (738.7) = Starting Rank Value (703.5) + Head To Head Adjustments (35.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.5
- 400 + ( ( 0.148 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 703.5


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
|           24 |        2 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.141 (0.038)    | 0 (0.000) |    11.47 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       45 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       73 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.141 (0.038)    | 0 (0.000) |    11.56 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      496 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.81 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      528 | 2024-07-20 | YeYO              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.06 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      996 | 2024-06-16 | dream catchers fe | W   | 0.873      | 0.250        | 0.016 (0.003)    | 0.172 (0.038)    | 0 (0.000) |    13.49 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1739 | 2024-05-26 | Crescent fe       | L   | 0.734      | -            | -                | -                | -         |   -14.21 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1947 | 2024-05-19 | Imperial fe       | L   | 0.685      | -            | -                | -                | -         |    -3.16 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1970 | 2024-05-18 | Astralis W        | W   | 0.680      | 0.281        | 0.002 (0.000)    | 0.064 (0.012)    | 0 (0.000) |     8.93 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2513 | 2024-04-27 | Imperial fe       | L   | 0.540      | -            | -                | -                | -         |    -2.50 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2518 | 2024-04-27 | ENCE Athena       | W   | 0.539      | 0.252        | 0.002 (0.000)    | 0.036 (0.005)    | 0 (0.000) |     6.42 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2705 | 2024-04-19 | BIG EQUIPA        | L   | 0.487      | -            | -                | -                | -         |    -6.69 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2858 | 2024-04-15 | NAVI Javelins     | L   | 0.460      | -            | -                | -                | -         |    -5.47 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2871 | 2024-04-14 | Imperial fe       | L   | 0.453      | -            | -                | -                | -         |    -2.12 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2884 | 2024-04-13 | Astralis W        | W   | 0.447      | -            | -                | -                | 0 (0.000) |     4.84 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2925 | 2024-04-11 | Let Her Cook      | W   | 0.433      | 0.303        | 0.060 (0.008)    | 0.144 (0.019)    | 0 (0.000) |    10.06 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2969 | 2024-04-10 | Astralis W        | L   | 0.427      | -            | -                | -                | -         |    -7.94 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3030 | 2024-04-09 | NAVI Javelins     | W   | 0.419      | 0.303        | 0.026 (0.003)    | 0.189 (0.024)    | 0 (0.000) |     8.43 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3089 | 2024-04-07 | Imperial fe       | L   | 0.406      | -            | -                | -                | -         |    -1.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3094 | 2024-04-07 | Fearless Cheetahs | W   | 0.405      | 0.262        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     6.07 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3107 | 2024-04-06 | Astralis W        | W   | 0.399      | 0.262        | 0.002 (0.000)    | 0.064 (0.007)    | -         |     5.45 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3198 | 2024-04-03 | Astralis W        | W   | 0.380      | -            | -                | -                | -         |     4.47 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3446 | 2024-03-20 | ENCE Athena       | W   | 0.287      | 0.331        | 0.002 (0.000)    | 0.036 (0.003)    | -         |     3.78 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3743 | 2024-03-07 | Imperial fe       | L   | 0.201      | -            | -                | -                | -         |    -0.87 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,738.42)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.873 | $750.00        | $654.93         |
| 2024-05-26 |      0.734 | $250.00        | $183.38         |
| 2024-04-27 |      0.540 | $321.00        | $173.20         |
| 2024-04-21 |      0.500 | $1,250.00      | $625.38         |
| 2024-04-07 |      0.406 | $250.00        | $101.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
