### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, myltsi, podi, teme<br />
Global Rank: [147](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  720.8<br />
<br />
Final Rank Value (720.8) = Starting Rank Value (732.0) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.033[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.0
- 400 + ( ( 0.161 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 732.0


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
|           20 |     2183 | 2024-05-06 | Permitta        | L   | 0.624      | -            | -                | -                | -         |    -5.07 | 2high, HENU, myltsi, podi, teme |
|           19 |     2194 | 2024-05-05 | Heimo           | L   | 0.619      | -            | -                | -                | -         |   -10.62 | 2high, HENU, myltsi, podi, teme |
|           18 |     2203 | 2024-05-05 | jefet           | W   | 0.618      | 0.306        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     4.71 | 2high, HENU, myltsi, podi, teme |
|           17 |     2218 | 2024-05-04 | TMVG            | W   | 0.611      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.52 | 2high, HENU, myltsi, podi, teme |
|           16 |     2238 | 2024-05-03 | Nexus           | W   | 0.604      | 0.435        | 0.014 (0.004)    | 0.465 (0.122)    | 0 (0.000) |    12.17 | 2high, HENU, myltsi, podi, teme |
|           15 |     2270 | 2024-05-01 | Enterprise      | L   | 0.593      | -            | -                | -                | -         |    -5.49 | 2high, HENU, myltsi, podi, teme |
|           14 |     2288 | 2024-05-01 | Sampi           | L   | 0.590      | -            | -                | -                | -         |    -4.54 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2304 | 2024-04-30 | Endpoint        | L   | 0.584      | -            | -                | -                | -         |    -4.99 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2316 | 2024-04-29 | RUSH B          | L   | 0.580      | -            | -                | -                | -         |    -6.05 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2347 | 2024-04-28 | Heimo           | L   | 0.571      | -            | -                | -                | -         |   -10.49 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2481 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.531      | -            | -                | -                | -         |    -4.23 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2528 | 2024-04-20 | SINNERS         | W   | 0.518      | 0.371        | 0.038 (0.007)    | 0.721 (0.138)    | 0 (0.000) |    13.96 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2582 | 2024-04-19 | Viperio         | L   | 0.510      | -            | -                | -                | -         |   -10.49 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2628 | 2024-04-18 | MOUZ NXT        | L   | 0.504      | -            | -                | -                | -         |    -2.46 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2690 | 2024-04-16 | 1WIN            | L   | 0.492      | -            | -                | -                | -         |    -4.50 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2710 | 2024-04-15 | Sampi           | W   | 0.485      | 0.371        | 0.028 (0.005)    | 1.000 (0.180)    | 0 (0.000) |    11.13 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2714 | 2024-04-15 | Viperio         | W   | 0.484      | 0.143        | 0.002 (0.000)    | 0.038 (0.003)    | 0 (0.000) |     5.37 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2787 | 2024-04-11 | Secret          | W   | 0.457      | 0.371        | 0.000 (0.000)    | 0.061 (0.010)    | 0 (0.000) |     3.75 | HENU, myltsi, podi, S1rva, teme |
|            2 |     3869 | 2024-02-24 | HAVU            | W   | 0.147      | 0.306        | 0.001 (0.000)    | 0.162 (0.007)    | 1 (0.147) |     2.21 | HENU, myltsi, podi, S1rva, teme |
|            1 |     3885 | 2024-02-24 | ex-sYnck        | W   | 0.144      | 0.306        | 0.000 (0.000)    | 0.018 (0.001)    | 1 (0.144) |     0.96 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,544.40)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.619 | $1,608.00      | $995.00         |
| 2024-02-24 |      0.147 | $3,748.00      | $549.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
