### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: HENU, myltsi, podi, S1rva, teme<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.5<br />
<br />
Final Rank Value (706.5) = Starting Rank Value (712.6) + Head To Head Adjustments (-6.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.027[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 712.6
- 400 + ( ( 0.153 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 712.6


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
|           14 |     2441 | 2024-05-01 | Sampi           | L   | 0.562      | -            | -                | -                | -         |    -4.12 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2457 | 2024-04-30 | Endpoint        | L   | 0.557      | -            | -                | -                | -         |    -4.54 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2469 | 2024-04-29 | RUSH B          | L   | 0.552      | -            | -                | -                | -         |    -5.16 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2500 | 2024-04-28 | Heimo           | L   | 0.543      | -            | -                | -                | -         |    -9.70 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2634 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.503      | -            | -                | -                | -         |    -3.76 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2681 | 2024-04-20 | SINNERS         | W   | 0.490      | 0.371        | 0.037 (0.007)    | 0.797 (0.145)    | 0 (0.000) |    14.08 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2735 | 2024-04-19 | Viperio         | L   | 0.482      | -            | -                | -                | -         |    -9.62 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2781 | 2024-04-18 | MOUZ NXT        | L   | 0.476      | -            | -                | -                | -         |    -2.19 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2843 | 2024-04-16 | 1WIN            | L   | 0.464      | -            | -                | -                | -         |    -3.54 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2863 | 2024-04-15 | Sampi           | W   | 0.457      | 0.371        | 0.027 (0.005)    | 1.000 (0.169)    | 0 (0.000) |    10.71 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2867 | 2024-04-15 | Viperio         | W   | 0.456      | 0.143        | 0.001 (0.000)    | 0.037 (0.002)    | 0 (0.000) |     5.37 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2940 | 2024-04-11 | Secret          | W   | 0.429      | 0.371        | 0.000 (0.000)    | 0.058 (0.009)    | 0 (0.000) |     3.77 | HENU, myltsi, podi, S1rva, teme |
|            2 |     4022 | 2024-02-24 | HAVU            | W   | 0.119      | 0.306        | 0.001 (0.000)    | 0.160 (0.006)    | 1 (0.119) |     1.84 | HENU, myltsi, podi, S1rva, teme |
|            1 |     4038 | 2024-02-24 | ex-sYnck        | W   | 0.116      | 0.306        | 0.000 (0.000)    | 0.016 (0.001)    | 1 (0.116) |     0.83 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,394.70)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.591 | $1,608.00      | $950.06         |
| 2024-02-24 |      0.119 | $3,748.00      | $444.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
