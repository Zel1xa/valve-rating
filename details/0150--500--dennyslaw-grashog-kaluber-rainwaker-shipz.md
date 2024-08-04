### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.5<br />
<br />
Final Rank Value (722.5) = Starting Rank Value (700.1) + Head To Head Adjustments (22.4)<br />

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
|           22 |     2407 | 2024-05-02 | 1WIN              | L   | 0.572      | -            | -                | -                | -         |    -4.23 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2477 | 2024-04-29 | Sashi             | L   | 0.552      | -            | -                | -                | -         |    -1.32 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2506 | 2024-04-27 | Zero Tenacity     | L   | 0.540      | -            | -                | -                | -         |    -2.35 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2776 | 2024-04-18 | Secret            | L   | 0.478      | -            | -                | -                | -         |   -11.27 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2801 | 2024-04-17 | Portugal          | L   | 0.473      | -            | -                | -                | -         |    -8.65 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2838 | 2024-04-16 | Passion UA        | W   | 0.467      | 0.384        | 0.172 (0.031)    | 1.000 (0.179)    | 0 (0.000) |    12.45 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2927 | 2024-04-11 | PARIVISION        | W   | 0.433      | 0.384        | 0.017 (0.003)    | 0.534 (0.089)    | 0 (0.000) |    11.98 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3250 | 2024-04-02 | ex-Guild Eagles   | W   | 0.372      | 0.384        | 0.007 (0.001)    | 0.219 (0.031)    | 0 (0.000) |     7.29 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3255 | 2024-04-01 | ex-Guild Eagles   | L   | 0.367      | -            | -                | -                | -         |    -4.44 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3327 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.334      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3334 | 2024-03-27 | FORZE             | W   | 0.334      | 0.143        | 0.058 (0.003)    | 0.176 (0.008)    | 0 (0.000) |     8.02 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3679 | 2024-03-10 | Young Ninjas      | L   | 0.219      | -            | -                | -                | -         |    -3.03 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3752 | 2024-03-07 | Sangal            | W   | 0.199      | 0.143        | 0.219 (0.006)    | 0.861 (0.025)    | 0 (0.000) |     5.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3828 | 2024-03-05 | Entropiq          | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.73 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3887 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.166      | 0.358        | 0.031 (0.002)    | 0.560 (0.033)    | 0 (0.000) |     4.31 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3975 | 2024-02-26 | Imperial fe       | W   | 0.132      | 0.143        | 0.128 (0.002)    | 0.299 (0.006)    | 0 (0.000) |     3.59 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4023 | 2024-02-24 | Portugal          | W   | 0.120      | 0.358        | 0.003 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     1.79 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4166 | 2024-02-18 | Sangal            | L   | 0.078      | -            | -                | -                | -         |    -0.17 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4206 | 2024-02-16 | SINNERS           | L   | 0.067      | -            | -                | -                | -         |    -0.16 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4212 | 2024-02-16 | B8                | L   | 0.067      | -            | -                | -                | -         |    -0.22 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4214 | 2024-02-16 | SINNERS           | W   | 0.066      | 0.143        | 0.037 (0.000)    | 0.797 (0.008)    | 0 (0.000) |     1.92 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4346 | 2024-02-10 | Secret            | L   | 0.025      | -            | -                | -                | -         |    -0.57 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($286.61)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
