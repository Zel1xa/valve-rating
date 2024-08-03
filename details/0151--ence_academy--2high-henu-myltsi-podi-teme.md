### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, myltsi, podi, teme<br />
Global Rank: [151](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  714.6<br />
<br />
Final Rank Value (714.6) = Starting Rank Value (724.6) + Head To Head Adjustments (-10.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.029[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 724.6
- 400 + ( ( 0.159 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 724.6


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
|           20 |     2230 | 2024-05-06 | Permitta        | L   | 0.605      | -            | -                | -                | -         |    -4.64 | 2high, HENU, myltsi, podi, teme |
|           19 |     2241 | 2024-05-05 | Heimo           | L   | 0.600      | -            | -                | -                | -         |   -10.22 | 2high, HENU, myltsi, podi, teme |
|           18 |     2250 | 2024-05-05 | jefet           | W   | 0.599      | 0.306        | 0.001 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     4.64 | 2high, HENU, myltsi, podi, teme |
|           17 |     2265 | 2024-05-04 | TMVG            | W   | 0.592      | 0.306        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.54 | 2high, HENU, myltsi, podi, teme |
|           16 |     2285 | 2024-05-03 | Nexus           | W   | 0.584      | 0.435        | 0.014 (0.003)    | 0.441 (0.112)    | 0 (0.000) |    11.87 | 2high, HENU, myltsi, podi, teme |
|           15 |     2317 | 2024-05-01 | Enterprise      | L   | 0.574      | -            | -                | -                | -         |    -5.24 | 2high, HENU, myltsi, podi, teme |
|           14 |     2335 | 2024-05-01 | Sampi           | L   | 0.571      | -            | -                | -                | -         |    -4.29 | HENU, myltsi, podi, S1rva, teme |
|           13 |     2351 | 2024-04-30 | Endpoint        | L   | 0.565      | -            | -                | -                | -         |    -4.74 | HENU, myltsi, podi, S1rva, teme |
|           12 |     2363 | 2024-04-29 | RUSH B          | L   | 0.561      | -            | -                | -                | -         |    -5.70 | HENU, myltsi, podi, S1rva, teme |
|           11 |     2394 | 2024-04-28 | Heimo           | L   | 0.552      | -            | -                | -                | -         |   -10.06 | HENU, myltsi, podi, S1rva, teme |
|           10 |     2527 | 2024-04-22 | ALTERNATE aTTaX | L   | 0.512      | -            | -                | -                | -         |    -4.00 | HENU, myltsi, podi, S1rva, teme |
|            9 |     2574 | 2024-04-20 | SINNERS         | W   | 0.499      | 0.371        | 0.037 (0.007)    | 0.784 (0.145)    | 0 (0.000) |    13.91 | HENU, myltsi, podi, S1rva, teme |
|            8 |     2628 | 2024-04-19 | Viperio         | L   | 0.491      | -            | -                | -                | -         |   -10.00 | HENU, myltsi, podi, S1rva, teme |
|            7 |     2674 | 2024-04-18 | MOUZ NXT        | L   | 0.485      | -            | -                | -                | -         |    -2.42 | HENU, myltsi, podi, S1rva, teme |
|            6 |     2736 | 2024-04-16 | 1WIN            | L   | 0.473      | -            | -                | -                | -         |    -4.19 | HENU, myltsi, podi, S1rva, teme |
|            5 |     2756 | 2024-04-15 | Sampi           | W   | 0.466      | 0.371        | 0.028 (0.005)    | 1.000 (0.173)    | 0 (0.000) |    10.78 | HENU, myltsi, podi, S1rva, teme |
|            4 |     2760 | 2024-04-15 | Viperio         | W   | 0.465      | 0.143        | 0.001 (0.000)    | 0.039 (0.003)    | 0 (0.000) |     5.25 | HENU, myltsi, podi, S1rva, teme |
|            3 |     2833 | 2024-04-11 | Secret          | W   | 0.438      | 0.371        | 0.000 (0.000)    | 0.061 (0.010)    | 0 (0.000) |     3.68 | HENU, myltsi, podi, S1rva, teme |
|            2 |     3907 | 2024-02-24 | HAVU            | W   | 0.128      | 0.306        | 0.001 (0.000)    | 0.166 (0.006)    | 1 (0.128) |     1.93 | HENU, myltsi, podi, S1rva, teme |
|            1 |     3923 | 2024-02-24 | ex-sYnck        | W   | 0.125      | 0.306        | 0.000 (0.000)    | 0.017 (0.001)    | 1 (0.125) |     0.85 | HENU, myltsi, podi, S1rva, teme |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,442.56)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      0.600 | $1,608.00      | $964.43         |
| 2024-02-24 |      0.128 | $3,748.00      | $478.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
