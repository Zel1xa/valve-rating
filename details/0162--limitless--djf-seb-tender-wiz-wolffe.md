### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  680.6<br />
<br />
Final Rank Value (680.6) = Starting Rank Value (749.4) + Head To Head Adjustments (-68.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.079[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 749.4
- 400 + ( ( 0.171 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 749.4


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
|           28 |       76 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.10 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |       82 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.11 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      321 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.32 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      324 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.05 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      354 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.65 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      356 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.96 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      587 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.17 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      590 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -6.53 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      642 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.19 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      648 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.56 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      692 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.55 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      695 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.07 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1014 | 2024-06-13 | E-Xolos LAZER    | L   | 0.860      | -            | -                | -                | -         |   -12.48 | Lake, micro, Seb, Tender, wiz |
|           15 |     1357 | 2024-06-05 | LAG              | L   | 0.808      | -            | -                | -                | -         |   -10.24 | Lake, micro, Seb, Tender, wiz |
|           14 |     1399 | 2024-06-04 | LAG              | L   | 0.803      | -            | -                | -                | -         |   -10.91 | Lake, micro, Seb, Tender, wiz |
|           13 |     1709 | 2024-05-22 | MIGHT            | W   | 0.716      | 0.477        | 0.000 (0.000)    | 0.062 (0.021)    | 0 (0.000) |     4.07 | Lake, micro, Seb, Tender, wiz |
|           12 |     1714 | 2024-05-22 | MIGHT            | W   | 0.716      | 0.477        | 0.000 (0.000)    | 0.062 (0.021)    | 0 (0.000) |     4.23 | Lake, micro, Seb, Tender, wiz |
|           11 |     1762 | 2024-05-21 | Legacy           | L   | 0.708      | -            | -                | -                | -         |    -4.88 | Lake, micro, Seb, Tender, wiz |
|           10 |     1764 | 2024-05-21 | Wildcard         | L   | 0.708      | -            | -                | -                | -         |    -6.58 | Lake, micro, Seb, Tender, wiz |
|            9 |     1768 | 2024-05-21 | Wildcard         | L   | 0.708      | -            | -                | -                | -         |    -6.94 | Lake, micro, Seb, Tender, wiz |
|            8 |     1793 | 2024-05-20 | BOSS             | W   | 0.702      | 0.477        | 0.014 (0.005)    | 0.344 (0.115)    | 0 (0.000) |    11.01 | Lake, micro, Seb, Tender, wiz |
|            7 |     1797 | 2024-05-20 | BOSS             | L   | 0.702      | -            | -                | -                | -         |   -11.33 | Lake, micro, Seb, Tender, wiz |
|            6 |     1919 | 2024-05-16 | Take Flyte       | W   | 0.676      | 0.477        | 0.002 (0.001)    | 0.249 (0.080)    | 0 (0.000) |     7.53 | Lake, micro, Seb, Tender, wiz |
|            5 |     1920 | 2024-05-16 | Take Flyte       | W   | 0.676      | 0.477        | 0.002 (0.001)    | 0.249 (0.080)    | 0 (0.000) |     7.96 | Lake, micro, Seb, Tender, wiz |
|            4 |     1957 | 2024-05-15 | Nouns            | W   | 0.669      | 0.477        | 0.057 (0.018)    | 0.566 (0.181)    | 0 (0.000) |    14.32 | Lake, micro, Seb, Tender, wiz |
|            3 |     1962 | 2024-05-15 | Nouns            | W   | 0.669      | 0.477        | 0.057 (0.018)    | 0.566 (0.181)    | 0 (0.000) |    15.06 | Lake, micro, Seb, Tender, wiz |
|            2 |     2013 | 2024-05-14 | LAG              | L   | 0.662      | -            | -                | -                | -         |    -8.30 | Lake, micro, Seb, Tender, wiz |
|            1 |     2019 | 2024-05-14 | LAG              | W   | 0.662      | 0.477        | 0.012 (0.004)    | 0.353 (0.111)    | 0 (0.000) |    12.89 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,670.65)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
