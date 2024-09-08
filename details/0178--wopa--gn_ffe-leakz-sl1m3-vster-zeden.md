### Roster Details<br />
Team Name: WOPA<br />
Roster: Gnøffe, leakz, sL1m3, Vster, zEden<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
<br />
Final Rank Value:  630.8<br />
<br />
Final Rank Value (630.8) = Starting Rank Value (640.6) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.6
- 400 + ( ( 0.124 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 640.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      699 | 2024-08-20 | Grannys Knockers | L   | 1.000      | -            | -                | -                | -         |   -12.41 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|           13 |      733 | 2024-08-19 | ALTERNATE aTTaX  | L   | 1.000      | -            | -                | -                | -         |    -8.06 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|           12 |     1648 | 2024-07-21 | Sampi            | L   | 0.874      | -            | -                | -                | -         |    -6.22 | Gnøffe, leakz, sL1m3, Topa, zEden   |
|           11 |     1735 | 2024-07-19 | VP.Prodigy       | W   | 0.859      | 0.435        | 0.020 (0.007)    | 0.245 (0.091)    | 0 (0.000) |    19.70 | Gnøffe, leakz, sL1m3, Topa, zEden   |
|           10 |     1861 | 2024-07-17 | GUN5             | L   | 0.846      | -            | -                | -                | -         |    -3.80 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|            9 |     1959 | 2024-07-15 | Passion UA       | L   | 0.832      | -            | -                | -                | -         |    -2.90 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|            8 |     2166 | 2024-06-16 | FLuffy Gangsters | W   | 0.641      | 0.143        | 0.000 (0.000)    | 0.357 (0.033)    | 0 (0.000) |     9.30 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            7 |     2294 | 2024-06-12 | The Prodigies    | W   | 0.615      | 0.143        | 0.000 (0.000)    | 0.063 (0.006)    | 0 (0.000) |     7.55 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            6 |     2306 | 2024-06-12 | CPH Wolves       | L   | 0.614      | -            | -                | -                | -         |    -5.83 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            5 |     2315 | 2024-06-11 | ADEPTS           | W   | 0.608      | 0.143        | 0.002 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     9.59 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            4 |     2779 | 2024-06-01 | Illuminar        | L   | 0.539      | -            | -                | -                | -         |   -11.04 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            3 |     3175 | 2024-05-17 | LEON             | L   | 0.440      | -            | -                | -                | -         |    -6.57 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            2 |     3321 | 2024-05-14 | Secret           | W   | 0.420      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | 0 (0.000) |     4.34 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            1 |     3339 | 2024-05-13 | VP.Prodigy       | L   | 0.414      | -            | -                | -                | -         |    -3.49 | brzer, Gnøffe, leakz, LUMSEN, Vster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($221.23)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
