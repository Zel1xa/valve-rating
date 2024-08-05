### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1009.8<br />
<br />
Final Rank Value (1009.8) = Starting Rank Value (996.8) + Head To Head Adjustments (13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.120[<sup>2</sup>](#table1)

The average of these factors is 0.291<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 996.8
- 400 + ( ( 0.291 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 996.8


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
|           25 |      232 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      267 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1679 | 2024-05-30 | Chinggis Warriors | L   | 0.753      | -            | -                | -                | -         |   -18.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1707 | 2024-05-29 | ATOX              | L   | 0.745      | -            | -                | -                | -         |   -16.92 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1966 | 2024-05-19 | paiN              | L   | 0.679      | -            | -                | -                | -         |    -2.87 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1974 | 2024-05-18 | Liquid            | L   | 0.675      | -            | -                | -                | -         |    -1.01 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2440 | 2024-05-01 | Insilio           | L   | 0.561      | -            | -                | -                | -         |   -11.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2469 | 2024-04-30 | Sashi             | L   | 0.554      | -            | -                | -                | -         |    -6.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2691 | 2024-04-20 | MIBR              | L   | 0.487      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2706 | 2024-04-19 | 9z                | W   | 0.483      | 0.589        | 0.405 (0.115)    | 0.615 (0.175)    | 1 (0.483) |    14.24 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2717 | 2024-04-19 | Monte             | W   | 0.482      | 0.589        | 0.057 (0.016)    | 0.157 (0.045)    | 1 (0.482) |     6.44 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2761 | 2024-04-18 | MIBR              | L   | 0.475      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2890 | 2024-04-14 | Aurora            | L   | 0.447      | -            | -                | -                | -         |    -0.50 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2899 | 2024-04-13 | BetBoom           | W   | 0.441      | 0.684        | 0.249 (0.075)    | 0.536 (0.162)    | 0 (0.000) |    12.31 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2908 | 2024-04-13 | BIG               | W   | 0.440      | 0.684        | 0.155 (0.046)    | 0.302 (0.091)    | 0 (0.000) |    11.35 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2921 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.433      | 0.684        | 0.254 (0.075)    | 0.551 (0.163)    | 0 (0.000) |    13.28 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2993 | 2024-04-10 | ENCE              | W   | 0.420      | 0.684        | 0.168 (0.048)    | 0.438 (0.126)    | 0 (0.000) |    12.18 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3071 | 2024-04-08 | Aurora            | L   | 0.408      | -            | -                | -                | -         |    -0.32 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3693 | 2024-03-10 | SAW               | L   | 0.214      | -            | -                | -                | -         |    -1.88 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3718 | 2024-03-09 | HEROIC            | W   | 0.207      | 0.535        | 0.225 (0.025)    | 0.370 (0.041)    | 0 (0.000) |     6.26 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3761 | 2024-03-07 | Complexity        | W   | 0.195      | 0.535        | 0.342 (0.036)    | 0.378 (0.039)    | 0 (0.000) |     5.99 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4102 | 2024-02-21 | GamerLegion       | L   | 0.094      | -            | -                | -                | -         |    -2.29 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4135 | 2024-02-20 | Gaimin Gladiators | L   | 0.086      | -            | -                | -                | -         |    -1.49 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4152 | 2024-02-19 | ex-Preasy         | W   | 0.081      | 0.143        | 0.012 (0.000)    | 0.109 (0.001)    | 1 (0.081) |     0.58 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4159 | 2024-02-19 | Apeks             | L   | 0.080      | -            | -                | -                | -         |    -1.59 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,439.66)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.568 | $1,000.00      | $567.50         |
| 2024-04-20 |      0.489 | $10,000.00     | $4,887.96       |
| 2024-04-14 |      0.447 | $70,000.00     | $31,295.83      |
| 2024-03-10 |      0.215 | $12,500.00     | $2,688.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
