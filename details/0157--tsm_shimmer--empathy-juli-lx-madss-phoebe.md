### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  696.3<br />
<br />
Final Rank Value (696.3) = Starting Rank Value (715.9) + Head To Head Adjustments (-19.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.9
- 400 + ( ( 0.153 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 715.9


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
|           24 |      140 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.004 (0.001)    | 0.036 (0.009)    | 0 (0.000) |    12.58 | empathy, Juli, Lx, madss, phoebe   |
|           23 |      885 | 2024-06-16 | Lotus fe         | W   | 0.896      | 0.250        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |    12.48 | abby, empathy, Juli, Lx, madss     |
|           22 |     1101 | 2024-06-09 | Perseverance     | L   | 0.848      | -            | -                | -                | -         |   -18.71 | abby, empathy, Florence, Lx, madss |
|           21 |     1207 | 2024-06-07 | Zomblers         | L   | 0.838      | -            | -                | -                | -         |   -19.19 | abby, empathy, Florence, Lx, madss |
|           20 |     1364 | 2024-06-05 | Asian Kings      | W   | 0.822      | -            | -                | -                | 0 (0.000) |     3.80 | abby, empathy, Florence, Lx, madss |
|           19 |     1408 | 2024-06-04 | Nouns            | L   | 0.816      | -            | -                | -                | -         |    -4.60 | abby, empathy, Florence, Lx, madss |
|           18 |     1410 | 2024-06-04 | Homyno           | L   | 0.815      | -            | -                | -                | -         |   -13.04 | abby, empathy, Florence, Lx, madss |
|           17 |     1518 | 2024-05-31 | NAVI Javelins    | L   | 0.790      | -            | -                | -                | -         |    -7.42 | abby, empathy, Lx, madss, phoebe   |
|           16 |     1524 | 2024-05-31 | panelinha        | L   | 0.789      | -            | -                | -                | -         |    -7.83 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1640 | 2024-05-26 | FlyQuest RED     | L   | 0.756      | -            | -                | -                | -         |   -10.82 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1641 | 2024-05-26 | Karma            | W   | 0.755      | 0.303        | 0.004 (0.001)    | 0.075 (0.017)    | 0 (0.000) |     9.60 | abby, empathy, Lx, madss, phoebe   |
|           13 |     2276 | 2024-05-05 | Lotus fe         | W   | 0.616      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.57 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2641 | 2024-04-19 | Limitless Angels | W   | 0.510      | 0.322        | 0.003 (0.000)    | 0.050 (0.008)    | 0 (0.000) |     6.29 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2823 | 2024-04-14 | FlyQuest RED     | L   | 0.476      | -            | -                | -                | -         |    -7.01 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2871 | 2024-04-11 | COVEN            | W   | 0.457      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.36 | abby, empathy, Lx, madss, phoebe   |
|            9 |     3038 | 2024-04-07 | Limitless Angels | W   | 0.430      | 0.250        | 0.003 (0.000)    | 0.050 (0.005)    | 0 (0.000) |     5.31 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3137 | 2024-04-03 | WG Bandits       | W   | 0.403      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     4.51 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3277 | 2024-03-27 | cleanup crew fe  | W   | 0.357      | 0.322        | -                | 0.022 (0.003)    | 0 (0.000) |     4.36 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3377 | 2024-03-21 | Karma            | W   | 0.317      | 0.322        | 0.004 (0.000)    | 0.075 (0.008)    | -         |     4.22 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3521 | 2024-03-14 | Nouns fe         | W   | 0.270      | 0.322        | 0.004 (0.000)    | 0.036 (0.003)    | -         |     3.58 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3737 | 2024-03-06 | FlyQuest RED     | L   | 0.217      | -            | -                | -                | -         |    -3.21 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3826 | 2024-03-03 | FlyQuest RED     | L   | 0.196      | -            | -                | -                | -         |    -2.96 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3969 | 2024-02-25 | FlyQuest RED     | L   | 0.150      | -            | -                | -                | -         |    -2.29 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4404 | 2024-02-04 | FlyQuest RED     | L   | 0.010      | -            | -                | -                | -         |    -0.15 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,758.21)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.896 | $750.00        | $672.33         |
| 2024-06-02 |      0.802 | $4,000.00      | $3,210.00       |
| 2024-05-26 |      0.756 | $1,500.00      | $1,133.26       |
| 2024-05-05 |      0.616 | $750.00        | $462.33         |
| 2024-04-14 |      0.476 | $250.00        | $119.03         |
| 2024-04-07 |      0.430 | $750.00        | $322.29         |
| 2024-03-03 |      0.196 | $250.00        | $49.10          |
| 2024-02-25 |      0.150 | $250.00        | $37.43          |
| 2024-02-04 |      0.010 | $250.00        | $2.44           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
