### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.2<br />
<br />
Final Rank Value (722.2) = Starting Rank Value (700.3) + Head To Head Adjustments (21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.3
- 400 + ( ( 0.147 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 700.3


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
|           23 |     2375 | 2024-05-02 | 1WIN              | L   | 0.574      | -            | -                | -                | -         |    -4.74 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           22 |     2445 | 2024-04-29 | Sashi             | L   | 0.554      | -            | -                | -                | -         |    -1.34 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     2474 | 2024-04-27 | Zero Tenacity     | L   | 0.542      | -            | -                | -                | -         |    -2.39 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2744 | 2024-04-18 | Secret            | L   | 0.480      | -            | -                | -                | -         |   -11.30 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2769 | 2024-04-17 | Portugal          | L   | 0.475      | -            | -                | -                | -         |    -8.69 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2806 | 2024-04-16 | Passion UA        | W   | 0.468      | 0.384        | 0.172 (0.031)    | 1.000 (0.180)    | 0 (0.000) |    12.45 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2895 | 2024-04-11 | PARIVISION        | W   | 0.435      | 0.384        | 0.017 (0.003)    | 0.534 (0.089)    | 0 (0.000) |    12.02 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3218 | 2024-04-02 | ex-Guild Eagles   | W   | 0.373      | 0.384        | 0.007 (0.001)    | 0.220 (0.032)    | 0 (0.000) |     7.35 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3223 | 2024-04-01 | ex-Guild Eagles   | L   | 0.369      | -            | -                | -                | -         |    -4.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3295 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.336      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3302 | 2024-03-27 | FORZE             | W   | 0.336      | 0.143        | 0.058 (0.003)    | 0.177 (0.009)    | 0 (0.000) |     8.06 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3647 | 2024-03-10 | Young Ninjas      | L   | 0.221      | -            | -                | -                | -         |    -3.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3720 | 2024-03-07 | Sangal            | W   | 0.201      | 0.143        | 0.219 (0.006)    | 0.862 (0.025)    | 0 (0.000) |     5.83 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3796 | 2024-03-05 | Entropiq          | W   | 0.187      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.75 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3855 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.168      | 0.358        | 0.031 (0.002)    | 0.560 (0.034)    | 0 (0.000) |     4.36 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3943 | 2024-02-26 | Imperial fe       | W   | 0.134      | 0.143        | 0.128 (0.002)    | 0.299 (0.006)    | 0 (0.000) |     3.64 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3991 | 2024-02-24 | Portugal          | W   | 0.122      | 0.358        | 0.003 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     1.82 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4134 | 2024-02-18 | Sangal            | L   | 0.080      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4174 | 2024-02-16 | SINNERS           | L   | 0.069      | -            | -                | -                | -         |    -0.23 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4180 | 2024-02-16 | B8                | L   | 0.068      | -            | -                | -                | -         |    -0.23 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4182 | 2024-02-16 | SINNERS           | W   | 0.068      | 0.143        | 0.037 (0.000)    | 0.758 (0.007)    | 0 (0.000) |     1.92 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4314 | 2024-02-10 | Secret            | L   | 0.027      | -            | -                | -                | -         |    -0.61 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4356 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.001      | -            | -                | -                | -         |    -0.01 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($287.50)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
