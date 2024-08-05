### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  738.5<br />
<br />
Final Rank Value (738.5) = Starting Rank Value (703.5) + Head To Head Adjustments (35.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.5
- 400 + ( ( 0.148 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 703.5


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
|           24 |       19 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.140 (0.038)    | 0 (0.000) |    11.50 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       62 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       90 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.140 (0.038)    | 0 (0.000) |    11.59 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      513 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.78 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      545 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.08 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1013 | 2024-06-16 | dream catchers fe | W   | 0.868      | 0.250        | 0.016 (0.003)    | 0.172 (0.037)    | 0 (0.000) |    13.44 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1756 | 2024-05-26 | Crescent fe       | L   | 0.728      | -            | -                | -                | -         |   -14.08 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1964 | 2024-05-19 | Imperial fe       | L   | 0.679      | -            | -                | -                | -         |    -3.14 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1987 | 2024-05-18 | Astralis W        | W   | 0.674      | 0.281        | 0.002 (0.000)    | 0.063 (0.012)    | 0 (0.000) |     8.86 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2530 | 2024-04-27 | Imperial fe       | L   | 0.534      | -            | -                | -                | -         |    -2.47 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2535 | 2024-04-27 | ENCE Athena       | W   | 0.533      | 0.252        | 0.002 (0.000)    | 0.035 (0.005)    | 0 (0.000) |     6.36 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2722 | 2024-04-19 | BIG EQUIPA        | L   | 0.481      | -            | -                | -                | -         |    -6.61 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2875 | 2024-04-15 | NAVI Javelins     | L   | 0.454      | -            | -                | -                | -         |    -5.40 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2888 | 2024-04-14 | Imperial fe       | L   | 0.448      | -            | -                | -                | -         |    -2.10 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2901 | 2024-04-13 | Astralis W        | W   | 0.441      | -            | -                | -                | 0 (0.000) |     4.79 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2942 | 2024-04-11 | Let Her Cook      | W   | 0.428      | 0.303        | 0.060 (0.008)    | 0.143 (0.019)    | 0 (0.000) |     9.93 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2986 | 2024-04-10 | Astralis W        | L   | 0.421      | -            | -                | -                | -         |    -7.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3047 | 2024-04-09 | NAVI Javelins     | W   | 0.414      | 0.303        | 0.026 (0.003)    | 0.187 (0.023)    | 0 (0.000) |     8.31 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3106 | 2024-04-07 | Imperial fe       | L   | 0.400      | -            | -                | -                | -         |    -1.84 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3111 | 2024-04-07 | Fearless Cheetahs | W   | 0.399      | 0.262        | 0.003 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     5.98 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3124 | 2024-04-06 | Astralis W        | W   | 0.393      | 0.262        | 0.002 (0.000)    | 0.063 (0.006)    | -         |     5.38 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3215 | 2024-04-03 | Astralis W        | W   | 0.375      | -            | -                | -                | -         |     4.40 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3463 | 2024-03-20 | ENCE Athena       | W   | 0.282      | 0.331        | -                | 0.035 (0.003)    | -         |     3.70 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3760 | 2024-03-07 | Imperial fe       | L   | 0.195      | -            | -                | -                | -         |    -0.85 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,722.29)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.868 | $750.00        | $650.64         |
| 2024-05-26 |      0.728 | $250.00        | $181.95         |
| 2024-04-27 |      0.534 | $321.00        | $171.36         |
| 2024-04-21 |      0.495 | $1,250.00      | $618.23         |
| 2024-04-07 |      0.400 | $250.00        | $100.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
