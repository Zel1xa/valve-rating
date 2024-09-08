### Roster Details<br />
Team Name: True Rippers<br />
Roster: Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  665.5<br />
<br />
Final Rank Value (665.5) = Starting Rank Value (655.9) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.9
- 400 + ( ( 0.132 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 655.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      244 | 2024-08-30 | Gods Reign  | L   | 1.000      | -            | -                | -                | -         |   -13.42 | Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi    |
|           21 |      282 | 2024-08-29 | ONi         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.113 (0.016)    | 0 (0.000) |     8.57 | Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi    |
|           20 |      297 | 2024-08-29 | Forward     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     8.22 | Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi    |
|           19 |      332 | 2024-08-28 | Dewa United | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     8.46 | Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi    |
|           18 |      351 | 2024-08-28 | Niory       | L   | 1.000      | -            | -                | -                | -         |   -22.03 | Crazy_Gamer, Crunchy, DayMake, DEFAULTER, Rossi    |
|           17 |     1490 | 2024-07-26 | ENCE        | L   | 0.907      | -            | -                | -                | -         |    -1.26 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           16 |     1498 | 2024-07-26 | PARIVISION  | L   | 0.906      | -            | -                | -                | -         |    -2.75 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           15 |     1528 | 2024-07-25 | Aurora      | L   | 0.901      | -            | -                | -                | -         |    -0.63 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           14 |     1564 | 2024-07-24 | BLEED       | L   | 0.893      | -            | -                | -                | -         |    -1.61 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           13 |     1615 | 2024-07-23 | The MongolZ | L   | 0.885      | -            | -                | -                | -         |    -0.07 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           12 |     2105 | 2024-06-30 | Gods Reign  | L   | 0.732      | -            | -                | -                | -         |   -11.01 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           11 |     2106 | 2024-06-29 | Niory       | W   | 0.731      | 0.262        | 0.000 (0.000)    | 0.113 (0.022)    | 0 (0.000) |     5.70 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|           10 |     2111 | 2024-06-29 | Gods Reign  | W   | 0.727      | 0.143        | 0.022 (0.002)    | 0.247 (0.026)    | 0 (0.000) |    12.27 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|            9 |     2117 | 2024-06-28 | Marcos      | W   | 0.720      | 0.143        | 0.000 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     6.07 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|            8 |     2123 | 2024-06-27 | Gods Reign  | W   | 0.713      | 0.143        | 0.022 (0.002)    | 0.247 (0.025)    | 0 (0.000) |    12.68 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|            7 |     2918 | 2024-05-26 | Gods Reign  | L   | 0.499      | -            | -                | -                | -         |    -6.87 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|            6 |     2922 | 2024-05-25 | Carnival    | W   | 0.498      | 0.262        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.04 | Crazy_Gamer, DayMake, DEFAULTER, Mcg!LLzZz, Rossi  |
|            5 |     3651 | 2024-04-29 | Carnival    | W   | 0.318      | 0.262        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.33 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg!LLzZz, Rossi |
|            4 |     4436 | 2024-03-31 | Gods Reign  | L   | 0.125      | -            | -                | -                | -         |    -1.74 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg!LLzZz, Rossi |
|            3 |     4442 | 2024-03-30 | Marcos      | W   | 0.119      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.47 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg!LLzZz, Rossi |
|            2 |     4450 | 2024-03-29 | Grayfox     | W   | 0.113      | -            | -                | -                | -         |     0.69 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg!LLzZz, Rossi |
|            1 |     4545 | 2024-03-23 | Marcos      | L   | 0.078      | -            | -                | -                | -         |    -1.49 | Anasasis, Crazy_Gamer, DEFAULTER, Mcg!LLzZz, Rossi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($933.81)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-30 |      0.732 | $500.00        | $365.88         |
| 2024-05-26 |      0.499 | $500.00        | $249.43         |
| 2024-04-29 |      0.318 | $1,000.00      | $318.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
