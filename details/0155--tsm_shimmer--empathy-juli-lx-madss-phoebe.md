### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [155](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [43]( ../standings_americas.md)<br />
<br />
Final Rank Value:  695.9<br />
<br />
Final Rank Value (695.9) = Starting Rank Value (716.2) + Head To Head Adjustments (-20.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.372[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.2
- 400 + ( ( 0.153 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 716.2


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
|           24 |      111 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.004 (0.001)    | 0.037 (0.009)    | 0 (0.000) |    12.60 | empathy, Juli, Lx, madss, phoebe   |
|           23 |      839 | 2024-06-16 | Lotus fe         | W   | 0.901      | 0.250        | 0.005 (0.001)    | 0.038 (0.009)    | 0 (0.000) |    12.56 | abby, empathy, Juli, Lx, madss     |
|           22 |     1064 | 2024-06-09 | Perseverance     | L   | 0.853      | -            | -                | -                | -         |   -18.82 | abby, empathy, Florence, Lx, madss |
|           21 |     1166 | 2024-06-07 | Zomblers         | L   | 0.842      | -            | -                | -                | -         |   -19.53 | abby, empathy, Florence, Lx, madss |
|           20 |     1314 | 2024-06-05 | Asian Kings      | W   | 0.826      | -            | -                | -                | 0 (0.000) |     3.82 | abby, empathy, Florence, Lx, madss |
|           19 |     1357 | 2024-06-04 | Nouns            | L   | 0.820      | -            | -                | -                | -         |    -4.67 | abby, empathy, Florence, Lx, madss |
|           18 |     1359 | 2024-06-04 | Homyno           | L   | 0.819      | -            | -                | -                | -         |   -13.14 | abby, empathy, Florence, Lx, madss |
|           17 |     1466 | 2024-05-31 | NAVI Javelins    | L   | 0.794      | -            | -                | -                | -         |    -7.72 | abby, empathy, Lx, madss, phoebe   |
|           16 |     1472 | 2024-05-31 | panelinha        | L   | 0.793      | -            | -                | -                | -         |    -7.88 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1586 | 2024-05-26 | FlyQuest RED     | L   | 0.760      | -            | -                | -                | -         |   -10.87 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1587 | 2024-05-26 | Karma            | W   | 0.760      | 0.303        | 0.004 (0.001)    | 0.075 (0.017)    | 0 (0.000) |     9.66 | abby, empathy, Lx, madss, phoebe   |
|           13 |     2185 | 2024-05-05 | Lotus fe         | W   | 0.621      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.61 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2541 | 2024-04-19 | Limitless Angels | W   | 0.514      | 0.322        | 0.003 (0.000)    | 0.051 (0.008)    | 0 (0.000) |     6.35 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2719 | 2024-04-14 | FlyQuest RED     | L   | 0.480      | -            | -                | -                | -         |    -7.06 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2766 | 2024-04-11 | COVEN            | W   | 0.461      | 0.322        | 0.002 (0.000)    | -                | 0 (0.000) |     3.39 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2933 | 2024-04-07 | Limitless Angels | W   | 0.434      | 0.250        | 0.003 (0.000)    | 0.051 (0.006)    | 0 (0.000) |     5.37 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3031 | 2024-04-03 | WG Bandits       | W   | 0.408      | 0.322        | 0.002 (0.000)    | 0.023 (0.003)    | 0 (0.000) |     4.56 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3164 | 2024-03-27 | cleanup crew fe  | W   | 0.361      | 0.322        | -                | 0.023 (0.003)    | 0 (0.000) |     4.41 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3259 | 2024-03-21 | Karma            | W   | 0.321      | 0.322        | 0.004 (0.000)    | 0.075 (0.008)    | -         |     4.28 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3403 | 2024-03-14 | Nouns fe         | W   | 0.274      | 0.322        | 0.004 (0.000)    | 0.037 (0.003)    | -         |     3.64 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3613 | 2024-03-06 | FlyQuest RED     | L   | 0.221      | -            | -                | -                | -         |    -3.27 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3697 | 2024-03-03 | FlyQuest RED     | L   | 0.201      | -            | -                | -                | -         |    -3.02 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3837 | 2024-02-25 | FlyQuest RED     | L   | 0.154      | -            | -                | -                | -         |    -2.35 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4255 | 2024-02-04 | FlyQuest RED     | L   | 0.014      | -            | -                | -                | -         |    -0.22 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,796.17)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.901 | $750.00        | $675.58         |
| 2024-06-02 |      0.807 | $4,000.00      | $3,227.35       |
| 2024-05-26 |      0.760 | $1,500.00      | $1,139.77       |
| 2024-05-05 |      0.621 | $750.00        | $465.58         |
| 2024-04-14 |      0.480 | $250.00        | $120.11         |
| 2024-04-07 |      0.434 | $750.00        | $325.55         |
| 2024-03-03 |      0.201 | $250.00        | $50.19          |
| 2024-02-25 |      0.154 | $250.00        | $38.52          |
| 2024-02-04 |      0.014 | $250.00        | $3.53           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
