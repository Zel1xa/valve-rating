### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1012.8<br />
<br />
Final Rank Value (1012.8) = Starting Rank Value (994.9) + Head To Head Adjustments (17.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.536[<sup>1</sup>](#table2)
- Bounty Collected: 0.422[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.118[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 994.9
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 994.9


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
|           25 |      259 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.40 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      294 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.20 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1706 | 2024-05-30 | Chinggis Warriors | L   | 0.746      | -            | -                | -                | -         |   -12.93 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1734 | 2024-05-29 | ATOX              | L   | 0.738      | -            | -                | -                | -         |   -16.70 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1993 | 2024-05-19 | paiN              | L   | 0.672      | -            | -                | -                | -         |    -2.87 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     2001 | 2024-05-18 | Liquid            | L   | 0.668      | -            | -                | -                | -         |    -0.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2467 | 2024-05-01 | Insilio           | L   | 0.554      | -            | -                | -                | -         |   -11.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2496 | 2024-04-30 | Sashi             | L   | 0.547      | -            | -                | -                | -         |    -5.96 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2718 | 2024-04-20 | MIBR              | L   | 0.480      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2733 | 2024-04-19 | 9z                | W   | 0.476      | 0.589        | 0.404 (0.113)    | 0.591 (0.166)    | 1 (0.476) |    14.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2744 | 2024-04-19 | Monte             | W   | 0.475      | 0.589        | 0.057 (0.016)    | 0.149 (0.042)    | 1 (0.475) |     6.38 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2788 | 2024-04-18 | MIBR              | L   | 0.468      | -            | -                | -                | -         |    -1.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2917 | 2024-04-14 | Aurora            | L   | 0.440      | -            | -                | -                | -         |    -0.46 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2926 | 2024-04-13 | BetBoom           | W   | 0.434      | 0.684        | 0.248 (0.074)    | 0.513 (0.153)    | 0 (0.000) |    12.11 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2935 | 2024-04-13 | BIG               | W   | 0.433      | 0.684        | 0.154 (0.046)    | 0.290 (0.086)    | 0 (0.000) |    11.19 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2948 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.426      | 0.684        | 0.253 (0.074)    | 0.531 (0.155)    | 0 (0.000) |    13.06 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3020 | 2024-04-10 | ENCE              | W   | 0.413      | 0.684        | 0.173 (0.049)    | 0.422 (0.119)    | 0 (0.000) |    12.01 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3098 | 2024-04-08 | Aurora            | L   | 0.401      | -            | -                | -                | -         |    -0.30 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3720 | 2024-03-10 | SAW               | L   | 0.207      | -            | -                | -                | -         |    -1.84 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3745 | 2024-03-09 | HEROIC            | W   | 0.200      | 0.535        | 0.224 (0.024)    | 0.354 (0.038)    | 0 (0.000) |     6.04 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3788 | 2024-03-07 | Complexity        | W   | 0.188      | 0.535        | 0.341 (0.034)    | 0.364 (0.037)    | 0 (0.000) |     5.77 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4129 | 2024-02-21 | GamerLegion       | L   | 0.087      | -            | -                | -                | -         |    -2.12 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4162 | 2024-02-20 | Gaimin Gladiators | L   | 0.079      | -            | -                | -                | -         |    -1.37 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4179 | 2024-02-19 | ex-Preasy         | W   | 0.074      | 0.143        | 0.011 (0.000)    | 0.102 (0.001)    | 1 (0.074) |     0.53 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4186 | 2024-02-19 | Apeks             | L   | 0.073      | -            | -                | -                | -         |    -1.45 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,781.70)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.560 | $1,000.00      | $560.46         |
| 2024-04-20 |      0.482 | $10,000.00     | $4,817.59       |
| 2024-04-14 |      0.440 | $70,000.00     | $30,803.24      |
| 2024-03-10 |      0.208 | $12,500.00     | $2,600.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
