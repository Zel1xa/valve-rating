### Roster Details<br />
Team Name: 777<br />
Roster: Hagmeister, qzr, SLY, Viktha, Wenba<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
<br />
Final Rank Value:  644.1<br />
<br />
Final Rank Value (644.1) = Starting Rank Value (705.8) + Head To Head Adjustments (-61.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.354[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 705.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |       29 | 2024-08-05 | ECSTATIC      | L   | 1.000      | -            | -                | -                | -         |   -19.95 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           19 |       35 | 2024-08-05 | TSM           | L   | 1.000      | -            | -                | -                | -         |    -4.72 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           18 |      580 | 2024-07-20 | Heimo         | L   | 1.000      | -            | -                | -                | -         |   -16.85 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           17 |      594 | 2024-07-19 | INFINITE      | L   | 1.000      | -            | -                | -                | -         |   -20.20 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           16 |      971 | 2024-07-06 | Revenant      | L   | 0.993      | -            | -                | -                | -         |   -11.31 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           15 |     1054 | 2024-06-16 | CPH Wolves    | L   | 0.859      | -            | -                | -                | -         |   -10.31 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           14 |     1088 | 2024-06-15 | The Prodigies | W   | 0.852      | 0.143        | 0.000 (0.000)    | 0.090 (0.011)    | 0 (0.000) |     8.10 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           13 |     1191 | 2024-06-12 | ADEPTS        | W   | 0.832      | 0.143        | 0.002 (0.000)    | 0.026 (0.003)    | 0 (0.000) |    10.86 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           12 |     1205 | 2024-06-11 | The Prodigies | L   | 0.826      | -            | -                | -                | -         |   -17.92 | Hagmeister, qzr, SLY, Viktha, Wenba          |
|           11 |     1657 | 2024-06-01 | VP.Prodigy    | L   | 0.759      | -            | -                | -                | -         |    -6.40 | Affava, Hagmeister, qzr, Viktha, Wenba       |
|           10 |     1790 | 2024-05-26 | Metizport X   | W   | 0.720      | 0.322        | 0.005 (0.001)    | 0.024 (0.006)    | 0 (0.000) |     8.99 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            9 |     2015 | 2024-05-18 | DMS           | L   | 0.666      | -            | -                | -                | -         |    -5.33 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            8 |     2064 | 2024-05-17 | Space         | W   | 0.658      | 0.143        | 0.006 (0.001)    | 0.429 (0.040)    | 0 (0.000) |    13.74 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            7 |     2094 | 2024-05-16 | Rounds        | W   | 0.652      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.99 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            6 |     2130 | 2024-05-15 | GUN5          | L   | 0.647      | -            | -                | -                | -         |    -4.61 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            5 |     2273 | 2024-05-11 | Metizport X   | W   | 0.620      | 0.322        | 0.005 (0.001)    | 0.024 (0.005)    | 0 (0.000) |     8.14 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            4 |     2554 | 2024-04-27 | Sashi         | L   | 0.527      | -            | -                | -                | -         |    -1.15 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            3 |     2565 | 2024-04-27 | Preasy        | W   | 0.526      | 0.336        | 0.008 (0.001)    | 0.216 (0.038)    | 0 (0.000) |     9.91 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            2 |     2934 | 2024-04-13 | Norway        | L   | 0.433      | -            | -                | -                | -         |    -6.88 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |
|            1 |     3541 | 2024-03-17 | INFURITY      | W   | 0.254      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.22 | Affava, Hagmeister, MadeInRed, Viktha, Wenba |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,805.03)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      0.720 | $3,864.00      | $2,782.08       |
| 2024-04-27 |      0.527 | $2,655.00      | $1,400.51       |
| 2024-04-13 |      0.433 | $1,436.00      | $622.43         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
