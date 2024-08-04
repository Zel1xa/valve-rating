### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: HENU, myltsi, podi, S1rva, teme<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  705.9<br />
<br />
Final Rank Value (705.9) = Starting Rank Value (713.0) + Head To Head Adjustments (-7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.0
- 400 + ( ( 0.153 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 713.0


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
|           14 |     2405 | 2024-05-01 | Sampi           | L   | 0.567      | -            | -                | -                | -         |    -4.14 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2421 | 2024-04-30 | Endpoint        | L   | 0.561      | -            | -                | -                | -         |    -4.57 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2433 | 2024-04-29 | RUSH B          | L   | 0.556      | -            | -                | -                | -         |    -5.46 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2464 | 2024-04-28 | Heimo           | L   | 0.547      | -            | -                | -                | -         |    -9.77 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2598 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.507      | -            | -                | -                | -         |    -3.81 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2645 | 2024-04-20 | SINNERS         | W   | 0.494      | 0.371        | 0.037 (0.007)    | 0.758 (0.139)    | 0 (0.000) |    13.84 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2699 | 2024-04-19 | Viperio         | L   | 0.486      | -            | -                | -                | -         |    -9.71 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2745 | 2024-04-18 | MOUZ NXT        | L   | 0.480      | -            | -                | -                | -         |    -2.22 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2807 | 2024-04-16 | 1WIN            | L   | 0.468      | -            | -                | -                | -         |    -4.02 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2827 | 2024-04-15 | Sampi           | W   | 0.461      | 0.371        | 0.027 (0.005)    | 1.000 (0.171)    | 0 (0.000) |    10.79 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2831 | 2024-04-15 | Viperio         | W   | 0.460      | 0.143        | 0.001 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     5.40 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2904 | 2024-04-11 | Secret          | W   | 0.434      | 0.371        | 0.000 (0.000)    | 0.058 (0.009)    | 0 (0.000) |     3.80 | HENU, myltsi, podi, S1rva, teme |
|            2 |     3986 | 2024-02-24 | HAVU            | W   | 0.123      | 0.306        | 0.001 (0.000)    | 0.160 (0.006)    | 1 (0.123) |     1.91 | HENU, myltsi, podi, S1rva, teme |
|            1 |     4002 | 2024-02-24 | ex-sYnck        | W   | 0.120      | 0.306        | 0.000 (0.000)    | 0.016 (0.001)    | 1 (0.120) |     0.86 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,417.02)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.595 | $1,608.00      | $956.76         |
| 2024-02-24 |      0.123 | $3,748.00      | $460.26         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
