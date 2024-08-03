### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  723.9<br />
<br />
Final Rank Value (723.9) = Starting Rank Value (701.4) + Head To Head Adjustments (22.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.4
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 701.4


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
|           23 |     2305 | 2024-05-02 | 1WIN              | L   | 0.579      | -            | -                | -                | -         |    -4.74 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           22 |     2375 | 2024-04-29 | Sashi             | L   | 0.558      | -            | -                | -                | -         |    -1.31 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     2404 | 2024-04-27 | Zero Tenacity     | L   | 0.547      | -            | -                | -                | -         |    -2.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2673 | 2024-04-18 | Secret            | L   | 0.485      | -            | -                | -                | -         |   -11.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2698 | 2024-04-17 | Portugal          | L   | 0.480      | -            | -                | -                | -         |    -8.78 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2735 | 2024-04-16 | Passion UA        | W   | 0.473      | 0.384        | 0.172 (0.031)    | 1.000 (0.182)    | 0 (0.000) |    12.57 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2824 | 2024-04-11 | PARIVISION        | W   | 0.440      | 0.384        | 0.018 (0.003)    | 0.553 (0.093)    | 0 (0.000) |    12.16 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3147 | 2024-04-02 | ex-Guild Eagles   | W   | 0.378      | 0.384        | 0.007 (0.001)    | 0.228 (0.033)    | 0 (0.000) |     7.44 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3152 | 2024-04-01 | ex-Guild Eagles   | L   | 0.374      | -            | -                | -                | -         |    -4.49 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3223 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.341      | -            | -                | -                | -         |    -0.07 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3230 | 2024-03-27 | FORZE             | W   | 0.340      | 0.143        | 0.059 (0.003)    | 0.186 (0.009)    | 0 (0.000) |     8.18 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3568 | 2024-03-10 | Young Ninjas      | L   | 0.226      | -            | -                | -                | -         |    -3.11 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3641 | 2024-03-07 | Sangal            | W   | 0.206      | 0.143        | 0.219 (0.006)    | 0.823 (0.024)    | 0 (0.000) |     5.96 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3717 | 2024-03-05 | Entropiq          | W   | 0.192      | 0.143        | 0.000 (0.000)    | 0.040 (0.001)    | 0 (0.000) |     1.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3776 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.173      | 0.358        | 0.032 (0.002)    | 0.580 (0.036)    | 0 (0.000) |     4.48 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3864 | 2024-02-26 | Imperial fe       | W   | 0.138      | 0.143        | 0.129 (0.003)    | 0.310 (0.006)    | 0 (0.000) |     3.77 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3912 | 2024-02-24 | Portugal          | W   | 0.126      | 0.358        | 0.003 (0.000)    | 0.125 (0.006)    | 0 (0.000) |     1.90 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4054 | 2024-02-18 | Sangal            | L   | 0.085      | -            | -                | -                | -         |    -0.20 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4094 | 2024-02-16 | SINNERS           | L   | 0.074      | -            | -                | -                | -         |    -0.24 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4100 | 2024-02-16 | B8                | L   | 0.073      | -            | -                | -                | -         |    -0.24 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4102 | 2024-02-16 | SINNERS           | W   | 0.073      | 0.143        | 0.037 (0.000)    | 0.784 (0.008)    | 0 (0.000) |     2.06 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4234 | 2024-02-10 | Secret            | L   | 0.032      | -            | -                | -                | -         |    -0.72 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4276 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.006      | -            | -                | -                | -         |    -0.03 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($289.88)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
