### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, myltsi, podi, teme<br />
Global Rank: [149](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  720.8<br />
<br />
Final Rank Value (720.8) = Starting Rank Value (731.8) + Head To Head Adjustments (-10.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.032[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.8
- 400 + ( ( 0.161 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 731.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2274 | 2024-05-06 | Permitta        | L   | 0.619      | -            | -                | -                | -         |    -4.93 | 2high, HENU, myltsi, podi, teme |
|           19 |     2285 | 2024-05-05 | Heimo           | L   | 0.614      | -            | -                | -                | -         |   -10.55 | 2high, HENU, myltsi, podi, teme |
|           18 |     2294 | 2024-05-05 | jefet           | W   | 0.613      | 0.306        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     4.67 | 2high, HENU, myltsi, podi, teme |
|           17 |     2309 | 2024-05-04 | TMVG            | W   | 0.607      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.42 | 2high, HENU, myltsi, podi, teme |
|           16 |     2329 | 2024-05-03 | Nexus           | W   | 0.599      | 0.435        | 0.014 (0.004)    | 0.504 (0.131)    | 0 (0.000) |    12.10 | 2high, HENU, myltsi, podi, teme |
|           15 |     2363 | 2024-05-01 | Enterprise      | L   | 0.588      | -            | -                | -                | -         |    -5.60 | 2high, HENU, myltsi, podi, teme |
|           14 |     2381 | 2024-05-01 | Sampi           | L   | 0.586      | -            | -                | -                | -         |    -4.70 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2398 | 2024-04-30 | Endpoint        | L   | 0.580      | -            | -                | -                | -         |    -4.64 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2410 | 2024-04-29 | RUSH B          | L   | 0.575      | -            | -                | -                | -         |    -6.02 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2441 | 2024-04-28 | Heimo           | L   | 0.567      | -            | -                | -                | -         |   -10.41 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2578 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.526      | -            | -                | -                | -         |    -4.24 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2628 | 2024-04-20 | SINNERS         | W   | 0.513      | 0.371        | 0.038 (0.007)    | 0.768 (0.146)    | 0 (0.000) |    13.96 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2683 | 2024-04-19 | Viperio         | L   | 0.506      | -            | -                | -                | -         |   -10.40 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2730 | 2024-04-18 | MOUZ NXT        | L   | 0.500      | -            | -                | -                | -         |    -2.33 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2794 | 2024-04-16 | 1WIN            | L   | 0.487      | -            | -                | -                | -         |    -4.44 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2814 | 2024-04-15 | Sampi           | W   | 0.481      | 0.371        | 0.028 (0.005)    | 1.000 (0.178)    | 0 (0.000) |    11.05 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2818 | 2024-04-15 | Viperio         | W   | 0.480      | 0.143        | 0.002 (0.000)    | 0.038 (0.003)    | 0 (0.000) |     5.32 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2892 | 2024-04-11 | Secret          | W   | 0.453      | 0.371        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.72 | HENU, myltsi, podi, S1rva, teme |
|            2 |     4002 | 2024-02-24 | HAVU            | W   | 0.142      | 0.306        | 0.001 (0.000)    | 0.168 (0.007)    | 1 (0.142) |     2.14 | HENU, myltsi, podi, S1rva, teme |
|            1 |     4020 | 2024-02-24 | ex-sYnck        | W   | 0.140      | 0.306        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.140) |     0.93 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,521.16)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.614 | $1,608.00      | $988.03         |
| 2024-02-24 |      0.142 | $3,748.00      | $533.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
