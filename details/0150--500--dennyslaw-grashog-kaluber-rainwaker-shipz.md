### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [150](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  724.5<br />
<br />
Final Rank Value (724.5) = Starting Rank Value (703.2) + Head To Head Adjustments (21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.306[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.2
- 400 + ( ( 0.147 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 703.2


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
|           22 |     2457 | 2024-05-02 | 1WIN              | L   | 0.559      | -            | -                | -                | -         |    -4.00 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           21 |     2527 | 2024-04-29 | Sashi             | L   | 0.538      | -            | -                | -                | -         |    -1.29 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2556 | 2024-04-27 | Zero Tenacity     | L   | 0.527      | -            | -                | -                | -         |    -2.26 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2826 | 2024-04-18 | Secret            | L   | 0.465      | -            | -                | -                | -         |   -10.97 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2851 | 2024-04-17 | Portugal          | L   | 0.460      | -            | -                | -                | -         |    -8.46 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2888 | 2024-04-16 | Passion UA        | W   | 0.453      | 0.384        | 0.173 (0.030)    | 1.000 (0.174)    | 0 (0.000) |    12.16 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     2977 | 2024-04-11 | PARIVISION        | W   | 0.420      | 0.384        | 0.049 (0.008)    | 0.590 (0.095)    | 0 (0.000) |    11.91 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3300 | 2024-04-02 | ex-Guild Eagles   | W   | 0.358      | 0.384        | 0.007 (0.001)    | 0.207 (0.028)    | 0 (0.000) |     7.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3305 | 2024-04-01 | ex-Guild Eagles   | L   | 0.354      | -            | -                | -                | -         |    -4.25 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3377 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.321      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3384 | 2024-03-27 | FORZE             | W   | 0.320      | 0.143        | 0.057 (0.003)    | 0.163 (0.007)    | 0 (0.000) |     7.66 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3729 | 2024-03-10 | Young Ninjas      | L   | 0.206      | -            | -                | -                | -         |    -2.82 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3802 | 2024-03-07 | Sangal            | W   | 0.186      | 0.143        | 0.288 (0.008)    | 0.858 (0.023)    | 0 (0.000) |     5.46 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3878 | 2024-03-05 | Entropiq          | W   | 0.172      | 0.143        | 0.000 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     1.58 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3937 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.153      | 0.358        | 0.031 (0.002)    | 0.537 (0.029)    | 0 (0.000) |     3.97 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4025 | 2024-02-26 | Imperial fe       | W   | 0.118      | 0.143        | 0.128 (0.002)    | 0.287 (0.005)    | 0 (0.000) |     3.22 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4073 | 2024-02-24 | Portugal          | W   | 0.106      | 0.358        | 0.003 (0.000)    | 0.115 (0.004)    | 0 (0.000) |     1.57 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4216 | 2024-02-18 | Sangal            | L   | 0.065      | -            | -                | -                | -         |    -0.13 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4256 | 2024-02-16 | SINNERS           | L   | 0.054      | -            | -                | -                | -         |    -0.13 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4262 | 2024-02-16 | B8                | L   | 0.053      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4264 | 2024-02-16 | SINNERS           | W   | 0.053      | 0.143        | 0.037 (0.000)    | 0.800 (0.006)    | 0 (0.000) |     1.53 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4396 | 2024-02-10 | Secret            | L   | 0.012      | -            | -                | -                | -         |    -0.27 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($279.93)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
