### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  721.7<br />
<br />
Final Rank Value (721.7) = Starting Rank Value (700.4) + Head To Head Adjustments (21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.4
- 400 + ( ( 0.146 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 700.4


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
|           22 |     2456 | 2024-05-02 | 1WIN              | L   | 0.559      | -            | -                | -                | -         |    -3.96 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2526 | 2024-04-29 | Sashi             | L   | 0.539      | -            | -                | -                | -         |    -1.27 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2555 | 2024-04-27 | Zero Tenacity     | L   | 0.527      | -            | -                | -                | -         |    -2.24 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2825 | 2024-04-18 | Secret            | L   | 0.465      | -            | -                | -                | -         |   -10.93 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2850 | 2024-04-17 | Portugal          | L   | 0.460      | -            | -                | -                | -         |    -8.41 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2887 | 2024-04-16 | Passion UA        | W   | 0.453      | 0.384        | 0.173 (0.030)    | 1.000 (0.174)    | 0 (0.000) |    12.19 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2976 | 2024-04-11 | PARIVISION        | W   | 0.420      | 0.384        | 0.017 (0.003)    | 0.590 (0.095)    | 0 (0.000) |    11.70 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3299 | 2024-04-02 | ex-Guild Eagles   | W   | 0.358      | 0.384        | 0.007 (0.001)    | 0.207 (0.029)    | 0 (0.000) |     7.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3304 | 2024-04-01 | ex-Guild Eagles   | L   | 0.354      | -            | -                | -                | -         |    -4.25 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3376 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.321      | -            | -                | -                | -         |    -0.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3383 | 2024-03-27 | FORZE             | W   | 0.321      | 0.143        | 0.057 (0.003)    | 0.163 (0.007)    | 0 (0.000) |     7.69 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3728 | 2024-03-10 | Young Ninjas      | L   | 0.206      | -            | -                | -                | -         |    -2.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3801 | 2024-03-07 | Sangal            | W   | 0.186      | 0.143        | 0.219 (0.006)    | 0.846 (0.023)    | 0 (0.000) |     5.42 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3877 | 2024-03-05 | Entropiq          | W   | 0.172      | 0.143        | 0.000 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     1.59 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3936 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.153      | 0.358        | 0.031 (0.002)    | 0.537 (0.029)    | 0 (0.000) |     3.98 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4024 | 2024-02-26 | Imperial fe       | W   | 0.119      | 0.143        | 0.128 (0.002)    | 0.287 (0.005)    | 0 (0.000) |     3.23 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4072 | 2024-02-24 | Portugal          | W   | 0.107      | 0.358        | 0.003 (0.000)    | 0.115 (0.004)    | 0 (0.000) |     1.59 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4215 | 2024-02-18 | Sangal            | L   | 0.065      | -            | -                | -                | -         |    -0.14 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4255 | 2024-02-16 | SINNERS           | L   | 0.054      | -            | -                | -                | -         |    -0.13 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4261 | 2024-02-16 | B8                | L   | 0.053      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4263 | 2024-02-16 | SINNERS           | W   | 0.053      | 0.143        | 0.037 (0.000)    | 0.800 (0.006)    | 0 (0.000) |     1.54 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4395 | 2024-02-10 | Secret            | L   | 0.012      | -            | -                | -                | -         |    -0.27 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($280.00)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
