### Roster Details<br />
Team Name: OG<br />
Roster: Buzz, Chr1zN, F1KU, MoDo, Nexius<br />
Global Rank: [50](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [37]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  1034.5<br />
<br />
Final Rank Value (1034.5) = Starting Rank Value (956.4) + Head To Head Adjustments (78.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.520[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.285<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.4
- 400 + ( ( 0.285 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 956.4


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
|           33 |      181 | 2024-08-31 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -19.31 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           32 |      198 | 2024-08-30 | Endpoint          | W   | 1.000      | 0.384        | 0.064 (0.025)    | 0.742 (0.285)    | 0 (0.000) |    11.96 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           31 |      406 | 2024-08-26 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -5.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           30 |      422 | 2024-08-26 | Falcons           | L   | 1.000      | -            | -                | -                | -         |    -1.94 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           29 |      466 | 2024-08-25 | FaZe              | L   | 1.000      | -            | -                | -                | -         |    -0.66 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           28 |      506 | 2024-08-23 | AMKAL             | W   | 1.000      | 0.535        | 0.123 (0.066)    | 0.413 (0.221)    | 0 (0.000) |    14.36 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           27 |      514 | 2024-08-23 | Sashi             | L   | 1.000      | -            | -                | -                | -         |   -13.52 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           26 |      519 | 2024-08-23 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -14.12 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           25 |      554 | 2024-08-22 | Rebels            | W   | 1.000      | 0.143        | -                | 0.677 (0.097)    | 0 (0.000) |    10.72 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           24 |      583 | 2024-08-21 | HEROIC            | W   | 1.000      | 0.535        | 0.206 (0.110)    | 0.401 (0.215)    | 0 (0.000) |    27.36 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           23 |      591 | 2024-08-21 | Zero Tenacity     | W   | 1.000      | 0.143        | 0.138 (0.020)    | 1.000 (0.143)    | 0 (0.000) |    15.04 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           22 |      628 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.85 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           21 |      773 | 2024-08-15 | B8                | W   | 1.000      | 0.143        | 0.176 (0.025)    | 1.000 (0.143)    | 0 (0.000) |    19.98 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           20 |      778 | 2024-08-15 | PARIVISION        | W   | 1.000      | 0.143        | -                | 0.753 (0.108)    | 0 (0.000) |    21.87 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           19 |      782 | 2024-08-15 | ARCRED            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.03 | Buzz, Chr1zN, F1KU, MoDo, Nexius   |
|           18 |     1342 | 2024-07-30 | Complexity        | L   | 0.945      | -            | -                | -                | -         |    -1.51 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           17 |     1377 | 2024-07-29 | Spirit            | L   | 0.938      | -            | -                | -                | -         |    -0.10 | F1KU, k1to, MoDo, Nexius, Thomas   |
|           16 |     2792 | 2024-05-30 | Chinggis Warriors | L   | 0.538      | -            | -                | -                | -         |   -10.05 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           15 |     2820 | 2024-05-29 | ATOX              | L   | 0.530      | -            | -                | -                | -         |   -12.30 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           14 |     3079 | 2024-05-19 | paiN              | L   | 0.464      | -            | -                | -                | -         |    -0.39 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           13 |     3087 | 2024-05-18 | Liquid            | L   | 0.460      | -            | -                | -                | -         |    -0.48 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           12 |     3553 | 2024-05-01 | Insilio           | L   | 0.346      | -            | -                | -                | -         |    -6.65 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           11 |     3582 | 2024-04-30 | Sashi             | L   | 0.339      | -            | -                | -                | -         |    -3.75 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|           10 |     3804 | 2024-04-20 | MIBR              | L   | 0.272      | -            | -                | -                | -         |    -0.66 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            9 |     3819 | 2024-04-19 | 9z                | W   | 0.269      | 0.589        | 0.342 (0.054)    | 0.550 (0.087)    | 1 (0.269) |     8.00 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            8 |     3830 | 2024-04-19 | Monte             | W   | 0.267      | -            | -                | -                | 1 (0.267) |     3.95 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            7 |     3874 | 2024-04-18 | MIBR              | L   | 0.261      | -            | -                | -                | -         |    -0.66 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            6 |     4003 | 2024-04-14 | Aurora            | L   | 0.232      | -            | -                | -                | -         |    -0.55 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            5 |     4012 | 2024-04-13 | BetBoom           | W   | 0.227      | 0.684        | 0.230 (0.036)    | 0.555 (0.086)    | -         |     5.86 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            4 |     4021 | 2024-04-13 | BIG               | W   | 0.225      | 0.684        | 0.147 (0.023)    | -                | -         |     5.63 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            3 |     4034 | 2024-04-12 | Ninjas in Pyjamas | W   | 0.219      | 0.684        | 0.210 (0.031)    | 0.445 (0.067)    | -         |     6.46 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            2 |     4106 | 2024-04-10 | ENCE              | W   | 0.205      | 0.684        | 0.131 (0.018)    | -                | -         |     5.44 | F1KU, HeavyGod, k1to, MoDo, Nexius |
|            1 |     4184 | 2024-04-08 | Aurora            | L   | 0.193      | -            | -                | -                | -         |    -0.40 | F1KU, HeavyGod, k1to, MoDo, Nexius |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($36,752.06)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-25 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-08-04 |      0.979 | $5,000.00      | $4,895.14       |
| 2024-05-02 |      0.353 | $1,000.00      | $352.75         |
| 2024-04-20 |      0.274 | $10,000.00     | $2,740.51       |
| 2024-04-14 |      0.232 | $70,000.00     | $16,263.66      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
