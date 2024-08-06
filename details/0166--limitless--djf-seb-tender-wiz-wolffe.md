### Roster Details<br />
Team Name: Limitless<br />
Roster: DJF, Seb, Tender, wiz, Wolffe<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  668.2<br />
<br />
Final Rank Value (668.2) = Starting Rank Value (747.7) + Head To Head Adjustments (-79.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.7
- 400 + ( ( 0.169 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 747.7


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
|           28 |      169 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.05 | DJF, Seb, Tender, wiz, Wolffe |
|           27 |      175 | 2024-07-31 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.06 | DJF, Seb, Tender, wiz, Wolffe |
|           26 |      415 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |    -9.59 | DJF, Seb, Tender, wiz, Wolffe |
|           25 |      418 | 2024-07-24 | LAG              | L   | 1.000      | -            | -                | -                | -         |   -10.35 | DJF, Seb, Tender, wiz, Wolffe |
|           24 |      448 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.27 | DJF, Seb, Tender, wiz, Wolffe |
|           23 |      450 | 2024-07-23 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -5.54 | DJF, Seb, Tender, wiz, Wolffe |
|           22 |      681 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -10.31 | DJF, Seb, Tender, wiz, Wolffe |
|           21 |      684 | 2024-07-17 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |   -11.17 | DJF, Seb, Tender, wiz, Wolffe |
|           20 |      739 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.16 | DJF, Seb, Tender, wiz, Wolffe |
|           19 |      745 | 2024-07-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -6.52 | DJF, Seb, Tender, wiz, Wolffe |
|           18 |      789 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.55 | DJF, Seb, Tender, wiz, Wolffe |
|           17 |      792 | 2024-07-15 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.07 | DJF, Seb, Tender, wiz, Wolffe |
|           16 |     1136 | 2024-06-13 | E-Xolos LAZER    | L   | 0.842      | -            | -                | -                | -         |   -11.78 | Lake, micro, Seb, Tender, wiz |
|           15 |     1489 | 2024-06-05 | LAG              | L   | 0.790      | -            | -                | -                | -         |   -10.40 | Lake, micro, Seb, Tender, wiz |
|           14 |     1531 | 2024-06-04 | LAG              | L   | 0.784      | -            | -                | -                | -         |   -11.06 | Lake, micro, Seb, Tender, wiz |
|           13 |     1845 | 2024-05-22 | MIGHT            | W   | 0.697      | 0.477        | 0.000 (0.000)    | 0.056 (0.019)    | 0 (0.000) |     4.02 | Lake, micro, Seb, Tender, wiz |
|           12 |     1850 | 2024-05-22 | MIGHT            | W   | 0.697      | 0.477        | 0.000 (0.000)    | 0.056 (0.019)    | 0 (0.000) |     4.18 | Lake, micro, Seb, Tender, wiz |
|           11 |     1898 | 2024-05-21 | Legacy           | L   | 0.690      | -            | -                | -                | -         |    -4.70 | Lake, micro, Seb, Tender, wiz |
|           10 |     1900 | 2024-05-21 | Wildcard         | L   | 0.690      | -            | -                | -                | -         |    -7.14 | Lake, micro, Seb, Tender, wiz |
|            9 |     1904 | 2024-05-21 | Wildcard         | L   | 0.689      | -            | -                | -                | -         |    -7.54 | Lake, micro, Seb, Tender, wiz |
|            8 |     1929 | 2024-05-20 | BOSS             | W   | 0.684      | 0.477        | 0.014 (0.005)    | 0.319 (0.104)    | 0 (0.000) |    10.78 | Lake, micro, Seb, Tender, wiz |
|            7 |     1933 | 2024-05-20 | BOSS             | L   | 0.684      | -            | -                | -                | -         |   -10.97 | Lake, micro, Seb, Tender, wiz |
|            6 |     2056 | 2024-05-16 | Take Flyte       | W   | 0.657      | 0.477        | 0.002 (0.001)    | 0.231 (0.072)    | 0 (0.000) |     7.44 | Lake, micro, Seb, Tender, wiz |
|            5 |     2057 | 2024-05-16 | Take Flyte       | W   | 0.657      | 0.477        | 0.002 (0.001)    | 0.231 (0.072)    | 0 (0.000) |     7.85 | Lake, micro, Seb, Tender, wiz |
|            4 |     2094 | 2024-05-15 | Nouns            | W   | 0.651      | 0.477        | 0.057 (0.018)    | 0.541 (0.168)    | 0 (0.000) |    14.09 | Lake, micro, Seb, Tender, wiz |
|            3 |     2099 | 2024-05-15 | Nouns            | W   | 0.651      | 0.477        | 0.057 (0.018)    | 0.541 (0.168)    | 0 (0.000) |    14.78 | Lake, micro, Seb, Tender, wiz |
|            2 |     2150 | 2024-05-14 | LAG              | L   | 0.644      | -            | -                | -                | -         |    -8.49 | Lake, micro, Seb, Tender, wiz |
|            1 |     2156 | 2024-05-14 | LAG              | W   | 0.644      | 0.477        | 0.012 (0.004)    | 0.376 (0.115)    | 0 (0.000) |    12.10 | Lake, micro, Seb, Tender, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,633.89)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
