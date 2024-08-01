### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
<br />
Final Rank Value:  762.8<br />
<br />
Final Rank Value (762.8) = Starting Rank Value (727.1) + Head To Head Adjustments (35.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.063[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 727.1
- 400 + ( ( 0.159 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 727.1


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
|           27 |     2345 | 2024-05-02 | MOUZ NXT          | W   | 0.593      | 0.396        | 0.141 (0.033)    | 1.000 (0.235)    | 0 (0.000) |    15.65 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           26 |     2354 | 2024-05-02 | 1WIN              | L   | 0.592      | -            | -                | -                | -         |    -5.34 | dennyslaw, Grashog, KalubeR, Rainwaker, SHiPZ |
|           25 |     2426 | 2024-04-29 | Sashi             | L   | 0.572      | -            | -                | -                | -         |    -1.51 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           24 |     2455 | 2024-04-27 | Zero Tenacity     | L   | 0.560      | -            | -                | -                | -         |    -2.82 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           23 |     2733 | 2024-04-18 | Secret            | L   | 0.498      | -            | -                | -                | -         |   -12.11 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           22 |     2759 | 2024-04-17 | Portugal          | L   | 0.493      | -            | -                | -                | -         |    -9.44 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     2796 | 2024-04-16 | Passion UA        | W   | 0.486      | 0.384        | 0.173 (0.032)    | 1.000 (0.187)    | 0 (0.000) |    12.69 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           20 |     2887 | 2024-04-11 | PARIVISION        | W   | 0.453      | 0.384        | 0.018 (0.003)    | 0.451 (0.079)    | 0 (0.000) |    12.24 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           19 |     3218 | 2024-04-02 | ex-Guild Eagles   | W   | 0.391      | 0.384        | 0.007 (0.001)    | 0.224 (0.034)    | 0 (0.000) |     7.40 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           18 |     3223 | 2024-04-01 | ex-Guild Eagles   | L   | 0.387      | -            | -                | -                | -         |    -4.96 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           17 |     3296 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.354      | -            | -                | -                | -         |    -0.12 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3303 | 2024-03-27 | FORZE             | W   | 0.354      | 0.143        | 0.060 (0.003)    | 0.186 (0.009)    | 0 (0.000) |     8.30 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3657 | 2024-03-10 | Young Ninjas      | L   | 0.239      | -            | -                | -                | -         |    -3.49 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3731 | 2024-03-07 | Sangal            | W   | 0.219      | 0.143        | 0.221 (0.007)    | 0.823 (0.026)    | 0 (0.000) |     6.24 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3812 | 2024-03-05 | Entropiq          | W   | 0.205      | -            | -                | -                | 0 (0.000) |     1.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           12 |     3871 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.186      | 0.358        | 0.032 (0.002)    | 0.563 (0.038)    | 0 (0.000) |     4.71 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           11 |     3962 | 2024-02-26 | Imperial fe       | W   | 0.152      | 0.143        | 0.130 (0.003)    | 0.269 (0.006)    | 0 (0.000) |     4.07 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           10 |     4011 | 2024-02-24 | Portugal          | W   | 0.140      | 0.358        | 0.003 (0.000)    | 0.122 (0.006)    | 0 (0.000) |     1.97 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|            9 |     4159 | 2024-02-18 | Sangal            | L   | 0.098      | -            | -                | -                | -         |    -0.27 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            8 |     4200 | 2024-02-16 | SINNERS           | L   | 0.087      | -            | -                | -                | -         |    -0.38 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4206 | 2024-02-16 | B8                | L   | 0.086      | -            | -                | -                | -         |    -0.31 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4208 | 2024-02-16 | SINNERS           | W   | 0.086      | 0.143        | 0.038 (0.000)    | 0.768 (0.009)    | -         |     2.33 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4349 | 2024-02-10 | Secret            | L   | 0.045      | -            | -                | -                | -         |    -1.06 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4392 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.019      | -            | -                | -                | -         |    -0.11 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4411 | 2024-02-04 | Metizport         | W   | 0.007      | -            | -                | -                | -         |     0.17 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4423 | 2024-02-04 | Zero Tenacity     | W   | 0.006      | -            | -                | -                | -         |     0.16 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4442 | 2024-02-03 | Nexus             | W   | 0.000      | -            | -                | -                | -         |     0.00 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($296.53)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
