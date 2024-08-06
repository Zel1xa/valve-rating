### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1007.9<br />
<br />
Final Rank Value (1007.9) = Starting Rank Value (995.0) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.290<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.0
- 400 + ( ( 0.290 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 995.0


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
|           25 |      247 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      282 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1694 | 2024-05-30 | Chinggis Warriors | L   | 0.747      | -            | -                | -                | -         |   -17.93 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1722 | 2024-05-29 | ATOX              | L   | 0.739      | -            | -                | -                | -         |   -16.75 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1981 | 2024-05-19 | paiN              | L   | 0.673      | -            | -                | -                | -         |    -2.86 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1989 | 2024-05-18 | Liquid            | L   | 0.669      | -            | -                | -                | -         |    -0.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2455 | 2024-05-01 | Insilio           | L   | 0.555      | -            | -                | -                | -         |   -11.64 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2484 | 2024-04-30 | Sashi             | L   | 0.548      | -            | -                | -                | -         |    -6.00 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2706 | 2024-04-20 | MIBR              | L   | 0.481      | -            | -                | -                | -         |    -1.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2721 | 2024-04-19 | 9z                | W   | 0.478      | 0.589        | 0.404 (0.114)    | 0.604 (0.170)    | 1 (0.478) |    14.08 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2732 | 2024-04-19 | Monte             | W   | 0.476      | 0.589        | 0.057 (0.016)    | 0.153 (0.043)    | 1 (0.476) |     6.37 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2776 | 2024-04-18 | MIBR              | L   | 0.470      | -            | -                | -                | -         |    -1.53 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2905 | 2024-04-14 | Aurora            | L   | 0.441      | -            | -                | -                | -         |    -0.47 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2914 | 2024-04-13 | BetBoom           | W   | 0.435      | 0.684        | 0.248 (0.074)    | 0.526 (0.157)    | 0 (0.000) |    12.14 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2923 | 2024-04-13 | BIG               | W   | 0.434      | 0.684        | 0.154 (0.046)    | 0.297 (0.088)    | 0 (0.000) |    11.21 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2936 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.428      | 0.684        | 0.254 (0.074)    | 0.543 (0.159)    | 0 (0.000) |    13.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3008 | 2024-04-10 | ENCE              | W   | 0.414      | 0.684        | 0.173 (0.049)    | 0.431 (0.122)    | 0 (0.000) |    12.04 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3086 | 2024-04-08 | Aurora            | L   | 0.402      | -            | -                | -                | -         |    -0.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3708 | 2024-03-10 | SAW               | L   | 0.209      | -            | -                | -                | -         |    -1.84 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3733 | 2024-03-09 | HEROIC            | W   | 0.201      | 0.535        | 0.225 (0.024)    | 0.363 (0.039)    | 0 (0.000) |     6.08 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3776 | 2024-03-07 | Complexity        | W   | 0.189      | 0.535        | 0.341 (0.034)    | 0.372 (0.038)    | 0 (0.000) |     5.81 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4117 | 2024-02-21 | GamerLegion       | L   | 0.088      | -            | -                | -                | -         |    -2.15 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4150 | 2024-02-20 | Gaimin Gladiators | L   | 0.080      | -            | -                | -                | -         |    -1.39 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4167 | 2024-02-19 | ex-Preasy         | W   | 0.075      | 0.143        | 0.011 (0.000)    | 0.105 (0.001)    | 1 (0.075) |     0.54 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4174 | 2024-02-19 | Apeks             | L   | 0.074      | -            | -                | -                | -         |    -1.48 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,894.25)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.562 | $1,000.00      | $561.67         |
| 2024-04-20 |      0.483 | $10,000.00     | $4,829.63       |
| 2024-04-14 |      0.441 | $70,000.00     | $30,887.50      |
| 2024-03-10 |      0.209 | $12,500.00     | $2,615.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
