### Roster Details<br />
Team Name: OG<br />
Roster: Buzz, Chr1zN, F1KU, MoDo, Nexius<br />
Global Rank: [50](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [37]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  1033.9<br />
<br />
Final Rank Value (1033.9) = Starting Rank Value (955.7) + Head To Head Adjustments (78.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.519[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.284<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 955.7
- 400 + ( ( 0.284 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 955.7


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
|           33 |      186 | 2024-08-31 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -19.24 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           32 |      203 | 2024-08-30 | Endpoint          | W   | 1.000      | 0.384        | 0.064 (0.025)    | 0.744 (0.286)    | 0 (0.000) |    12.01 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           31 |      411 | 2024-08-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           30 |      427 | 2024-08-26 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -1.93 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           29 |      471 | 2024-08-25 | FaZe              | L   | 1.000      | -            | -                | -                | -         |    -0.65 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           28 |      511 | 2024-08-23 | AMKAL             | W   | 1.000      | 0.535        | 0.123 (0.066)    | 0.412 (0.220)    | 0 (0.000) |    14.39 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           27 |      519 | 2024-08-23 | Sashi             | L   | 1.000      | -            | -                | -                | -         |   -13.50 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           26 |      524 | 2024-08-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -14.09 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           25 |      559 | 2024-08-22 | Rebels            | W   | 1.000      | 0.143        | -                | 0.677 (0.097)    | 0 (0.000) |    10.74 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           24 |      588 | 2024-08-21 | HEROIC            | W   | 1.000      | 0.535        | 0.206 (0.110)    | 0.401 (0.214)    | 0 (0.000) |    27.35 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           23 |      596 | 2024-08-21 | Zero Tenacity     | W   | 1.000      | 0.143        | 0.138 (0.020)    | 1.000 (0.143)    | 0 (0.000) |    15.08 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           22 |      633 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.84 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           21 |      778 | 2024-08-15 | B8                | W   | 1.000      | 0.143        | 0.176 (0.025)    | 1.000 (0.143)    | 0 (0.000) |    20.01 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           20 |      783 | 2024-08-15 | PARIVISION        | W   | 1.000      | 0.143        | -                | 0.754 (0.108)    | 0 (0.000) |    21.90 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           19 |      787 | 2024-08-15 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.07 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           18 |     1347 | 2024-07-30 | Complexity        | L   | 0.941      | -            | -                | -                | -         |    -1.51 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           17 |     1382 | 2024-07-29 | Spirit            | L   | 0.934      | -            | -                | -                | -         |    -0.10 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           16 |     2797 | 2024-05-30 | Chinggis Warriors | L   | 0.534      | -            | -                | -                | -         |    -9.97 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           15 |     2825 | 2024-05-29 | ATOX              | L   | 0.526      | -            | -                | -                | -         |   -12.20 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           14 |     3084 | 2024-05-19 | paiN              | L   | 0.460      | -            | -                | -                | -         |    -0.38 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           13 |     3092 | 2024-05-18 | Liquid            | L   | 0.456      | -            | -                | -                | -         |    -0.48 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           12 |     3558 | 2024-05-01 | Insilio           | L   | 0.342      | -            | -                | -                | -         |    -6.56 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           11 |     3587 | 2024-04-30 | Sashi             | L   | 0.335      | -            | -                | -                | -         |    -3.70 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           10 |     3809 | 2024-04-20 | MIBR              | L   | 0.268      | -            | -                | -                | -         |    -0.65 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            9 |     3824 | 2024-04-19 | 9z                | W   | 0.265      | 0.589        | 0.342 (0.053)    | 0.549 (0.086)    | 1 (0.265) |     7.88 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            8 |     3835 | 2024-04-19 | Monte             | W   | 0.263      | -            | -                | -                | 1 (0.263) |     3.89 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            7 |     3879 | 2024-04-18 | MIBR              | L   | 0.257      | -            | -                | -                | -         |    -0.65 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            6 |     4008 | 2024-04-14 | Aurora            | L   | 0.228      | -            | -                | -                | -         |    -0.54 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            5 |     4017 | 2024-04-13 | BetBoom           | W   | 0.223      | 0.684        | 0.230 (0.035)    | 0.554 (0.084)    | -         |     5.75 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            4 |     4026 | 2024-04-13 | BIG               | W   | 0.221      | 0.684        | 0.146 (0.022)    | -                | -         |     5.54 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            3 |     4039 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.215      | 0.684        | 0.210 (0.031)    | 0.444 (0.065)    | -         |     6.34 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            2 |     4111 | 2024-04-10 | ENCE              | W   | 0.201      | 0.684        | 0.131 (0.018)    | -                | -         |     5.33 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            1 |     4189 | 2024-04-08 | Aurora            | L   | 0.189      | -            | -                | -                | -         |    -0.39 | F1KU, HeavyGod, k1to, MoDo, Nexius |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($36,407.66)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-25 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-08-04 |      0.975 | $5,000.00      | $4,875.12       |
| 2024-05-02 |      0.349 | $1,000.00      | $348.75         |
| 2024-04-20 |      0.270 | $10,000.00     | $2,700.46       |
| 2024-04-14 |      0.228 | $70,000.00     | $15,983.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
