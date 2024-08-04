### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [148](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  722.5<br />
<br />
Final Rank Value (722.5) = Starting Rank Value (700.2) + Head To Head Adjustments (22.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.2
- 400 + ( ( 0.147 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 700.2


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
|           23 |     2383 | 2024-05-02 | 1WIN              | L   | 0.573      | -            | -                | -                | -         |    -4.35 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           22 |     2453 | 2024-04-29 | Sashi             | L   | 0.553      | -            | -                | -                | -         |    -1.33 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     2482 | 2024-04-27 | Zero Tenacity     | L   | 0.542      | -            | -                | -                | -         |    -2.39 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2752 | 2024-04-18 | Secret            | L   | 0.480      | -            | -                | -                | -         |   -11.29 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     2777 | 2024-04-17 | Portugal          | L   | 0.474      | -            | -                | -                | -         |    -8.67 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     2814 | 2024-04-16 | Passion UA        | W   | 0.468      | 0.384        | 0.172 (0.031)    | 1.000 (0.180)    | 0 (0.000) |    12.45 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     2903 | 2024-04-11 | PARIVISION        | W   | 0.434      | 0.384        | 0.017 (0.003)    | 0.534 (0.089)    | 0 (0.000) |    12.00 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3226 | 2024-04-02 | ex-Guild Eagles   | W   | 0.373      | 0.384        | 0.007 (0.001)    | 0.219 (0.031)    | 0 (0.000) |     7.33 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3231 | 2024-04-01 | ex-Guild Eagles   | L   | 0.368      | -            | -                | -                | -         |    -4.42 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3303 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.335      | -            | -                | -                | -         |    -0.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3310 | 2024-03-27 | FORZE             | W   | 0.335      | 0.143        | 0.058 (0.003)    | 0.177 (0.008)    | 0 (0.000) |     8.05 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3655 | 2024-03-10 | Young Ninjas      | L   | 0.221      | -            | -                | -                | -         |    -3.04 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3728 | 2024-03-07 | Sangal            | W   | 0.201      | 0.143        | 0.219 (0.006)    | 0.861 (0.025)    | 0 (0.000) |     5.81 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     3804 | 2024-03-05 | Entropiq          | W   | 0.186      | 0.143        | 0.000 (0.000)    | 0.038 (0.001)    | 0 (0.000) |     1.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     3863 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.167      | 0.358        | 0.031 (0.002)    | 0.560 (0.034)    | 0 (0.000) |     4.34 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            8 |     3951 | 2024-02-26 | Imperial fe       | W   | 0.133      | 0.143        | 0.128 (0.002)    | 0.299 (0.006)    | 0 (0.000) |     3.62 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            7 |     3999 | 2024-02-24 | Portugal          | W   | 0.121      | 0.358        | 0.003 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     1.81 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4142 | 2024-02-18 | Sangal            | L   | 0.079      | -            | -                | -                | -         |    -0.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4182 | 2024-02-16 | SINNERS           | L   | 0.068      | -            | -                | -                | -         |    -0.22 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4188 | 2024-02-16 | B8                | L   | 0.068      | -            | -                | -                | -         |    -0.23 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4190 | 2024-02-16 | SINNERS           | W   | 0.067      | 0.143        | 0.037 (0.000)    | 0.757 (0.007)    | 0 (0.000) |     1.90 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4322 | 2024-02-10 | Secret            | L   | 0.027      | -            | -                | -                | -         |    -0.59 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4364 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.000      | -            | -                | -                | -         |    -0.00 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($287.14)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
