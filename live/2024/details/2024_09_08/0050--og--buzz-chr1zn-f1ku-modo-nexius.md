### Roster Details<br />
Team Name: OG<br />
Roster: Buzz, Chr1zN, F1KU, MoDo, Nexius<br />
Global Rank: [50](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [37]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  1026.9<br />
<br />
Final Rank Value (1026.9) = Starting Rank Value (947.7) + Head To Head Adjustments (79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.518[<sup>1</sup>](#table2)
- Bounty Collected: 0.419[<sup>2</sup>](#table1)
- Opponent Network: 0.141[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 947.7
- 400 + ( ( 0.283 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 947.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      218 | 2024-08-31 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -19.15 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           32 |      235 | 2024-08-30 | Endpoint          | W   | 1.000      | 0.384        | 0.065 (0.025)    | 0.723 (0.278)    | 0 (0.000) |    12.09 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           31 |      443 | 2024-08-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           30 |      459 | 2024-08-26 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -2.00 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           29 |      503 | 2024-08-25 | FaZe              | L   | 1.000      | -            | -                | -                | -         |    -0.69 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           28 |      543 | 2024-08-23 | AMKAL             | W   | 1.000      | 0.535        | 0.123 (0.066)    | 0.397 (0.212)    | 0 (0.000) |    14.42 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           27 |      551 | 2024-08-23 | Sashi             | L   | 1.000      | -            | -                | -                | -         |   -13.50 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           26 |      556 | 2024-08-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -13.84 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           25 |      591 | 2024-08-22 | Rebels            | W   | 1.000      | 0.143        | -                | 0.656 (0.094)    | 0 (0.000) |    10.78 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           24 |      620 | 2024-08-21 | HEROIC            | W   | 1.000      | 0.535        | 0.205 (0.110)    | 0.412 (0.220)    | 0 (0.000) |    27.79 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           23 |      628 | 2024-08-21 | Zero Tenacity     | W   | 1.000      | 0.143        | 0.163 (0.023)    | 1.000 (0.143)    | 0 (0.000) |    15.43 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           22 |      665 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.83 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           21 |      810 | 2024-08-15 | B8                | W   | 1.000      | 0.143        | 0.176 (0.025)    | 1.000 (0.143)    | 0 (0.000) |    20.26 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           20 |      815 | 2024-08-15 | PARIVISION        | W   | 1.000      | 0.143        | -                | 0.730 (0.104)    | 0 (0.000) |    22.00 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           19 |      819 | 2024-08-15 | ARCRED            | W   | 1.000      | 0.143        | -                | 0.427 (0.061)    | 0 (0.000) |    16.12 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           18 |     1379 | 2024-07-30 | Complexity        | L   | 0.933      | -            | -                | -                | -         |    -1.55 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           17 |     1414 | 2024-07-29 | Spirit            | L   | 0.926      | -            | -                | -                | -         |    -0.10 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           16 |     2829 | 2024-05-30 | Chinggis Warriors | L   | 0.526      | -            | -                | -                | -         |    -9.80 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           15 |     2857 | 2024-05-29 | ATOX              | L   | 0.518      | -            | -                | -                | -         |   -11.96 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           14 |     3116 | 2024-05-19 | paiN              | L   | 0.452      | -            | -                | -                | -         |    -0.38 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           13 |     3124 | 2024-05-18 | Liquid            | L   | 0.449      | -            | -                | -                | -         |    -0.49 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           12 |     3590 | 2024-05-01 | Insilio           | L   | 0.334      | -            | -                | -                | -         |    -6.22 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           11 |     3619 | 2024-04-30 | Sashi             | L   | 0.327      | -            | -                | -                | -         |    -3.63 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           10 |     3841 | 2024-04-20 | MIBR              | L   | 0.260      | -            | -                | -                | -         |    -0.67 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            9 |     3856 | 2024-04-19 | 9z                | W   | 0.257      | 0.589        | 0.362 (0.055)    | 0.530 (0.080)    | 1 (0.257) |     7.64 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            8 |     3867 | 2024-04-19 | Monte             | W   | 0.255      | -            | -                | -                | 1 (0.255) |     3.78 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            7 |     3911 | 2024-04-18 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -0.67 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            6 |     4040 | 2024-04-14 | Aurora            | L   | 0.220      | -            | -                | -                | -         |    -0.55 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            5 |     4049 | 2024-04-13 | BetBoom           | W   | 0.215      | 0.684        | 0.229 (0.034)    | 0.535 (0.079)    | -         |     5.50 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            4 |     4058 | 2024-04-13 | BIG               | W   | 0.213      | 0.684        | 0.146 (0.021)    | -                | -         |     5.31 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            3 |     4071 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.207      | 0.684        | 0.232 (0.033)    | -                | -         |     6.10 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            2 |     4143 | 2024-04-10 | ENCE              | W   | 0.193      | 0.684        | 0.130 (0.017)    | -                | -         |     5.08 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            1 |     4221 | 2024-04-08 | Aurora            | L   | 0.181      | -            | -                | -                | -         |    -0.40 | F1KU, HeavyGod, k1to, MoDo, Nexius |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,726.83)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-25 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-08-04 |      0.967 | $5,000.00      | $4,835.53       |
| 2024-05-02 |      0.341 | $1,000.00      | $340.83         |
| 2024-04-20 |      0.262 | $10,000.00     | $2,621.30       |
| 2024-04-14 |      0.220 | $70,000.00     | $15,429.17      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
