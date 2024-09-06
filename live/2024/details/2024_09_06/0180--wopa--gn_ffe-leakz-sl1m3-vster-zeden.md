### Roster Details<br />
Team Name: WOPA<br />
Roster: Gnøffe, leakz, sL1m3, Vster, zEden<br />
Global Rank: [180](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [117]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  633.7<br />
<br />
Final Rank Value (633.7) = Starting Rank Value (643.4) + Head To Head Adjustments (-9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.242[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.4
- 400 + ( ( 0.125 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 643.4


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
|           14 |      662 | 2024-08-20 | Grannys Knockers | L   | 1.000      | -            | -                | -                | -         |   -12.38 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|           13 |      696 | 2024-08-19 | ALTERNATE aTTaX  | L   | 1.000      | -            | -                | -                | -         |    -8.02 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|           12 |     1611 | 2024-07-21 | Sampi            | L   | 0.886      | -            | -                | -                | -         |    -6.20 | Gnøffe, leakz, sL1m3, Topa, zEden   |
|           11 |     1698 | 2024-07-19 | VP.Prodigy       | W   | 0.871      | 0.435        | 0.020 (0.007)    | 0.257 (0.097)    | 0 (0.000) |    20.05 | Gnøffe, leakz, sL1m3, Topa, zEden   |
|           10 |     1824 | 2024-07-17 | GUN5             | L   | 0.857      | -            | -                | -                | -         |    -3.78 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|            9 |     1922 | 2024-07-15 | Passion UA       | L   | 0.844      | -            | -                | -                | -         |    -2.97 | Gnøffe, leakz, sL1m3, Vster, zEden  |
|            8 |     2129 | 2024-06-16 | FLuffy Gangsters | W   | 0.652      | 0.143        | 0.000 (0.000)    | 0.329 (0.031)    | 0 (0.000) |     9.18 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            7 |     2257 | 2024-06-12 | The Prodigies    | W   | 0.627      | 0.143        | 0.000 (0.000)    | 0.066 (0.006)    | 0 (0.000) |     7.71 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            6 |     2269 | 2024-06-12 | CPH Wolves       | L   | 0.626      | -            | -                | -                | -         |    -5.93 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            5 |     2278 | 2024-06-11 | ADEPTS           | W   | 0.620      | 0.143        | 0.002 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     9.79 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            4 |     2742 | 2024-06-01 | Illuminar        | L   | 0.551      | -            | -                | -                | -         |   -11.29 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            3 |     3138 | 2024-05-17 | LEON             | L   | 0.452      | -            | -                | -                | -         |    -6.74 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            2 |     3284 | 2024-05-14 | Secret           | W   | 0.432      | 0.143        | 0.000 (0.000)    | 0.026 (0.002)    | 0 (0.000) |     4.46 | brzer, Gnøffe, leakz, LUMSEN, Vster |
|            1 |     3302 | 2024-05-13 | VP.Prodigy       | L   | 0.426      | -            | -                | -                | -         |    -3.54 | brzer, Gnøffe, leakz, LUMSEN, Vster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($225.52)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
