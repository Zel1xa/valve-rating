### Roster Details<br />
Team Name: HOTU<br />
Roster: anttzz, fineshine52, lampada, mizu, Re1GN<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  789.2<br />
<br />
Final Rank Value (789.2) = Starting Rank Value (738.1) + Head To Head Adjustments (51.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.074[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 738.1
- 400 + ( ( 0.175 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 738.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       67 | 2024-09-05 | MOUZ NXT       | W   | 1.000      | 0.372        | 0.111 (0.041)    | 0.813 (0.303)    | 0 (0.000) |    24.53 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            9 |       85 | 2024-09-05 | RUSH B         | W   | 1.000      | 0.384        | 0.026 (0.010)    | 0.304 (0.117)    | 0 (0.000) |    21.64 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            8 |      148 | 2024-09-03 | Enterprise     | W   | 1.000      | 0.372        | 0.039 (0.015)    | 0.697 (0.260)    | 0 (0.000) |    19.98 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            7 |      241 | 2024-08-30 | SINNERS        | L   | 1.000      | -            | -                | -                | -         |    -2.60 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            6 |      813 | 2024-08-15 | QUAZAR         | L   | 1.000      | -            | -                | -                | -         |   -24.50 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            5 |      821 | 2024-08-15 | KOI            | W   | 1.000      | 0.143        | 0.053 (0.008)    | 0.317 (0.045)    | 0 (0.000) |    23.59 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            4 |     2276 | 2024-06-13 | VP.Prodigy     | L   | 0.620      | -            | -                | -                | -         |    -6.47 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            3 |     2804 | 2024-05-31 | CYBERSHOKE     | L   | 0.533      | -            | -                | -                | -         |    -4.17 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            2 |     2812 | 2024-05-30 | Spirit Academy | L   | 0.528      | -            | -                | -                | -         |    -7.32 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            1 |     2842 | 2024-05-29 | LEON           | W   | 0.522      | 0.372        | 0.005 (0.001)    | 0.080 (0.016)    | 0 (0.000) |     6.38 | anttzz, fineshine52, lampada, mizu, swiftsteel |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,599.31)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
