### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: HENU, myltsi, podi, S1rva, teme<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.4<br />
<br />
Final Rank Value (706.4) = Starting Rank Value (713.6) + Head To Head Adjustments (-7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.6
- 400 + ( ( 0.153 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 713.6


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
|           14 |     2401 | 2024-05-01 | Sampi           | L   | 0.570      | -            | -                | -                | -         |    -4.16 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2417 | 2024-04-30 | Endpoint        | L   | 0.564      | -            | -                | -                | -         |    -4.60 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2429 | 2024-04-29 | RUSH B          | L   | 0.559      | -            | -                | -                | -         |    -5.49 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2460 | 2024-04-28 | Heimo           | L   | 0.550      | -            | -                | -                | -         |    -9.84 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2593 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.510      | -            | -                | -                | -         |    -3.84 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2640 | 2024-04-20 | SINNERS         | W   | 0.497      | 0.371        | 0.037 (0.007)    | 0.758 (0.140)    | 0 (0.000) |    13.92 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2694 | 2024-04-19 | Viperio         | L   | 0.489      | -            | -                | -                | -         |    -9.78 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2740 | 2024-04-18 | MOUZ NXT        | L   | 0.483      | -            | -                | -                | -         |    -2.24 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2802 | 2024-04-16 | 1WIN            | L   | 0.471      | -            | -                | -                | -         |    -4.05 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2822 | 2024-04-15 | Sampi           | W   | 0.464      | 0.371        | 0.027 (0.005)    | 1.000 (0.172)    | 0 (0.000) |    10.86 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2826 | 2024-04-15 | Viperio         | W   | 0.463      | 0.143        | 0.001 (0.000)    | 0.038 (0.002)    | 0 (0.000) |     5.43 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2899 | 2024-04-11 | Secret          | W   | 0.437      | 0.371        | 0.000 (0.000)    | 0.059 (0.009)    | 0 (0.000) |     3.82 | HENU, myltsi, podi, S1rva, teme |
|            2 |     3980 | 2024-02-24 | HAVU            | W   | 0.126      | 0.306        | 0.001 (0.000)    | 0.160 (0.006)    | 1 (0.126) |     1.96 | HENU, myltsi, podi, S1rva, teme |
|            1 |     3996 | 2024-02-24 | ex-sYnck        | W   | 0.123      | 0.306        | 0.000 (0.000)    | 0.016 (0.001)    | 1 (0.123) |     0.88 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,433.38)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.598 | $1,608.00      | $961.67         |
| 2024-02-24 |      0.126 | $3,748.00      | $471.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
