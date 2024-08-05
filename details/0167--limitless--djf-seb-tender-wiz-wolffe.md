### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [167](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.5<br />
<br />
Final Rank Value (668.5) = Starting Rank Value (747.5) + Head To Head Adjustments (-79.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.5
- 400 + ( ( 0.170 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 747.5


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
|           28 |      150 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.04 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      156 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.06 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      396 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.57 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      399 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      429 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.24 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      431 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.51 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      662 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.33 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      665 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.18 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      720 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.12 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      726 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.48 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      770 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.51 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      773 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.02 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1117 | 2024-06-13 | E-Xolos LAZER    | L   | 0.848      | -            | -                | -                | -         |   -11.91 | Lake, micro, Seb, Tender, wiz |
|           15 |     1470 | 2024-06-05 | LAG              | L   | 0.796      | -            | -                | -                | -         |   -10.45 | Lake, micro, Seb, Tender, wiz |
|           14 |     1512 | 2024-06-04 | LAG              | L   | 0.790      | -            | -                | -                | -         |   -11.13 | Lake, micro, Seb, Tender, wiz |
|           13 |     1826 | 2024-05-22 | MIGHT            | W   | 0.704      | 0.477        | 0.000 (0.000)    | 0.059 (0.020)    | 0 (0.000) |     4.06 | Lake, micro, Seb, Tender, wiz |
|           12 |     1831 | 2024-05-22 | MIGHT            | W   | 0.703      | 0.477        | 0.000 (0.000)    | 0.059 (0.020)    | 0 (0.000) |     4.21 | Lake, micro, Seb, Tender, wiz |
|           11 |     1879 | 2024-05-21 | Legacy           | L   | 0.696      | -            | -                | -                | -         |    -4.69 | Lake, micro, Seb, Tender, wiz |
|           10 |     1881 | 2024-05-21 | Wildcard         | L   | 0.696      | -            | -                | -                | -         |    -7.18 | Lake, micro, Seb, Tender, wiz |
|            9 |     1885 | 2024-05-21 | Wildcard         | L   | 0.696      | -            | -                | -                | -         |    -7.59 | Lake, micro, Seb, Tender, wiz |
|            8 |     1910 | 2024-05-20 | BOSS             | W   | 0.690      | 0.477        | 0.014 (0.005)    | 0.331 (0.109)    | 0 (0.000) |    10.85 | Lake, micro, Seb, Tender, wiz |
|            7 |     1914 | 2024-05-20 | BOSS             | L   | 0.690      | -            | -                | -                | -         |   -11.09 | Lake, micro, Seb, Tender, wiz |
|            6 |     2037 | 2024-05-16 | Take Flyte       | W   | 0.664      | 0.477        | 0.002 (0.001)    | 0.239 (0.076)    | 0 (0.000) |     7.49 | Lake, micro, Seb, Tender, wiz |
|            5 |     2038 | 2024-05-16 | Take Flyte       | W   | 0.663      | 0.477        | 0.002 (0.001)    | 0.239 (0.076)    | 0 (0.000) |     7.91 | Lake, micro, Seb, Tender, wiz |
|            4 |     2075 | 2024-05-15 | Nouns            | W   | 0.657      | 0.477        | 0.057 (0.018)    | 0.560 (0.175)    | 0 (0.000) |    14.25 | Lake, micro, Seb, Tender, wiz |
|            3 |     2080 | 2024-05-15 | Nouns            | W   | 0.657      | 0.477        | 0.057 (0.018)    | 0.560 (0.175)    | 0 (0.000) |    14.95 | Lake, micro, Seb, Tender, wiz |
|            2 |     2131 | 2024-05-14 | LAG              | L   | 0.650      | -            | -                | -                | -         |    -8.54 | Lake, micro, Seb, Tender, wiz |
|            1 |     2137 | 2024-05-14 | LAG              | W   | 0.650      | 0.477        | 0.012 (0.004)    | 0.351 (0.109)    | 0 (0.000) |    12.25 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,646.11)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
