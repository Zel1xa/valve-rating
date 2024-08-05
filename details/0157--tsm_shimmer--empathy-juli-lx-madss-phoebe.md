### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: empathy, Juli, Lx, madss, phoebe<br />
Global Rank: [157](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.5<br />
<br />
Final Rank Value (693.5) = Starting Rank Value (712.7) + Head To Head Adjustments (-19.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.371[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.7
- 400 + ( ( 0.152 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 712.7


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
|           23 |      286 | 2024-07-28 | Nouns fe         | W   | 1.000      | 0.250        | 0.003 (0.001)    | 0.034 (0.008)    | 0 (0.000) |    12.61 | empathy, Juli, Lx, madss, phoebe   |
|           22 |     1014 | 2024-06-16 | Lotus fe         | W   | 0.868      | 0.250        | 0.005 (0.001)    | 0.038 (0.008)    | 0 (0.000) |    12.15 | abby, empathy, Juli, Lx, madss     |
|           21 |     1239 | 2024-06-09 | Perseverance     | L   | 0.820      | -            | -                | -                | -         |   -18.07 | abby, empathy, Florence, Lx, madss |
|           20 |     1341 | 2024-06-07 | Zomblers         | L   | 0.809      | -            | -                | -                | -         |   -18.73 | abby, empathy, Florence, Lx, madss |
|           19 |     1489 | 2024-06-05 | Asian Kings      | W   | 0.793      | -            | -                | -                | 0 (0.000) |     3.73 | abby, empathy, Florence, Lx, madss |
|           18 |     1532 | 2024-06-04 | Nouns            | L   | 0.787      | -            | -                | -                | -         |    -4.50 | abby, empathy, Florence, Lx, madss |
|           17 |     1534 | 2024-06-04 | Homyno           | L   | 0.787      | -            | -                | -                | -         |   -12.62 | abby, empathy, Florence, Lx, madss |
|           16 |     1641 | 2024-05-31 | NAVI Javelins    | L   | 0.762      | -            | -                | -                | -         |    -7.54 | abby, empathy, Lx, madss, phoebe   |
|           15 |     1647 | 2024-05-31 | panelinha        | L   | 0.760      | -            | -                | -                | -         |    -7.72 | abby, empathy, Lx, madss, phoebe   |
|           14 |     1761 | 2024-05-26 | FlyQuest RED     | L   | 0.727      | -            | -                | -                | -         |   -10.54 | abby, empathy, Lx, madss, phoebe   |
|           13 |     1762 | 2024-05-26 | Karma            | W   | 0.727      | 0.303        | 0.004 (0.001)    | 0.070 (0.016)    | 0 (0.000) |     9.26 | abby, empathy, Lx, madss, phoebe   |
|           12 |     2360 | 2024-05-05 | Lotus fe         | W   | 0.588      | 0.250        | 0.005 (0.001)    | 0.038 (0.006)    | 0 (0.000) |     7.27 | abby, empathy, Lx, madss, phoebe   |
|           11 |     2716 | 2024-04-19 | Limitless Angels | W   | 0.482      | 0.322        | 0.003 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     5.95 | abby, empathy, Lx, madss, phoebe   |
|           10 |     2894 | 2024-04-14 | FlyQuest RED     | L   | 0.448      | -            | -                | -                | -         |    -6.66 | abby, empathy, Lx, madss, phoebe   |
|            9 |     2941 | 2024-04-11 | COVEN            | W   | 0.428      | 0.322        | 0.001 (0.000)    | -                | 0 (0.000) |     3.21 | abby, empathy, Lx, madss, phoebe   |
|            8 |     3108 | 2024-04-07 | Limitless Angels | W   | 0.401      | 0.250        | 0.003 (0.000)    | 0.047 (0.005)    | 0 (0.000) |     4.97 | abby, empathy, Lx, madss, phoebe   |
|            7 |     3206 | 2024-04-03 | WG Bandits       | W   | 0.375      | 0.322        | 0.002 (0.000)    | 0.020 (0.002)    | 0 (0.000) |     4.22 | abby, empathy, Lx, madss, phoebe   |
|            6 |     3339 | 2024-03-27 | cleanup crew fe  | W   | 0.328      | 0.322        | -                | 0.020 (0.002)    | 0 (0.000) |     4.01 | abby, empathy, Lx, madss, phoebe   |
|            5 |     3434 | 2024-03-21 | Karma            | W   | 0.288      | 0.322        | 0.004 (0.000)    | 0.070 (0.007)    | -         |     3.84 | abby, empathy, Lx, madss, phoebe   |
|            4 |     3578 | 2024-03-14 | Nouns fe         | W   | 0.242      | 0.322        | 0.003 (0.000)    | 0.034 (0.003)    | -         |     3.19 | abby, empathy, Lx, madss, phoebe   |
|            3 |     3788 | 2024-03-06 | FlyQuest RED     | L   | 0.189      | -            | -                | -                | -         |    -2.82 | abby, empathy, Lx, madss, phoebe   |
|            2 |     3872 | 2024-03-03 | FlyQuest RED     | L   | 0.168      | -            | -                | -                | -         |    -2.55 | abby, empathy, Lx, madss, phoebe   |
|            1 |     4012 | 2024-02-25 | FlyQuest RED     | L   | 0.121      | -            | -                | -                | -         |    -1.86 | abby, empathy, Lx, madss, phoebe   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,513.76)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $750.00        | $750.00         |
| 2024-06-16 |      0.868 | $750.00        | $650.97         |
| 2024-06-02 |      0.774 | $4,000.00      | $3,096.11       |
| 2024-05-26 |      0.727 | $1,500.00      | $1,090.56       |
| 2024-05-05 |      0.588 | $750.00        | $440.97         |
| 2024-04-14 |      0.448 | $250.00        | $111.91         |
| 2024-04-07 |      0.401 | $750.00        | $300.94         |
| 2024-03-03 |      0.168 | $250.00        | $41.98          |
| 2024-02-25 |      0.121 | $250.00        | $30.31          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
