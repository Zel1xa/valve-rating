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
Final Rank Value (721.7) = Starting Rank Value (700.0) + Head To Head Adjustments (21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.0
- 400 + ( ( 0.146 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 700.0


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
|           22 |     2435 | 2024-05-02 | 1WIN              | L   | 0.563      | -            | -                | -                | -         |    -4.02 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2505 | 2024-04-29 | Sashi             | L   | 0.543      | -            | -                | -                | -         |    -1.29 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2534 | 2024-04-27 | Zero Tenacity     | L   | 0.531      | -            | -                | -                | -         |    -2.26 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2804 | 2024-04-18 | Secret            | L   | 0.469      | -            | -                | -                | -         |   -11.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2829 | 2024-04-17 | Portugal          | L   | 0.464      | -            | -                | -                | -         |    -8.48 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2866 | 2024-04-16 | Passion UA        | W   | 0.458      | 0.384        | 0.173 (0.030)    | 1.000 (0.176)    | 0 (0.000) |    12.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2955 | 2024-04-11 | PARIVISION        | W   | 0.424      | 0.384        | 0.017 (0.003)    | 0.565 (0.092)    | 0 (0.000) |    11.78 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3278 | 2024-04-02 | ex-Guild Eagles   | W   | 0.362      | 0.384        | 0.007 (0.001)    | 0.213 (0.030)    | 0 (0.000) |     7.11 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3283 | 2024-04-01 | ex-Guild Eagles   | L   | 0.358      | -            | -                | -                | -         |    -4.33 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3355 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.325      | -            | -                | -                | -         |    -0.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3362 | 2024-03-27 | FORZE             | W   | 0.325      | 0.143        | 0.058 (0.003)    | 0.169 (0.008)    | 0 (0.000) |     7.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3707 | 2024-03-10 | Young Ninjas      | L   | 0.210      | -            | -                | -                | -         |    -2.84 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3780 | 2024-03-07 | Sangal            | W   | 0.190      | 0.143        | 0.219 (0.006)    | 0.866 (0.024)    | 0 (0.000) |     5.53 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3856 | 2024-03-05 | Entropiq          | W   | 0.176      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     1.64 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3915 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.157      | 0.358        | 0.031 (0.002)    | 0.550 (0.031)    | 0 (0.000) |     4.08 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4003 | 2024-02-26 | Imperial fe       | W   | 0.123      | 0.143        | 0.128 (0.002)    | 0.294 (0.005)    | 0 (0.000) |     3.34 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4051 | 2024-02-24 | Portugal          | W   | 0.111      | 0.358        | 0.003 (0.000)    | 0.118 (0.005)    | 0 (0.000) |     1.66 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4194 | 2024-02-18 | Sangal            | L   | 0.069      | -            | -                | -                | -         |    -0.15 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4234 | 2024-02-16 | SINNERS           | L   | 0.058      | -            | -                | -                | -         |    -0.14 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4240 | 2024-02-16 | B8                | L   | 0.058      | -            | -                | -                | -         |    -0.19 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4242 | 2024-02-16 | SINNERS           | W   | 0.057      | 0.143        | 0.037 (0.000)    | 0.808 (0.007)    | 0 (0.000) |     1.66 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4374 | 2024-02-10 | Secret            | L   | 0.016      | -            | -                | -                | -         |    -0.37 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($282.08)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
