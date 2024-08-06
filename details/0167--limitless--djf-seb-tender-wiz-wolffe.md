### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.7<br />
<br />
Final Rank Value (668.7) = Starting Rank Value (747.9) + Head To Head Adjustments (-79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.9
- 400 + ( ( 0.170 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 747.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      161 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      167 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.06 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      407 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.58 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      410 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.34 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      440 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.26 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      442 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.53 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      673 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.31 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      676 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.16 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      731 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.14 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      737 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.50 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      781 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.54 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      784 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.05 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1128 | 2024-06-13 | E-Xolos LAZER    | L   | 0.845      | -            | -                | -                | -         |   -11.82 | Lake, micro, Seb, Tender, wiz |
|           15 |     1481 | 2024-06-05 | LAG              | L   | 0.792      | -            | -                | -                | -         |   -10.43 | Lake, micro, Seb, Tender, wiz |
|           14 |     1523 | 2024-06-04 | LAG              | L   | 0.787      | -            | -                | -                | -         |   -11.10 | Lake, micro, Seb, Tender, wiz |
|           13 |     1837 | 2024-05-22 | MIGHT            | W   | 0.700      | 0.477        | 0.000 (0.000)    | 0.058 (0.019)    | 0 (0.000) |     4.04 | Lake, micro, Seb, Tender, wiz |
|           12 |     1842 | 2024-05-22 | MIGHT            | W   | 0.700      | 0.477        | 0.000 (0.000)    | 0.058 (0.019)    | 0 (0.000) |     4.19 | Lake, micro, Seb, Tender, wiz |
|           11 |     1890 | 2024-05-21 | Legacy           | L   | 0.693      | -            | -                | -                | -         |    -4.70 | Lake, micro, Seb, Tender, wiz |
|           10 |     1892 | 2024-05-21 | Wildcard         | L   | 0.693      | -            | -                | -                | -         |    -7.16 | Lake, micro, Seb, Tender, wiz |
|            9 |     1896 | 2024-05-21 | Wildcard         | L   | 0.692      | -            | -                | -                | -         |    -7.56 | Lake, micro, Seb, Tender, wiz |
|            8 |     1921 | 2024-05-20 | BOSS             | W   | 0.687      | 0.477        | 0.014 (0.005)    | 0.326 (0.107)    | 0 (0.000) |    10.83 | Lake, micro, Seb, Tender, wiz |
|            7 |     1925 | 2024-05-20 | BOSS             | L   | 0.686      | -            | -                | -                | -         |   -11.01 | Lake, micro, Seb, Tender, wiz |
|            6 |     2048 | 2024-05-16 | Take Flyte       | W   | 0.660      | 0.477        | 0.002 (0.001)    | 0.236 (0.074)    | 0 (0.000) |     7.46 | Lake, micro, Seb, Tender, wiz |
|            5 |     2049 | 2024-05-16 | Take Flyte       | W   | 0.660      | 0.477        | 0.002 (0.001)    | 0.236 (0.074)    | 0 (0.000) |     7.88 | Lake, micro, Seb, Tender, wiz |
|            4 |     2086 | 2024-05-15 | Nouns            | W   | 0.654      | 0.477        | 0.057 (0.018)    | 0.553 (0.172)    | 0 (0.000) |    14.16 | Lake, micro, Seb, Tender, wiz |
|            3 |     2091 | 2024-05-15 | Nouns            | W   | 0.653      | 0.477        | 0.057 (0.018)    | 0.553 (0.172)    | 0 (0.000) |    14.86 | Lake, micro, Seb, Tender, wiz |
|            2 |     2142 | 2024-05-14 | LAG              | L   | 0.647      | -            | -                | -                | -         |    -8.51 | Lake, micro, Seb, Tender, wiz |
|            1 |     2148 | 2024-05-14 | LAG              | W   | 0.647      | 0.477        | 0.012 (0.004)    | 0.385 (0.119)    | 0 (0.000) |    12.16 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,639.44)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
