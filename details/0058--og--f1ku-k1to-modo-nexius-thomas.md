### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1009.6<br />
<br />
Final Rank Value (1009.6) = Starting Rank Value (996.6) + Head To Head Adjustments (13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.6
- 400 + ( ( 0.291 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 996.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      241 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      276 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1688 | 2024-05-30 | Chinggis Warriors | L   | 0.751      | -            | -                | -                | -         |   -18.07 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1716 | 2024-05-29 | ATOX              | L   | 0.743      | -            | -                | -                | -         |   -16.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1975 | 2024-05-19 | paiN              | L   | 0.677      | -            | -                | -                | -         |    -2.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1983 | 2024-05-18 | Liquid            | L   | 0.674      | -            | -                | -                | -         |    -1.00 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2449 | 2024-05-01 | Insilio           | L   | 0.560      | -            | -                | -                | -         |   -11.78 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2478 | 2024-04-30 | Sashi             | L   | 0.552      | -            | -                | -                | -         |    -6.08 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2700 | 2024-04-20 | MIBR              | L   | 0.485      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2715 | 2024-04-19 | 9z                | W   | 0.482      | 0.589        | 0.404 (0.115)    | 0.607 (0.172)    | 1 (0.482) |    14.20 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2726 | 2024-04-19 | Monte             | W   | 0.480      | 0.589        | 0.057 (0.016)    | 0.155 (0.044)    | 1 (0.480) |     6.42 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2770 | 2024-04-18 | MIBR              | L   | 0.474      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2899 | 2024-04-14 | Aurora            | L   | 0.446      | -            | -                | -                | -         |    -0.49 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2908 | 2024-04-13 | BetBoom           | W   | 0.440      | 0.684        | 0.249 (0.075)    | 0.529 (0.159)    | 0 (0.000) |    12.26 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2917 | 2024-04-13 | BIG               | W   | 0.438      | 0.684        | 0.154 (0.046)    | 0.298 (0.089)    | 0 (0.000) |    11.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2930 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.432      | 0.684        | 0.254 (0.075)    | 0.544 (0.161)    | 0 (0.000) |    13.23 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3002 | 2024-04-10 | ENCE              | W   | 0.419      | 0.684        | 0.174 (0.050)    | 0.432 (0.124)    | 0 (0.000) |    12.15 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3080 | 2024-04-08 | Aurora            | L   | 0.406      | -            | -                | -                | -         |    -0.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3702 | 2024-03-10 | SAW               | L   | 0.213      | -            | -                | -                | -         |    -1.87 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3727 | 2024-03-09 | HEROIC            | W   | 0.206      | 0.535        | 0.225 (0.025)    | 0.365 (0.040)    | 0 (0.000) |     6.21 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3770 | 2024-03-07 | Complexity        | W   | 0.193      | 0.535        | 0.342 (0.035)    | 0.373 (0.039)    | 0 (0.000) |     5.94 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4111 | 2024-02-21 | GamerLegion       | L   | 0.092      | -            | -                | -                | -         |    -2.25 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4144 | 2024-02-20 | Gaimin Gladiators | L   | 0.085      | -            | -                | -                | -         |    -1.46 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4161 | 2024-02-19 | ex-Preasy         | W   | 0.080      | 0.143        | 0.012 (0.000)    | 0.107 (0.001)    | 1 (0.080) |     0.57 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4168 | 2024-02-19 | Apeks             | L   | 0.078      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,296.82)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.566 | $1,000.00      | $565.97         |
| 2024-04-20 |      0.487 | $10,000.00     | $4,872.69       |
| 2024-04-14 |      0.446 | $70,000.00     | $31,188.89      |
| 2024-03-10 |      0.214 | $12,500.00     | $2,669.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
