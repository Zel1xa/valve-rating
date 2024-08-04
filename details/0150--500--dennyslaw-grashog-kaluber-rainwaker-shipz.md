### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.6<br />
<br />
Final Rank Value (722.6) = Starting Rank Value (700.1) + Head To Head Adjustments (22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.1
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 700.1


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
|           22 |     2406 | 2024-05-02 | 1WIN              | L   | 0.573      | -            | -                | -                | -         |    -4.24 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2476 | 2024-04-29 | Sashi             | L   | 0.552      | -            | -                | -                | -         |    -1.32 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2505 | 2024-04-27 | Zero Tenacity     | L   | 0.541      | -            | -                | -                | -         |    -2.36 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2775 | 2024-04-18 | Secret            | L   | 0.479      | -            | -                | -                | -         |   -11.27 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2800 | 2024-04-17 | Portugal          | L   | 0.473      | -            | -                | -                | -         |    -8.66 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2837 | 2024-04-16 | Passion UA        | W   | 0.467      | 0.384        | 0.172 (0.031)    | 1.000 (0.179)    | 0 (0.000) |    12.46 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2926 | 2024-04-11 | PARIVISION        | W   | 0.434      | 0.384        | 0.017 (0.003)    | 0.534 (0.089)    | 0 (0.000) |    11.98 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3249 | 2024-04-02 | ex-Guild Eagles   | W   | 0.372      | 0.384        | 0.007 (0.001)    | 0.219 (0.031)    | 0 (0.000) |     7.29 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3254 | 2024-04-01 | ex-Guild Eagles   | L   | 0.368      | -            | -                | -                | -         |    -4.44 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3326 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.334      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3333 | 2024-03-27 | FORZE             | W   | 0.334      | 0.143        | 0.058 (0.003)    | 0.177 (0.008)    | 0 (0.000) |     8.02 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3678 | 2024-03-10 | Young Ninjas      | L   | 0.220      | -            | -                | -                | -         |    -3.03 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3751 | 2024-03-07 | Sangal            | W   | 0.200      | 0.143        | 0.219 (0.006)    | 0.861 (0.025)    | 0 (0.000) |     5.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3827 | 2024-03-05 | Entropiq          | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.73 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3886 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.167      | 0.358        | 0.031 (0.002)    | 0.560 (0.033)    | 0 (0.000) |     4.32 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3974 | 2024-02-26 | Imperial fe       | W   | 0.132      | 0.143        | 0.128 (0.002)    | 0.299 (0.006)    | 0 (0.000) |     3.60 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4022 | 2024-02-24 | Portugal          | W   | 0.120      | 0.358        | 0.003 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     1.80 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4165 | 2024-02-18 | Sangal            | L   | 0.078      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4205 | 2024-02-16 | SINNERS           | L   | 0.067      | -            | -                | -                | -         |    -0.17 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4211 | 2024-02-16 | B8                | L   | 0.067      | -            | -                | -                | -         |    -0.22 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4213 | 2024-02-16 | SINNERS           | W   | 0.066      | 0.143        | 0.037 (0.000)    | 0.797 (0.008)    | 0 (0.000) |     1.93 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4345 | 2024-02-10 | Secret            | L   | 0.026      | -            | -                | -                | -         |    -0.58 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($286.76)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
