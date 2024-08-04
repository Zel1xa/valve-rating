### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [146](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
<br />
Final Rank Value:  725.6<br />
<br />
Final Rank Value (725.6) = Starting Rank Value (700.7) + Head To Head Adjustments (24.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.7
- 400 + ( ( 0.147 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 700.7


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
|           23 |       15 | 2024-08-03 | Imperial fe       | L   | 1.000      | -            | -                | -                | -         |    -4.14 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           22 |       43 | 2024-08-02 | Spirit fe         | W   | 1.000      | 0.273        | 0.005 (0.001)    | 0.141 (0.038)    | 0 (0.000) |    11.62 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           21 |      464 | 2024-07-21 | France fe         | L   | 1.000      | -            | -                | -                | -         |   -17.73 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           20 |      496 | 2024-07-20 | YeYO              | W   | 1.000      | 0.294        | 0.001 (0.000)    | -                | 0 (0.000) |     7.12 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           19 |      964 | 2024-06-16 | dream catchers fe | W   | 0.875      | 0.250        | 0.016 (0.003)    | 0.172 (0.038)    | 0 (0.000) |    13.58 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           18 |     1707 | 2024-05-26 | Crescent fe       | L   | 0.735      | -            | -                | -                | -         |   -14.18 | Nayomy, Qiyarah, ramziiN, spike, vilga |
|           17 |     1915 | 2024-05-19 | Imperial fe       | L   | 0.687      | -            | -                | -                | -         |    -3.14 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           16 |     1938 | 2024-05-18 | Astralis W        | W   | 0.681      | 0.281        | 0.002 (0.000)    | 0.064 (0.012)    | 0 (0.000) |     9.01 | aiM, Nayomy, Qiyarah, ramziiN, vilga   |
|           15 |     2481 | 2024-04-27 | Imperial fe       | L   | 0.541      | -            | -                | -                | -         |    -2.48 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           14 |     2486 | 2024-04-27 | ENCE Athena       | W   | 0.541      | 0.252        | 0.002 (0.000)    | 0.036 (0.005)    | 0 (0.000) |     6.49 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           13 |     2673 | 2024-04-19 | BIG EQUIPA        | L   | 0.489      | -            | -                | -                | -         |    -6.66 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           12 |     2826 | 2024-04-15 | NAVI Javelins     | L   | 0.462      | -            | -                | -                | -         |    -5.44 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           11 |     2839 | 2024-04-14 | Imperial fe       | L   | 0.455      | -            | -                | -                | -         |    -2.11 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|           10 |     2852 | 2024-04-13 | Astralis W        | W   | 0.448      | 0.303        | -                | 0.021 (0.003)    | 0 (0.000) |     4.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            9 |     2893 | 2024-04-11 | Let Her Cook      | W   | 0.435      | 0.303        | 0.060 (0.008)    | 0.144 (0.019)    | 0 (0.000) |    10.13 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            8 |     2937 | 2024-04-10 | Astralis W        | L   | 0.429      | -            | -                | -                | -         |    -7.93 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            7 |     2998 | 2024-04-09 | NAVI Javelins     | W   | 0.421      | 0.303        | 0.026 (0.003)    | 0.189 (0.024)    | 0 (0.000) |     8.51 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            6 |     3057 | 2024-04-07 | Imperial fe       | L   | 0.408      | -            | -                | -                | -         |    -1.84 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            5 |     3062 | 2024-04-07 | Fearless Cheetahs | W   | 0.407      | 0.262        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     6.14 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            4 |     3075 | 2024-04-06 | Astralis W        | W   | 0.400      | 0.262        | 0.002 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     5.53 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            3 |     3166 | 2024-04-03 | Astralis W        | W   | 0.382      | -            | -                | -                | -         |     4.54 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            2 |     3414 | 2024-03-20 | ENCE Athena       | W   | 0.289      | 0.331        | 0.002 (0.000)    | 0.036 (0.003)    | -         |     3.83 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |
|            1 |     3711 | 2024-03-07 | Imperial fe       | L   | 0.202      | -            | -                | -                | -         |    -0.86 | aiM, jenkon, Nayomy, Qiyarah, ramziiN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,743.45)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.875 | $750.00        | $656.27         |
| 2024-05-26 |      0.735 | $250.00        | $183.83         |
| 2024-04-27 |      0.541 | $321.00        | $173.77         |
| 2024-04-21 |      0.502 | $1,250.00      | $627.60         |
| 2024-04-07 |      0.408 | $250.00        | $101.98         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
