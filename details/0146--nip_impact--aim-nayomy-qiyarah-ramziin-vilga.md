### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
<br />
Final Rank Value:  738.6<br />
<br />
Final Rank Value (738.6) = Starting Rank Value (703.5) + Head To Head Adjustments (35.1)<br />

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
|           24 |        6 | 2024-08-04 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.141 (0.038)    | 0 (0.000) |    11.48 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           23 |       49 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.18 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       77 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.141 (0.038)    | 0 (0.000) |    11.57 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      500 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.79 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      532 | 2024-07-20 | YeYO              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.07 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |     1000 | 2024-06-16 | dream catchers fe | W   | 0.871      | 0.250        | 0.016 (0.003)    | 0.173 (0.038)    | 0 (0.000) |    13.47 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1743 | 2024-05-26 | Crescent fe       | L   | 0.731      | -            | -                | -                | -         |   -14.15 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1951 | 2024-05-19 | Imperial fe       | L   | 0.683      | -            | -                | -                | -         |    -3.15 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1974 | 2024-05-18 | Astralis W        | W   | 0.677      | 0.281        | 0.002 (0.000)    | 0.063 (0.012)    | 0 (0.000) |     8.90 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2517 | 2024-04-27 | Imperial fe       | L   | 0.537      | -            | -                | -                | -         |    -2.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2522 | 2024-04-27 | ENCE Athena       | W   | 0.537      | 0.252        | 0.002 (0.000)    | 0.035 (0.005)    | 0 (0.000) |     6.39 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2709 | 2024-04-19 | BIG EQUIPA        | L   | 0.485      | -            | -                | -                | -         |    -6.65 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2862 | 2024-04-15 | NAVI Javelins     | L   | 0.458      | -            | -                | -                | -         |    -5.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2875 | 2024-04-14 | Imperial fe       | L   | 0.451      | -            | -                | -                | -         |    -2.11 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2888 | 2024-04-13 | Astralis W        | W   | 0.444      | -            | -                | -                | 0 (0.000) |     4.82 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2929 | 2024-04-11 | Let Her Cook      | W   | 0.431      | 0.303        | 0.060 (0.008)    | 0.144 (0.019)    | 0 (0.000) |    10.00 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2973 | 2024-04-10 | Astralis W        | L   | 0.425      | -            | -                | -                | -         |    -7.89 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     3034 | 2024-04-09 | NAVI Javelins     | W   | 0.417      | 0.303        | 0.026 (0.003)    | 0.188 (0.024)    | 0 (0.000) |     8.38 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3093 | 2024-04-07 | Imperial fe       | L   | 0.404      | -            | -                | -                | -         |    -1.85 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3098 | 2024-04-07 | Fearless Cheetahs | W   | 0.403      | 0.262        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     6.03 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3111 | 2024-04-06 | Astralis W        | W   | 0.396      | 0.262        | 0.002 (0.000)    | 0.063 (0.007)    | -         |     5.42 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3202 | 2024-04-03 | Astralis W        | W   | 0.378      | -            | -                | -                | -         |     4.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3450 | 2024-03-20 | ENCE Athena       | W   | 0.285      | 0.331        | 0.002 (0.000)    | 0.035 (0.003)    | -         |     3.74 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3747 | 2024-03-07 | Imperial fe       | L   | 0.198      | -            | -                | -                | -         |    -0.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,731.69)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.871 | $750.00        | $653.14         |
| 2024-05-26 |      0.731 | $250.00        | $182.78         |
| 2024-04-27 |      0.537 | $321.00        | $172.43         |
| 2024-04-21 |      0.498 | $1,250.00      | $622.40         |
| 2024-04-07 |      0.404 | $250.00        | $100.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
