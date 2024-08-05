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
Final Rank Value (722.0) = Starting Rank Value (699.9) + Head To Head Adjustments (22.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.038[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.9
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 699.9


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
|           22 |     2411 | 2024-05-02 | 1WIN              | L   | 0.570      | -            | -                | -                | -         |    -4.21 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2481 | 2024-04-29 | Sashi             | L   | 0.549      | -            | -                | -                | -         |    -1.31 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2510 | 2024-04-27 | Zero Tenacity     | L   | 0.538      | -            | -                | -                | -         |    -2.33 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2780 | 2024-04-18 | Secret            | L   | 0.476      | -            | -                | -                | -         |   -11.20 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2805 | 2024-04-17 | Portugal          | L   | 0.471      | -            | -                | -                | -         |    -8.61 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2842 | 2024-04-16 | Passion UA        | W   | 0.464      | 0.384        | 0.172 (0.031)    | 1.000 (0.178)    | 0 (0.000) |    12.40 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2931 | 2024-04-11 | PARIVISION        | W   | 0.431      | 0.384        | 0.017 (0.003)    | 0.534 (0.088)    | 0 (0.000) |    11.92 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3254 | 2024-04-02 | ex-Guild Eagles   | W   | 0.369      | 0.384        | 0.007 (0.001)    | 0.218 (0.031)    | 0 (0.000) |     7.24 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3259 | 2024-04-01 | ex-Guild Eagles   | L   | 0.365      | -            | -                | -                | -         |    -4.41 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3331 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.332      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3338 | 2024-03-27 | FORZE             | W   | 0.331      | 0.143        | 0.058 (0.003)    | 0.175 (0.008)    | 0 (0.000) |     7.96 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3683 | 2024-03-10 | Young Ninjas      | L   | 0.217      | -            | -                | -                | -         |    -3.00 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3756 | 2024-03-07 | Sangal            | W   | 0.197      | 0.143        | 0.219 (0.006)    | 0.861 (0.024)    | 0 (0.000) |     5.72 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3832 | 2024-03-05 | Entropiq          | W   | 0.183      | 0.143        | 0.000 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     1.70 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3891 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.164      | 0.358        | 0.031 (0.002)    | 0.560 (0.033)    | 0 (0.000) |     4.25 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3979 | 2024-02-26 | Imperial fe       | W   | 0.129      | 0.143        | 0.128 (0.002)    | 0.299 (0.006)    | 0 (0.000) |     3.53 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4027 | 2024-02-24 | Portugal          | W   | 0.117      | 0.358        | 0.003 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     1.76 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4170 | 2024-02-18 | Sangal            | L   | 0.076      | -            | -                | -                | -         |    -0.17 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4210 | 2024-02-16 | SINNERS           | L   | 0.065      | -            | -                | -                | -         |    -0.16 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4216 | 2024-02-16 | B8                | L   | 0.064      | -            | -                | -                | -         |    -0.21 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4218 | 2024-02-16 | SINNERS           | W   | 0.064      | 0.143        | 0.037 (0.000)    | 0.797 (0.007)    | 0 (0.000) |     1.85 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4350 | 2024-02-10 | Secret            | L   | 0.023      | -            | -                | -                | -         |    -0.52 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($285.42)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
