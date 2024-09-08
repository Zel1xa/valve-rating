### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: Lake, micro, Seb, Tender, wiz<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
<br />
Final Rank Value:  702.2<br />
<br />
Final Rank Value (702.2) = Starting Rank Value (703.4) + Head To Head Adjustments (-1.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.4
- 400 + ( ( 0.157 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 703.4


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
|           28 |     2267 | 2024-06-13 | E-Xolos LAZER    | L   | 0.621      | -            | -                | -                | -         |    -8.01 | Lake, micro, Seb, Tender, wiz |
|           27 |     2620 | 2024-06-05 | LAG              | L   | 0.569      | -            | -                | -                | -         |    -7.84 | Lake, micro, Seb, Tender, wiz |
|           26 |     2662 | 2024-06-04 | LAG              | L   | 0.564      | -            | -                | -                | -         |    -8.16 | Lake, micro, Seb, Tender, wiz |
|           25 |     2976 | 2024-05-22 | MIGHT            | W   | 0.477      | 0.477        | 0.000 (0.000)    | 0.025 (0.006)    | 0 (0.000) |     3.12 | Lake, micro, Seb, Tender, wiz |
|           24 |     2981 | 2024-05-22 | MIGHT            | W   | 0.477      | 0.477        | 0.000 (0.000)    | 0.025 (0.006)    | 0 (0.000) |     3.21 | Lake, micro, Seb, Tender, wiz |
|           23 |     3029 | 2024-05-21 | Legacy           | L   | 0.469      | -            | -                | -                | -         |    -4.03 | Lake, micro, Seb, Tender, wiz |
|           22 |     3031 | 2024-05-21 | Wildcard         | L   | 0.469      | -            | -                | -                | -         |    -2.60 | Lake, micro, Seb, Tender, wiz |
|           21 |     3035 | 2024-05-21 | Wildcard         | L   | 0.469      | -            | -                | -                | -         |    -2.66 | Lake, micro, Seb, Tender, wiz |
|           20 |     3060 | 2024-05-20 | BOSS             | W   | 0.463      | 0.477        | 0.013 (0.003)    | 0.401 (0.089)    | 0 (0.000) |     8.17 | Lake, micro, Seb, Tender, wiz |
|           19 |     3064 | 2024-05-20 | BOSS             | L   | 0.463      | -            | -                | -                | -         |    -6.54 | Lake, micro, Seb, Tender, wiz |
|           18 |     3187 | 2024-05-16 | Take Flyte       | W   | 0.437      | 0.477        | 0.002 (0.000)    | 0.230 (0.048)    | 0 (0.000) |     5.90 | Lake, micro, Seb, Tender, wiz |
|           17 |     3188 | 2024-05-16 | Take Flyte       | W   | 0.437      | 0.477        | 0.002 (0.000)    | 0.230 (0.048)    | 0 (0.000) |     6.13 | Lake, micro, Seb, Tender, wiz |
|           16 |     3225 | 2024-05-15 | Nouns            | W   | 0.430      | 0.477        | 0.056 (0.012)    | 0.519 (0.107)    | 0 (0.000) |     9.89 | Lake, micro, Seb, Tender, wiz |
|           15 |     3230 | 2024-05-15 | Nouns            | W   | 0.430      | 0.477        | 0.056 (0.012)    | 0.519 (0.107)    | 0 (0.000) |    10.18 | Lake, micro, Seb, Tender, wiz |
|           14 |     3281 | 2024-05-14 | LAG              | L   | 0.424      | -            | -                | -                | -         |    -5.82 | Lake, micro, Seb, Tender, wiz |
|           13 |     3287 | 2024-05-14 | LAG              | W   | 0.423      | 0.477        | 0.007 (0.001)    | 0.371 (0.075)    | 0 (0.000) |     7.70 | Lake, micro, Seb, Tender, wiz |
|           12 |     4076 | 2024-04-11 | Mythic           | W   | 0.204      | 0.477        | 0.007 (0.001)    | 0.276 (0.027)    | 0 (0.000) |     3.87 | arcade, Lake, micro, Seb, wiz |
|           11 |     4078 | 2024-04-11 | Mythic           | L   | 0.203      | -            | -                | -                | -         |    -2.58 | arcade, Lake, micro, Seb, wiz |
|           10 |     4166 | 2024-04-09 | NRG              | L   | 0.190      | -            | -                | -                | -         |    -1.96 | arcade, Lake, micro, Seb, wiz |
|            9 |     4169 | 2024-04-09 | NRG              | L   | 0.190      | -            | -                | -                | -         |    -1.99 | arcade, Lake, micro, Seb, wiz |
|            8 |     4293 | 2024-04-04 | Phoenix          | L   | 0.157      | -            | -                | -                | -         |    -2.47 | arcade, Lake, micro, Seb, wiz |
|            7 |     4298 | 2024-04-04 | Phoenix          | L   | 0.157      | -            | -                | -                | -         |    -2.50 | arcade, Lake, micro, Seb, wiz |
|            6 |     4472 | 2024-03-27 | Party Astronauts | L   | 0.104      | -            | -                | -                | -         |    -0.94 | arcade, Lake, micro, Seb, wiz |
|            5 |     4475 | 2024-03-27 | Party Astronauts | L   | 0.104      | -            | -                | -                | -         |    -0.94 | arcade, Lake, micro, Seb, wiz |
|            4 |     4691 | 2024-03-15 | timbermen        | L   | 0.024      | -            | -                | -                | -         |    -0.17 | arcade, Lake, micro, Seb, wiz |
|            3 |     4693 | 2024-03-15 | timbermen        | L   | 0.024      | -            | -                | -                | -         |    -0.16 | arcade, Lake, micro, Seb, wiz |
|            2 |     4751 | 2024-03-13 | Party Astronauts | L   | 0.009      | -            | -                | -                | -         |    -0.08 | arcade, Lake, micro, Seb, wiz |
|            1 |     4791 | 2024-03-12 | NRG              | W   | 0.003      | 0.143        | 0.018 (0.000)    | 0.573 (0.000)    | 0 (0.000) |     0.07 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,192.78)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
