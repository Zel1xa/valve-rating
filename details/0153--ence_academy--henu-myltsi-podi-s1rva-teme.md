### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: HENU, myltsi, podi, S1rva, teme<br />
Global Rank: [153](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.1<br />
<br />
Final Rank Value (706.1) = Starting Rank Value (711.8) + Head To Head Adjustments (-5.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.025[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.8
- 400 + ( ( 0.152 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 711.8


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
|           14 |     2473 | 2024-05-01 | Sampi           | L   | 0.553      | -            | -                | -                | -         |    -4.05 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2489 | 2024-04-30 | Endpoint        | L   | 0.547      | -            | -                | -                | -         |    -4.44 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2501 | 2024-04-29 | RUSH B          | L   | 0.542      | -            | -                | -                | -         |    -5.05 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2532 | 2024-04-28 | Heimo           | L   | 0.534      | -            | -                | -                | -         |    -9.49 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2666 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.493      | -            | -                | -                | -         |    -3.63 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2713 | 2024-04-20 | SINNERS         | W   | 0.480      | 0.371        | 0.037 (0.007)    | 0.790 (0.141)    | 0 (0.000) |    13.85 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2767 | 2024-04-19 | Viperio         | L   | 0.472      | -            | -                | -                | -         |    -9.40 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2813 | 2024-04-18 | MOUZ NXT        | L   | 0.467      | -            | -                | -                | -         |    -2.10 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2875 | 2024-04-16 | 1WIN            | L   | 0.454      | -            | -                | -                | -         |    -3.32 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2895 | 2024-04-15 | Sampi           | W   | 0.448      | 0.371        | 0.027 (0.004)    | 1.000 (0.166)    | 0 (0.000) |    10.48 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2899 | 2024-04-15 | Viperio         | W   | 0.447      | 0.143        | 0.001 (0.000)    | 0.036 (0.002)    | 0 (0.000) |     5.29 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2972 | 2024-04-11 | Secret          | W   | 0.420      | 0.371        | 0.000 (0.000)    | 0.055 (0.009)    | 0 (0.000) |     3.70 | HENU, myltsi, podi, S1rva, teme |
|            2 |     4054 | 2024-02-24 | HAVU            | W   | 0.109      | 0.306        | 0.001 (0.000)    | 0.152 (0.005)    | 1 (0.109) |     1.69 | HENU, myltsi, podi, S1rva, teme |
|            1 |     4070 | 2024-02-24 | ex-sYnck        | W   | 0.107      | 0.306        | 0.000 (0.000)    | 0.015 (0.000)    | 1 (0.107) |     0.77 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,344.12)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.581 | $1,608.00      | $934.87         |
| 2024-02-24 |      0.109 | $3,748.00      | $409.24         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
