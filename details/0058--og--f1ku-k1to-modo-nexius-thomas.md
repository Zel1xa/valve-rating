### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1008.9<br />
<br />
Final Rank Value (1008.9) = Starting Rank Value (997.8) + Head To Head Adjustments (11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.539[<sup>1</sup>](#table2)
- Bounty Collected: 0.424[<sup>2</sup>](#table1)
- Opponent Network: 0.085[<sup>2</sup>](#table1)
- LAN Wins: 0.122[<sup>2</sup>](#table1)

The average of these factors is 0.292<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 997.8
- 400 + ( ( 0.292 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 997.8


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
|           25 |      183 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.43 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      219 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1630 | 2024-05-30 | Chinggis Warriors | L   | 0.760      | -            | -                | -                | -         |   -19.82 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1658 | 2024-05-29 | ATOX              | L   | 0.752      | -            | -                | -                | -         |   -17.15 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1917 | 2024-05-19 | paiN              | L   | 0.687      | -            | -                | -                | -         |    -2.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1925 | 2024-05-18 | Liquid            | L   | 0.683      | -            | -                | -                | -         |    -1.58 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2391 | 2024-05-01 | Insilio           | L   | 0.569      | -            | -                | -                | -         |   -12.10 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2420 | 2024-04-30 | Sashi             | L   | 0.561      | -            | -                | -                | -         |    -6.29 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2642 | 2024-04-20 | MIBR              | L   | 0.494      | -            | -                | -                | -         |    -1.57 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2657 | 2024-04-19 | 9z                | W   | 0.491      | 0.589        | 0.406 (0.117)    | 0.619 (0.179)    | 1 (0.491) |    14.45 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2668 | 2024-04-19 | Monte             | W   | 0.489      | 0.589        | 0.059 (0.017)    | 0.161 (0.046)    | 1 (0.489) |     6.60 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2712 | 2024-04-18 | MIBR              | L   | 0.483      | -            | -                | -                | -         |    -1.56 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2841 | 2024-04-14 | Aurora            | L   | 0.455      | -            | -                | -                | -         |    -0.52 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2850 | 2024-04-13 | BetBoom           | W   | 0.449      | 0.684        | 0.251 (0.077)    | 0.542 (0.166)    | 0 (0.000) |    12.51 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2859 | 2024-04-13 | BIG               | W   | 0.447      | 0.684        | 0.155 (0.047)    | 0.304 (0.093)    | 0 (0.000) |    11.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2872 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.441      | 0.684        | 0.222 (0.067)    | 0.553 (0.167)    | 0 (0.000) |    13.48 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     2944 | 2024-04-10 | ENCE              | W   | 0.428      | 0.684        | 0.169 (0.049)    | 0.400 (0.117)    | 0 (0.000) |    12.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3022 | 2024-04-08 | Aurora            | L   | 0.415      | -            | -                | -                | -         |    -0.34 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3644 | 2024-03-10 | SAW               | L   | 0.222      | -            | -                | -                | -         |    -1.95 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3669 | 2024-03-09 | HEROIC            | W   | 0.215      | 0.535        | 0.229 (0.026)    | 0.374 (0.043)    | 0 (0.000) |     6.48 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3712 | 2024-03-07 | Complexity        | W   | 0.202      | 0.535        | 0.310 (0.034)    | 0.380 (0.041)    | 0 (0.000) |     6.21 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4053 | 2024-02-21 | GamerLegion       | L   | 0.101      | -            | -                | -                | -         |    -2.46 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4086 | 2024-02-20 | Gaimin Gladiators | L   | 0.094      | -            | -                | -                | -         |    -1.61 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4103 | 2024-02-19 | ex-Preasy         | W   | 0.089      | 0.143        | 0.012 (0.000)    | 0.113 (0.001)    | 1 (0.089) |     0.64 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4110 | 2024-02-19 | Apeks             | L   | 0.087      | -            | -                | -                | -         |    -1.74 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,140.91)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.575 | $1,000.00      | $575.00         |
| 2024-04-20 |      0.496 | $10,000.00     | $4,962.96       |
| 2024-04-14 |      0.455 | $70,000.00     | $31,820.83      |
| 2024-03-10 |      0.223 | $12,500.00     | $2,782.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
