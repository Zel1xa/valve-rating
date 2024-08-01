### Roster Details<br />
Team Name: Akimbo<br />
Roster: arviast, hyza, laxiee, N2o, obi<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
<br />
Final Rank Value:  755.3<br />
<br />
Final Rank Value (755.3) = Starting Rank Value (766.1) + Head To Head Adjustments (-10.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.067[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 766.1
- 400 + ( ( 0.178 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 766.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      111 | 2024-07-29 | jahsdnmasjdm     | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.62 | arviast, hyza, laxiee, N2o, obi        |
|           21 |      189 | 2024-07-26 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.57 | hyza, kmrn, laxiee, N2o, obi           |
|           20 |      884 | 2024-06-16 | E-Xolos LAZER    | L   | 0.897      | -            | -                | -                | -         |   -13.51 | calamity, kralz , laxiee, N2o, obi     |
|           19 |      908 | 2024-06-15 | Take Flyte       | L   | 0.890      | -            | -                | -                | -         |   -18.26 | calamity, kralz , laxiee, N2o, obi     |
|           18 |      912 | 2024-06-15 | Legacy           | L   | 0.889      | -            | -                | -                | -         |    -5.42 | calamity, kralz , laxiee, N2o, obi     |
|           17 |      941 | 2024-06-14 | Homyno           | W   | 0.884      | 0.143        | 0.008 (0.001)    | 0.160 (0.020)    | 0 (0.000) |     9.16 | calamity, kralz , laxiee, N2o, obi     |
|           16 |      943 | 2024-06-14 | Perseverance     | W   | 0.882      | 0.371        | 0.004 (0.001)    | 0.247 (0.081)    | 0 (0.000) |    11.61 | calamity, kralz , laxiee, N2o, obi     |
|           15 |     1053 | 2024-06-10 | Legacy           | L   | 0.857      | -            | -                | -                | -         |    -5.05 | calamity, kralz , laxiee, N2o, obi     |
|           14 |     1087 | 2024-06-09 | E-Xolos LAZER    | W   | 0.850      | 0.368        | 0.011 (0.003)    | 0.386 (0.121)    | 0 (0.000) |    12.88 | calamity, kralz , laxiee, N2o, obi     |
|           13 |     1270 | 2024-06-06 | FLUFFY AIMERS    | W   | 0.831      | 0.371        | 0.003 (0.001)    | 0.305 (0.094)    | 0 (0.000) |    10.37 | calamity, kralz , laxiee, N2o, obi     |
|           12 |     1279 | 2024-06-06 | Legacy           | L   | 0.829      | -            | -                | -                | -         |    -5.34 | calamity, kralz , laxiee, N2o, obi     |
|           11 |     1401 | 2024-06-04 | Final Form       | W   | 0.817      | 0.371        | 0.003 (0.001)    | 0.098 (0.030)    | 0 (0.000) |     8.55 | calamity, kralz , laxiee, N2o, obi     |
|           10 |     1436 | 2024-06-03 | Villainous       | W   | 0.810      | 0.368        | 0.003 (0.001)    | 0.000 (0.000)    | 0 (0.000) |     5.63 | calamity, kralz , laxiee, N2o, obi     |
|            9 |     1810 | 2024-05-20 | Party Astronauts | L   | 0.717      | -            | -                | -                | -         |    -6.24 | calamity, kralz , laxiee, N2o, obi     |
|            8 |     2741 | 2024-04-17 | Liquid           | L   | 0.496      | -            | -                | -                | -         |    -0.33 | calamity, kralz , laxiee, N2o, obi     |
|            7 |     2747 | 2024-04-17 | NRG              | W   | 0.496      | 0.143        | 0.020 (0.001)    | 0.519 (0.037)    | 0 (0.000) |    10.14 | calamity, kralz , laxiee, N2o, obi     |
|            6 |     3450 | 2024-03-17 | LAG              | L   | 0.291      | -            | -                | -                | -         |    -3.37 | arviast, C4LLM3SU3, calamity, N2o, obi |
|            5 |     3451 | 2024-03-17 | Xiaoma           | W   | 0.290      | 0.333        | 0.001 (0.000)    | 0.011 (0.001)    | 1 (0.290) |     2.09 | arviast, C4LLM3SU3, calamity, N2o, obi |
|            4 |     3459 | 2024-03-17 | Snakes Den       | W   | 0.289      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.289) |     1.06 | arviast, C4LLM3SU3, calamity, N2o, obi |
|            3 |     3998 | 2024-02-24 | Wildcard         | L   | 0.143      | -            | -                | -                | -         |    -1.34 | C4LLM3SU3, calamity, laxiee, N2o, obi  |
|            2 |     4117 | 2024-02-19 | Mythic           | L   | 0.111      | -            | -                | -                | -         |    -1.57 | C4LLM3SU3, calamity, laxiee, N2o, obi  |
|            1 |     4119 | 2024-02-19 | Party Astronauts | L   | 0.110      | -            | -                | -                | -         |    -0.96 | C4LLM3SU3, calamity, laxiee, N2o, obi  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,085.35)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.897 | $750.00        | $672.81         |
| 2024-06-10 |      0.857 | $4,300.00      | $3,685.46       |
| 2024-03-17 |      0.291 | $2,500.00      | $727.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
