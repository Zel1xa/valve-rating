### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  694.2<br />
<br />
Final Rank Value (694.2) = Starting Rank Value (713.3) + Head To Head Adjustments (-19.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.3
- 400 + ( ( 0.152 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 713.3


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
|           23 |      304 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.032 (0.008)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |     1032 | 2024-06-16 | Lotus fe         | W   | 0.862      | 0.250        | 0.004 (0.001)    | 0.037 (0.008)    | 0 (0.000) |    12.08 | abby, empathy, Juli, Lx, madss     |
|           21 |     1257 | 2024-06-09 | Perseverance     | L   | 0.814      | -            | -                | -                | -         |   -17.97 | abby, empathy, Florence, Lx, madss |
|           20 |     1359 | 2024-06-07 | Zomblers         | L   | 0.804      | -            | -                | -                | -         |   -18.61 | abby, empathy, Florence, Lx, madss |
|           19 |     1507 | 2024-06-05 | Asian Kings      | W   | 0.788      | -            | -                | -                | 0 (0.000) |     3.70 | abby, empathy, Florence, Lx, madss |
|           18 |     1550 | 2024-06-04 | Nouns            | L   | 0.782      | -            | -                | -                | -         |    -4.50 | abby, empathy, Florence, Lx, madss |
|           17 |     1552 | 2024-06-04 | Homyno           | L   | 0.781      | -            | -                | -                | -         |   -12.55 | abby, empathy, Florence, Lx, madss |
|           16 |     1659 | 2024-05-31 | NAVI Javelins    | L   | 0.756      | -            | -                | -                | -         |    -7.50 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1665 | 2024-05-31 | panelinha        | L   | 0.755      | -            | -                | -                | -         |    -7.67 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1779 | 2024-05-26 | FlyQuest RED     | L   | 0.722      | -            | -                | -                | -         |   -10.48 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1780 | 2024-05-26 | Karma            | W   | 0.721      | 0.303        | 0.004 (0.001)    | 0.068 (0.015)    | 0 (0.000) |     9.18 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2378 | 2024-05-05 | Lotus fe         | W   | 0.582      | 0.250        | 0.004 (0.001)    | 0.037 (0.005)    | 0 (0.000) |     7.21 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2734 | 2024-04-19 | Limitless Angels | W   | 0.476      | 0.322        | 0.003 (0.000)    | 0.045 (0.007)    | 0 (0.000) |     5.88 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2912 | 2024-04-14 | FlyQuest RED     | L   | 0.442      | -            | -                | -                | -         |    -6.59 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2959 | 2024-04-11 | COVEN            | W   | 0.423      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     3.17 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3126 | 2024-04-07 | Limitless Angels | W   | 0.396      | 0.250        | 0.003 (0.000)    | 0.045 (0.004)    | 0 (0.000) |     4.90 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3224 | 2024-04-03 | WG Bandits       | W   | 0.369      | 0.322        | 0.002 (0.000)    | 0.020 (0.002)    | 0 (0.000) |     4.16 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3357 | 2024-03-27 | cleanup crew fe  | W   | 0.323      | 0.322        | -                | 0.020 (0.002)    | 0 (0.000) |     3.94 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3452 | 2024-03-21 | Karma            | W   | 0.283      | 0.322        | 0.004 (0.000)    | 0.068 (0.006)    | -         |     3.76 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3596 | 2024-03-14 | Nouns fe         | W   | 0.236      | 0.322        | 0.003 (0.000)    | 0.032 (0.002)    | -         |     3.11 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3806 | 2024-03-06 | FlyQuest RED     | L   | 0.183      | -            | -                | -                | -         |    -2.74 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3890 | 2024-03-03 | FlyQuest RED     | L   | 0.162      | -            | -                | -                | -         |    -2.47 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4030 | 2024-02-25 | FlyQuest RED     | L   | 0.116      | -            | -                | -                | -         |    -1.78 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,466.93)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.862 | $750.00        | $646.84         |
| 2024-06-02 |      0.769 | $4,000.00      | $3,074.07       |
| 2024-05-26 |      0.722 | $1,500.00      | $1,082.29       |
| 2024-05-05 |      0.582 | $750.00        | $436.84         |
| 2024-04-14 |      0.442 | $250.00        | $110.53         |
| 2024-04-07 |      0.396 | $750.00        | $296.81         |
| 2024-03-03 |      0.162 | $250.00        | $40.61          |
| 2024-02-25 |      0.116 | $250.00        | $28.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />