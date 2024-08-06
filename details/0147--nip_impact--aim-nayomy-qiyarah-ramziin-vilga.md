### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  738.6<br />
<br />
Final Rank Value (738.6) = Starting Rank Value (703.7) + Head To Head Adjustments (34.9)<br />

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
|           24 |       30 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.139 (0.038)    | 0 (0.000) |    11.51 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       73 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.19 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |      101 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.139 (0.038)    | 0 (0.000) |    11.61 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      524 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.76 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      556 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.08 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1024 | 2024-06-16 | dream catchers fe | W   | 0.864      | 0.250        | 0.016 (0.003)    | 0.171 (0.037)    | 0 (0.000) |    13.40 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1767 | 2024-05-26 | Crescent fe       | L   | 0.724      | -            | -                | -                | -         |   -14.01 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1975 | 2024-05-19 | Imperial fe       | L   | 0.676      | -            | -                | -                | -         |    -3.12 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1998 | 2024-05-18 | Astralis W        | W   | 0.670      | 0.281        | 0.002 (0.000)    | 0.062 (0.012)    | 0 (0.000) |     8.82 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2541 | 2024-04-27 | Imperial fe       | L   | 0.531      | -            | -                | -                | -         |    -2.46 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2546 | 2024-04-27 | ENCE Athena       | W   | 0.530      | 0.252        | 0.002 (0.000)    | 0.034 (0.005)    | 0 (0.000) |     6.32 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2733 | 2024-04-19 | BIG EQUIPA        | L   | 0.478      | -            | -                | -                | -         |    -6.56 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2886 | 2024-04-15 | NAVI Javelins     | L   | 0.451      | -            | -                | -                | -         |    -5.36 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2899 | 2024-04-14 | Imperial fe       | L   | 0.444      | -            | -                | -                | -         |    -2.08 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2912 | 2024-04-13 | Astralis W        | W   | 0.438      | -            | -                | -                | 0 (0.000) |     4.75 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2953 | 2024-04-11 | Let Her Cook      | W   | 0.424      | 0.303        | 0.060 (0.008)    | 0.141 (0.018)    | 0 (0.000) |     9.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2997 | 2024-04-10 | Astralis W        | L   | 0.418      | -            | -                | -                | -         |    -7.77 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3058 | 2024-04-09 | NAVI Javelins     | W   | 0.410      | 0.303        | 0.026 (0.003)    | 0.184 (0.023)    | 0 (0.000) |     8.24 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3117 | 2024-04-07 | Imperial fe       | L   | 0.397      | -            | -                | -                | -         |    -1.82 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3122 | 2024-04-07 | Fearless Cheetahs | W   | 0.396      | 0.262        | 0.003 (0.000)    | 0.063 (0.007)    | 0 (0.000) |     5.92 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3135 | 2024-04-06 | Astralis W        | W   | 0.390      | 0.262        | 0.002 (0.000)    | 0.062 (0.006)    | -         |     5.33 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3226 | 2024-04-03 | Astralis W        | W   | 0.371      | -            | -                | -                | -         |     4.36 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3474 | 2024-03-20 | ENCE Athena       | W   | 0.278      | 0.331        | -                | 0.034 (0.003)    | -         |     3.65 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3771 | 2024-03-07 | Imperial fe       | L   | 0.192      | -            | -                | -                | -         |    -0.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,712.89)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $648.14         |
| 2024-05-26 |      0.724 | $250.00        | $181.12         |
| 2024-04-27 |      0.531 | $321.00        | $170.29         |
| 2024-04-21 |      0.491 | $1,250.00      | $614.06         |
| 2024-04-07 |      0.397 | $250.00        | $99.27          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
