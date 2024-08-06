### Roster Details<br />
Team Name: OG<br />
Roster: F1KU, k1to, MoDo, Nexius, Thomas<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1008.1<br />
<br />
Final Rank Value (1008.1) = Starting Rank Value (995.1) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.537[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.080[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 995.1
- 400 + ( ( 0.289 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 995.1


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
|           25 |      254 | 2024-07-30 | Complexity        | L   | 1.000      | -            | -                | -                | -         |    -1.37 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           24 |      289 | 2024-07-29 | Spirit            | L   | 1.000      | -            | -                | -                | -         |    -0.19 | F1KU, k1to, MoDo, Nexius, Thomas     |
|           23 |     1701 | 2024-05-30 | Chinggis Warriors | L   | 0.746      | -            | -                | -                | -         |   -17.90 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           22 |     1729 | 2024-05-29 | ATOX              | L   | 0.739      | -            | -                | -                | -         |   -16.72 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           21 |     1988 | 2024-05-19 | paiN              | L   | 0.673      | -            | -                | -                | -         |    -2.88 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           20 |     1996 | 2024-05-18 | Liquid            | L   | 0.669      | -            | -                | -                | -         |    -0.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           19 |     2462 | 2024-05-01 | Insilio           | L   | 0.555      | -            | -                | -                | -         |   -11.63 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           18 |     2491 | 2024-04-30 | Sashi             | L   | 0.547      | -            | -                | -                | -         |    -5.99 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           17 |     2713 | 2024-04-20 | MIBR              | L   | 0.480      | -            | -                | -                | -         |    -1.55 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           16 |     2728 | 2024-04-19 | 9z                | W   | 0.477      | 0.589        | 0.404 (0.113)    | 0.591 (0.166)    | 1 (0.477) |    14.05 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           15 |     2739 | 2024-04-19 | Monte             | W   | 0.475      | 0.589        | 0.057 (0.016)    | 0.149 (0.042)    | 1 (0.475) |     6.39 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           14 |     2783 | 2024-04-18 | MIBR              | L   | 0.469      | -            | -                | -                | -         |    -1.54 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           13 |     2912 | 2024-04-14 | Aurora            | L   | 0.441      | -            | -                | -                | -         |    -0.47 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           12 |     2921 | 2024-04-13 | BetBoom           | W   | 0.435      | 0.684        | 0.248 (0.074)    | 0.514 (0.153)    | 0 (0.000) |    12.12 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           11 |     2930 | 2024-04-13 | BIG               | W   | 0.433      | 0.684        | 0.154 (0.046)    | 0.290 (0.086)    | 0 (0.000) |    11.20 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|           10 |     2943 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.427      | 0.684        | 0.254 (0.074)    | 0.531 (0.155)    | 0 (0.000) |    13.08 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            9 |     3015 | 2024-04-10 | ENCE              | W   | 0.414      | 0.684        | 0.173 (0.049)    | 0.422 (0.119)    | 0 (0.000) |    12.03 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            8 |     3093 | 2024-04-08 | Aurora            | L   | 0.401      | -            | -                | -                | -         |    -0.30 | F1KU, HeavyGod, k1to, MoDo, Nexius   |
|            7 |     3715 | 2024-03-10 | SAW               | L   | 0.208      | -            | -                | -                | -         |    -1.84 | F1KU, k1to, Nexius, regali, s0und    |
|            6 |     3740 | 2024-03-09 | HEROIC            | W   | 0.201      | 0.535        | 0.224 (0.024)    | 0.355 (0.038)    | 0 (0.000) |     6.06 | F1KU, HeavyGod, k1to, Nexius, regali |
|            5 |     3783 | 2024-03-07 | Complexity        | W   | 0.188      | 0.535        | 0.341 (0.034)    | 0.364 (0.037)    | 0 (0.000) |     5.79 | F1KU, HeavyGod, k1to, Nexius, regali |
|            4 |     4124 | 2024-02-21 | GamerLegion       | L   | 0.087      | -            | -                | -                | -         |    -2.13 | F1KU, HeavyGod, k1to, Nexius, regali |
|            3 |     4157 | 2024-02-20 | Gaimin Gladiators | L   | 0.080      | -            | -                | -                | -         |    -1.38 | F1KU, HeavyGod, k1to, Nexius, regali |
|            2 |     4174 | 2024-02-19 | ex-Preasy         | W   | 0.075      | 0.143        | 0.011 (0.000)    | 0.103 (0.001)    | 1 (0.075) |     0.53 | F1KU, HeavyGod, k1to, Nexius, regali |
|            1 |     4181 | 2024-02-19 | Apeks             | L   | 0.073      | -            | -                | -                | -         |    -1.46 | F1KU, HeavyGod, k1to, Nexius, regali |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,833.65)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-02 |      0.561 | $1,000.00      | $561.02         |
| 2024-04-20 |      0.482 | $10,000.00     | $4,823.15       |
| 2024-04-14 |      0.441 | $70,000.00     | $30,842.13      |
| 2024-03-10 |      0.209 | $12,500.00     | $2,607.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
