### Roster Details<br />
Team Name: HOTU<br />
Roster: anttzz, fineshine52, lampada, mizu, Re1GN<br />
Global Rank: [116](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [84]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  793.5<br />
<br />
Final Rank Value (793.5) = Starting Rank Value (742.8) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.320[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.175<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 742.8
- 400 + ( ( 0.175 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 742.8


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
|           10 |       30 | 2024-09-05 | MOUZ NXT       | W   | 1.000      | 0.372        | 0.111 (0.041)    | 0.845 (0.315)    | 0 (0.000) |    24.58 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            9 |       48 | 2024-09-05 | RUSH B         | W   | 1.000      | 0.384        | 0.025 (0.010)    | 0.316 (0.121)    | 0 (0.000) |    21.76 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            8 |      111 | 2024-09-03 | Enterprise     | W   | 1.000      | 0.372        | 0.039 (0.015)    | 0.720 (0.268)    | 0 (0.000) |    20.07 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            7 |      204 | 2024-08-30 | SINNERS        | L   | 1.000      | -            | -                | -                | -         |    -2.61 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            6 |      776 | 2024-08-15 | QUAZAR         | L   | 1.000      | -            | -                | -                | -         |   -24.60 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            5 |      784 | 2024-08-15 | KOI            | W   | 1.000      | 0.143        | 0.053 (0.008)    | 0.330 (0.047)    | 0 (0.000) |    23.65 | anttzz, fineshine52, lampada, mizu, Re1GN      |
|            4 |     2239 | 2024-06-13 | VP.Prodigy     | L   | 0.632      | -            | -                | -                | -         |    -6.55 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            3 |     2767 | 2024-05-31 | CYBERSHOKE     | L   | 0.545      | -            | -                | -                | -         |    -4.30 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            2 |     2775 | 2024-05-30 | Spirit Academy | L   | 0.540      | -            | -                | -                | -         |    -7.80 | anttzz, fineshine52, lampada, mizu, swiftsteel |
|            1 |     2805 | 2024-05-29 | LEON           | W   | 0.534      | 0.372        | 0.005 (0.001)    | 0.084 (0.017)    | 0 (0.000) |     6.49 | anttzz, fineshine52, lampada, mizu, swiftsteel |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,629.11)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
