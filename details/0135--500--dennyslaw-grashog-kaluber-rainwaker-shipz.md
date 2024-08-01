### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [135](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
<br />
Final Rank Value:  763.6<br />
<br />
Final Rank Value (763.6) = Starting Rank Value (727.6) + Head To Head Adjustments (36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 727.6
- 400 + ( ( 0.159 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 727.6


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
|           29 |     2341 | 2024-05-02 | MOUZ NXT          | W   | 0.595      | 0.396        | 0.141 (0.033)    | 1.000 (0.236)    | 0 (0.000) |    15.69 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           28 |     2350 | 2024-05-02 | 1WIN              | L   | 0.593      | -            | -                | -                | -         |    -5.38 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           27 |     2422 | 2024-04-29 | Sashi             | L   | 0.573      | -            | -                | -                | -         |    -1.52 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           26 |     2451 | 2024-04-27 | Zero Tenacity     | L   | 0.562      | -            | -                | -                | -         |    -2.83 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           25 |     2729 | 2024-04-18 | Secret            | L   | 0.500      | -            | -                | -                | -         |   -12.15 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           24 |     2755 | 2024-04-17 | Portugal          | L   | 0.494      | -            | -                | -                | -         |    -9.47 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           23 |     2792 | 2024-04-16 | Passion UA        | W   | 0.488      | 0.384        | 0.172 (0.032)    | 1.000 (0.187)    | 0 (0.000) |    12.72 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           22 |     2883 | 2024-04-11 | PARIVISION        | W   | 0.454      | 0.384        | 0.018 (0.003)    | 0.451 (0.079)    | 0 (0.000) |    12.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     3214 | 2024-04-02 | ex-Guild Eagles   | W   | 0.393      | 0.384        | 0.007 (0.001)    | 0.225 (0.034)    | 0 (0.000) |     7.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     3219 | 2024-04-01 | ex-Guild Eagles   | L   | 0.388      | -            | -                | -                | -         |    -4.97 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     3292 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.355      | -            | -                | -                | -         |    -0.17 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     3299 | 2024-03-27 | FORZE             | W   | 0.355      | 0.143        | 0.060 (0.003)    | 0.186 (0.009)    | 0 (0.000) |     8.34 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     3653 | 2024-03-10 | Young Ninjas      | L   | 0.241      | -            | -                | -                | -         |    -3.51 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3727 | 2024-03-07 | Sangal            | W   | 0.221      | 0.143        | 0.221 (0.007)    | 0.823 (0.026)    | 0 (0.000) |     6.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3808 | 2024-03-05 | Entropiq          | W   | 0.206      | -            | -                | -                | 0 (0.000) |     1.75 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3867 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.188      | 0.358        | 0.032 (0.002)    | 0.564 (0.038)    | 0 (0.000) |     4.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3958 | 2024-02-26 | Imperial fe       | W   | 0.153      | 0.143        | 0.130 (0.003)    | 0.270 (0.006)    | 0 (0.000) |     4.11 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     4007 | 2024-02-24 | Portugal          | W   | 0.141      | 0.358        | 0.003 (0.000)    | 0.122 (0.006)    | 0 (0.000) |     1.99 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     4155 | 2024-02-18 | Sangal            | L   | 0.099      | -            | -                | -                | -         |    -0.27 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           10 |     4196 | 2024-02-16 | SINNERS           | L   | 0.088      | -            | -                | -                | -         |    -0.39 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            9 |     4202 | 2024-02-16 | B8                | L   | 0.088      | -            | -                | -                | -         |    -0.32 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            8 |     4204 | 2024-02-16 | SINNERS           | W   | 0.087      | 0.143        | 0.038 (0.000)    | 0.768 (0.010)    | -         |     2.37 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4345 | 2024-02-10 | Secret            | L   | 0.047      | -            | -                | -                | -         |    -1.09 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4388 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.021      | -            | -                | -                | -         |    -0.12 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4407 | 2024-02-04 | Metizport         | W   | 0.009      | -            | -                | -                | -         |     0.20 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4419 | 2024-02-04 | Zero Tenacity     | W   | 0.007      | -            | -                | -                | -         |     0.20 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4438 | 2024-02-03 | Nexus             | W   | 0.002      | -            | -                | -                | -         |     0.03 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4445 | 2024-02-03 | North Macedonia   | L   | 0.001      | -            | -                | -                | -         |    -0.02 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4447 | 2024-02-03 | Jake Bube         | W   | 0.001      | -            | -                | -                | -         |     0.00 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($297.22)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
