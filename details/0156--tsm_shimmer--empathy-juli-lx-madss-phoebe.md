### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  694.1<br />
<br />
Final Rank Value (694.1) = Starting Rank Value (713.3) + Head To Head Adjustments (-19.2)<br />

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
|           23 |      296 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.032 (0.008)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |     1024 | 2024-06-16 | Lotus fe         | W   | 0.863      | 0.250        | 0.004 (0.001)    | 0.037 (0.008)    | 0 (0.000) |    12.09 | abby, empathy, Juli, Lx, madss     |
|           21 |     1249 | 2024-06-09 | Perseverance     | L   | 0.815      | -            | -                | -                | -         |   -17.99 | abby, empathy, Florence, Lx, madss |
|           20 |     1351 | 2024-06-07 | Zomblers         | L   | 0.804      | -            | -                | -                | -         |   -18.64 | abby, empathy, Florence, Lx, madss |
|           19 |     1499 | 2024-06-05 | Asian Kings      | W   | 0.788      | -            | -                | -                | 0 (0.000) |     3.70 | abby, empathy, Florence, Lx, madss |
|           18 |     1542 | 2024-06-04 | Nouns            | L   | 0.783      | -            | -                | -                | -         |    -4.51 | abby, empathy, Florence, Lx, madss |
|           17 |     1544 | 2024-06-04 | Homyno           | L   | 0.782      | -            | -                | -                | -         |   -12.56 | abby, empathy, Florence, Lx, madss |
|           16 |     1651 | 2024-05-31 | NAVI Javelins    | L   | 0.757      | -            | -                | -                | -         |    -7.51 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1657 | 2024-05-31 | panelinha        | L   | 0.756      | -            | -                | -                | -         |    -7.68 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1771 | 2024-05-26 | FlyQuest RED     | L   | 0.722      | -            | -                | -                | -         |   -10.49 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1772 | 2024-05-26 | Karma            | W   | 0.722      | 0.303        | 0.004 (0.001)    | 0.068 (0.015)    | 0 (0.000) |     9.20 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2370 | 2024-05-05 | Lotus fe         | W   | 0.583      | 0.250        | 0.004 (0.001)    | 0.037 (0.005)    | 0 (0.000) |     7.22 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2726 | 2024-04-19 | Limitless Angels | W   | 0.477      | 0.322        | 0.003 (0.000)    | 0.045 (0.007)    | 0 (0.000) |     5.89 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2904 | 2024-04-14 | FlyQuest RED     | L   | 0.443      | -            | -                | -                | -         |    -6.60 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2951 | 2024-04-11 | COVEN            | W   | 0.423      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     3.18 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3118 | 2024-04-07 | Limitless Angels | W   | 0.397      | 0.250        | 0.003 (0.000)    | 0.045 (0.004)    | 0 (0.000) |     4.91 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3216 | 2024-04-03 | WG Bandits       | W   | 0.370      | 0.322        | 0.002 (0.000)    | 0.020 (0.002)    | 0 (0.000) |     4.17 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3349 | 2024-03-27 | cleanup crew fe  | W   | 0.324      | 0.322        | -                | 0.020 (0.002)    | 0 (0.000) |     3.95 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3444 | 2024-03-21 | Karma            | W   | 0.284      | 0.322        | 0.004 (0.000)    | 0.068 (0.006)    | -         |     3.77 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3588 | 2024-03-14 | Nouns fe         | W   | 0.237      | 0.322        | 0.003 (0.000)    | 0.032 (0.002)    | -         |     3.12 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3798 | 2024-03-06 | FlyQuest RED     | L   | 0.184      | -            | -                | -                | -         |    -2.75 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3882 | 2024-03-03 | FlyQuest RED     | L   | 0.163      | -            | -                | -                | -         |    -2.48 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4022 | 2024-02-25 | FlyQuest RED     | L   | 0.117      | -            | -                | -                | -         |    -1.79 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,474.80)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.863 | $750.00        | $647.53         |
| 2024-06-02 |      0.769 | $4,000.00      | $3,077.78       |
| 2024-05-26 |      0.722 | $1,500.00      | $1,083.68       |
| 2024-05-05 |      0.583 | $750.00        | $437.53         |
| 2024-04-14 |      0.443 | $250.00        | $110.76         |
| 2024-04-07 |      0.397 | $750.00        | $297.50         |
| 2024-03-03 |      0.163 | $250.00        | $40.84          |
| 2024-02-25 |      0.117 | $250.00        | $29.17          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />