### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  721.9<br />
<br />
Final Rank Value (721.9) = Starting Rank Value (700.5) + Head To Head Adjustments (21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.5
- 400 + ( ( 0.146 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 700.5


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
|           22 |     2443 | 2024-05-02 | 1WIN              | L   | 0.560      | -            | -                | -                | -         |    -4.00 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2513 | 2024-04-29 | Sashi             | L   | 0.540      | -            | -                | -                | -         |    -1.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2542 | 2024-04-27 | Zero Tenacity     | L   | 0.529      | -            | -                | -                | -         |    -2.25 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2812 | 2024-04-18 | Secret            | L   | 0.467      | -            | -                | -                | -         |   -10.97 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2837 | 2024-04-17 | Portugal          | L   | 0.461      | -            | -                | -                | -         |    -8.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2874 | 2024-04-16 | Passion UA        | W   | 0.455      | 0.384        | 0.173 (0.030)    | 1.000 (0.175)    | 0 (0.000) |    12.22 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2963 | 2024-04-11 | PARIVISION        | W   | 0.421      | 0.384        | 0.017 (0.003)    | 0.590 (0.096)    | 0 (0.000) |    11.73 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3286 | 2024-04-02 | ex-Guild Eagles   | W   | 0.360      | 0.384        | 0.007 (0.001)    | 0.207 (0.029)    | 0 (0.000) |     7.08 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3291 | 2024-04-01 | ex-Guild Eagles   | L   | 0.355      | -            | -                | -                | -         |    -4.27 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3363 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.322      | -            | -                | -                | -         |    -0.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3370 | 2024-03-27 | FORZE             | W   | 0.322      | 0.143        | 0.057 (0.003)    | 0.164 (0.008)    | 0 (0.000) |     7.71 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3715 | 2024-03-10 | Young Ninjas      | L   | 0.208      | -            | -                | -                | -         |    -2.81 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3788 | 2024-03-07 | Sangal            | W   | 0.188      | 0.143        | 0.219 (0.006)    | 0.846 (0.023)    | 0 (0.000) |     5.45 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3864 | 2024-03-05 | Entropiq          | W   | 0.173      | 0.143        | 0.000 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     1.61 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3923 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.155      | 0.358        | 0.031 (0.002)    | 0.537 (0.030)    | 0 (0.000) |     4.01 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4011 | 2024-02-26 | Imperial fe       | W   | 0.120      | 0.143        | 0.128 (0.002)    | 0.287 (0.005)    | 0 (0.000) |     3.27 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4059 | 2024-02-24 | Portugal          | W   | 0.108      | 0.358        | 0.003 (0.000)    | 0.115 (0.004)    | 0 (0.000) |     1.61 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4202 | 2024-02-18 | Sangal            | L   | 0.066      | -            | -                | -                | -         |    -0.15 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4242 | 2024-02-16 | SINNERS           | L   | 0.055      | -            | -                | -                | -         |    -0.13 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4248 | 2024-02-16 | B8                | L   | 0.055      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4250 | 2024-02-16 | SINNERS           | W   | 0.054      | 0.143        | 0.037 (0.000)    | 0.790 (0.006)    | 0 (0.000) |     1.58 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4382 | 2024-02-10 | Secret            | L   | 0.014      | -            | -                | -                | -         |    -0.30 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($280.69)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
