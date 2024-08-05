### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.0<br />
<br />
Final Rank Value (722.0) = Starting Rank Value (700.1) + Head To Head Adjustments (21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.1
- 400 + ( ( 0.146 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 700.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     2433 | 2024-05-02 | 1WIN              | L   | 0.565      | -            | -                | -                | -         |    -4.04 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2503 | 2024-04-29 | Sashi             | L   | 0.545      | -            | -                | -                | -         |    -1.30 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2532 | 2024-04-27 | Zero Tenacity     | L   | 0.533      | -            | -                | -                | -         |    -2.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2802 | 2024-04-18 | Secret            | L   | 0.471      | -            | -                | -                | -         |   -11.08 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2827 | 2024-04-17 | Portugal          | L   | 0.466      | -            | -                | -                | -         |    -8.52 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2864 | 2024-04-16 | Passion UA        | W   | 0.459      | 0.384        | 0.173 (0.031)    | 1.000 (0.177)    | 0 (0.000) |    12.32 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2953 | 2024-04-11 | PARIVISION        | W   | 0.426      | 0.384        | 0.017 (0.003)    | 0.565 (0.092)    | 0 (0.000) |    11.83 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3276 | 2024-04-02 | ex-Guild Eagles   | W   | 0.364      | 0.384        | 0.007 (0.001)    | 0.214 (0.030)    | 0 (0.000) |     7.14 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3281 | 2024-04-01 | ex-Guild Eagles   | L   | 0.360      | -            | -                | -                | -         |    -4.35 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3353 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.327      | -            | -                | -                | -         |    -0.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3360 | 2024-03-27 | FORZE             | W   | 0.327      | 0.143        | 0.058 (0.003)    | 0.170 (0.008)    | 0 (0.000) |     7.83 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3705 | 2024-03-10 | Young Ninjas      | L   | 0.212      | -            | -                | -                | -         |    -2.86 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3778 | 2024-03-07 | Sangal            | W   | 0.192      | 0.143        | 0.219 (0.006)    | 0.866 (0.024)    | 0 (0.000) |     5.58 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3854 | 2024-03-05 | Entropiq          | W   | 0.178      | 0.143        | 0.000 (0.000)    | 0.036 (0.001)    | 0 (0.000) |     1.66 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3913 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.159      | 0.358        | 0.031 (0.002)    | 0.550 (0.031)    | 0 (0.000) |     4.13 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4001 | 2024-02-26 | Imperial fe       | W   | 0.125      | 0.143        | 0.128 (0.002)    | 0.294 (0.005)    | 0 (0.000) |     3.39 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4049 | 2024-02-24 | Portugal          | W   | 0.113      | 0.358        | 0.003 (0.000)    | 0.118 (0.005)    | 0 (0.000) |     1.68 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4192 | 2024-02-18 | Sangal            | L   | 0.071      | -            | -                | -                | -         |    -0.16 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4232 | 2024-02-16 | SINNERS           | L   | 0.060      | -            | -                | -                | -         |    -0.14 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4238 | 2024-02-16 | B8                | L   | 0.059      | -            | -                | -                | -         |    -0.20 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4240 | 2024-02-16 | SINNERS           | W   | 0.059      | 0.143        | 0.037 (0.000)    | 0.809 (0.007)    | 0 (0.000) |     1.72 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4372 | 2024-02-10 | Secret            | L   | 0.018      | -            | -                | -                | -         |    -0.41 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($282.99)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
