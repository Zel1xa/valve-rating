### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  696.0<br />
<br />
Final Rank Value (696.0) = Starting Rank Value (715.5) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.5
- 400 + ( ( 0.153 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 715.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      144 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.004 (0.001)    | 0.036 (0.009)    | 0 (0.000) |    12.58 | empathy, Juli, Lx, madss, phoebe   |
|           23 |      889 | 2024-06-16 | Lotus fe         | W   | 0.895      | 0.250        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |    12.47 | abby, empathy, Juli, Lx, madss     |
|           22 |     1105 | 2024-06-09 | Perseverance     | L   | 0.847      | -            | -                | -                | -         |   -18.68 | abby, empathy, Florence, Lx, madss |
|           21 |     1211 | 2024-06-07 | Zomblers         | L   | 0.836      | -            | -                | -                | -         |   -19.15 | abby, empathy, Florence, Lx, madss |
|           20 |     1368 | 2024-06-05 | Asian Kings      | W   | 0.820      | -            | -                | -                | 0 (0.000) |     3.80 | abby, empathy, Florence, Lx, madss |
|           19 |     1412 | 2024-06-04 | Nouns            | L   | 0.815      | -            | -                | -                | -         |    -4.60 | abby, empathy, Florence, Lx, madss |
|           18 |     1414 | 2024-06-04 | Homyno           | L   | 0.814      | -            | -                | -                | -         |   -13.02 | abby, empathy, Florence, Lx, madss |
|           17 |     1522 | 2024-05-31 | NAVI Javelins    | L   | 0.789      | -            | -                | -                | -         |    -7.42 | abby, empathy, Lx, madss, phoebe   |
|           16 |     1528 | 2024-05-31 | panelinha        | L   | 0.787      | -            | -                | -                | -         |    -7.82 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1644 | 2024-05-26 | FlyQuest RED     | L   | 0.754      | -            | -                | -                | -         |   -10.81 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1645 | 2024-05-26 | Karma            | W   | 0.754      | 0.303        | 0.004 (0.001)    | 0.075 (0.017)    | 0 (0.000) |     9.59 | abby, empathy, Lx, madss, phoebe   |
|           13 |     2280 | 2024-05-05 | Lotus fe         | W   | 0.615      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.55 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2645 | 2024-04-19 | Limitless Angels | W   | 0.509      | 0.322        | 0.003 (0.000)    | 0.050 (0.008)    | 0 (0.000) |     6.28 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2827 | 2024-04-14 | FlyQuest RED     | L   | 0.475      | -            | -                | -                | -         |    -6.99 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2875 | 2024-04-11 | COVEN            | W   | 0.455      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.36 | abby, empathy, Lx, madss, phoebe   |
|            9 |     3042 | 2024-04-07 | Limitless Angels | W   | 0.428      | 0.250        | 0.003 (0.000)    | 0.050 (0.005)    | 0 (0.000) |     5.30 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3141 | 2024-04-03 | WG Bandits       | W   | 0.402      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.50 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3281 | 2024-03-27 | cleanup crew fe  | W   | 0.355      | 0.322        | -                | 0.022 (0.003)    | 0 (0.000) |     4.34 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3381 | 2024-03-21 | Karma            | W   | 0.315      | 0.322        | 0.004 (0.000)    | 0.075 (0.008)    | -         |     4.20 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3525 | 2024-03-14 | Nouns fe         | W   | 0.269      | 0.322        | 0.004 (0.000)    | 0.036 (0.003)    | -         |     3.56 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3741 | 2024-03-06 | FlyQuest RED     | L   | 0.216      | -            | -                | -                | -         |    -3.19 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3830 | 2024-03-03 | FlyQuest RED     | L   | 0.195      | -            | -                | -                | -         |    -2.94 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3973 | 2024-02-25 | FlyQuest RED     | L   | 0.148      | -            | -                | -                | -         |    -2.27 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4408 | 2024-02-04 | FlyQuest RED     | L   | 0.008      | -            | -                | -                | -         |    -0.13 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,746.06)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.895 | $750.00        | $671.28         |
| 2024-06-02 |      0.801 | $4,000.00      | $3,204.44       |
| 2024-05-26 |      0.754 | $1,500.00      | $1,131.18       |
| 2024-05-05 |      0.615 | $750.00        | $461.28         |
| 2024-04-14 |      0.475 | $250.00        | $118.68         |
| 2024-04-07 |      0.428 | $750.00        | $321.25         |
| 2024-03-03 |      0.195 | $250.00        | $48.76          |
| 2024-02-25 |      0.148 | $250.00        | $37.08          |
| 2024-02-04 |      0.008 | $250.00        | $2.09           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
