### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, myltsi, podi, teme<br />
Global Rank: [149](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
<br />
Final Rank Value:  719.9<br />
<br />
Final Rank Value (719.9) = Starting Rank Value (731.0) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.032[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.0
- 400 + ( ( 0.161 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 731.0


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
|           20 |     2280 | 2024-05-06 | Permitta        | L   | 0.618      | -            | -                | -                | -         |    -4.95 | 2high, HENU, myltsi, podi, teme |
|           19 |     2291 | 2024-05-05 | Heimo           | L   | 0.613      | -            | -                | -                | -         |   -10.51 | 2high, HENU, myltsi, podi, teme |
|           18 |     2300 | 2024-05-05 | jefet           | W   | 0.612      | 0.306        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     4.67 | 2high, HENU, myltsi, podi, teme |
|           17 |     2315 | 2024-05-04 | TMVG            | W   | 0.605      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.26 | 2high, HENU, myltsi, podi, teme |
|           16 |     2335 | 2024-05-03 | Nexus           | W   | 0.598      | 0.435        | 0.014 (0.004)    | 0.504 (0.131)    | 0 (0.000) |    12.07 | 2high, HENU, myltsi, podi, teme |
|           15 |     2369 | 2024-05-01 | Enterprise      | L   | 0.587      | -            | -                | -                | -         |    -5.59 | 2high, HENU, myltsi, podi, teme |
|           14 |     2387 | 2024-05-01 | Sampi           | L   | 0.584      | -            | -                | -                | -         |    -4.69 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2404 | 2024-04-30 | Endpoint        | L   | 0.578      | -            | -                | -                | -         |    -4.63 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2416 | 2024-04-29 | RUSH B          | L   | 0.574      | -            | -                | -                | -         |    -6.00 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2447 | 2024-04-28 | Heimo           | L   | 0.565      | -            | -                | -                | -         |   -10.37 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2584 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.525      | -            | -                | -                | -         |    -4.22 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2634 | 2024-04-20 | SINNERS         | W   | 0.512      | 0.371        | 0.038 (0.007)    | 0.768 (0.146)    | 0 (0.000) |    13.91 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2689 | 2024-04-19 | Viperio         | L   | 0.504      | -            | -                | -                | -         |   -10.36 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2736 | 2024-04-18 | MOUZ NXT        | L   | 0.498      | -            | -                | -                | -         |    -2.32 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2800 | 2024-04-16 | 1WIN            | L   | 0.486      | -            | -                | -                | -         |    -4.40 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2820 | 2024-04-15 | Sampi           | W   | 0.479      | 0.371        | 0.028 (0.005)    | 1.000 (0.177)    | 0 (0.000) |    11.01 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2824 | 2024-04-15 | Viperio         | W   | 0.478      | 0.143        | 0.002 (0.000)    | 0.038 (0.003)    | 0 (0.000) |     5.31 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2898 | 2024-04-11 | Secret          | W   | 0.451      | 0.371        | 0.000 (0.000)    | 0.060 (0.010)    | 0 (0.000) |     3.71 | HENU, myltsi, podi, S1rva, teme |
|            2 |     4008 | 2024-02-24 | HAVU            | W   | 0.141      | 0.306        | 0.001 (0.000)    | 0.168 (0.007)    | 1 (0.141) |     2.12 | HENU, myltsi, podi, S1rva, teme |
|            1 |     4026 | 2024-02-24 | ex-sYnck        | W   | 0.138      | 0.306        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.138) |     0.92 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,512.24)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.613 | $1,608.00      | $985.35         |
| 2024-02-24 |      0.141 | $3,748.00      | $526.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
