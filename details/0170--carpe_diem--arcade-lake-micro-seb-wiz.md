### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  664.8<br />
<br />
Final Rank Value (664.8) = Starting Rank Value (674.5) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.5
- 400 + ( ( 0.134 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 674.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     2913 | 2024-04-11 | Mythic           | W   | 0.434      | 0.477        | 0.010 (0.002)    | 0.299 (0.062)    | 0 (0.000) |     9.04 | arcade, Lake, micro, Seb, wiz |
|           17 |     2915 | 2024-04-11 | Mythic           | L   | 0.433      | -            | -                | -                | -         |    -4.68 | arcade, Lake, micro, Seb, wiz |
|           16 |     3003 | 2024-04-09 | NRG              | L   | 0.420      | -            | -                | -                | -         |    -3.32 | arcade, Lake, micro, Seb, wiz |
|           15 |     3006 | 2024-04-09 | NRG              | L   | 0.420      | -            | -                | -                | -         |    -3.41 | arcade, Lake, micro, Seb, wiz |
|           14 |     3130 | 2024-04-04 | Phoenix          | L   | 0.387      | -            | -                | -                | -         |    -4.94 | arcade, Lake, micro, Seb, wiz |
|           13 |     3135 | 2024-04-04 | Phoenix          | L   | 0.387      | -            | -                | -                | -         |    -5.10 | arcade, Lake, micro, Seb, wiz |
|           12 |     3309 | 2024-03-27 | Party Astronauts | L   | 0.334      | -            | -                | -                | -         |    -2.03 | arcade, Lake, micro, Seb, wiz |
|           11 |     3312 | 2024-03-27 | Party Astronauts | L   | 0.334      | -            | -                | -                | -         |    -2.07 | arcade, Lake, micro, Seb, wiz |
|           10 |     3528 | 2024-03-15 | Elevate          | L   | 0.254      | -            | -                | -                | -         |    -1.17 | arcade, Lake, micro, Seb, wiz |
|            9 |     3530 | 2024-03-15 | Elevate          | L   | 0.254      | -            | -                | -                | -         |    -1.18 | arcade, Lake, micro, Seb, wiz |
|            8 |     3588 | 2024-03-13 | Party Astronauts | L   | 0.239      | -            | -                | -                | -         |    -1.51 | arcade, Lake, micro, Seb, wiz |
|            7 |     3628 | 2024-03-12 | NRG              | W   | 0.233      | 0.143        | 0.020 (0.001)    | 0.521 (0.017)    | 0 (0.000) |     5.32 | arcade, Lake, micro, Seb, wiz |
|            6 |     3762 | 2024-03-06 | Limitless        | W   | 0.194      | 0.477        | 0.001 (0.000)    | 0.167 (0.015)    | 0 (0.000) |     2.86 | arcade, Lake, micro, Seb, wiz |
|            5 |     3765 | 2024-03-06 | Limitless        | W   | 0.194      | 0.477        | 0.001 (0.000)    | 0.167 (0.015)    | 0 (0.000) |     2.90 | arcade, Lake, micro, Seb, wiz |
|            4 |     4259 | 2024-02-14 | Rocket           | W   | 0.054      | 0.477        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.45 | arcade, Lake, micro, Seb, wiz |
|            3 |     4261 | 2024-02-14 | Rocket           | L   | 0.054      | -            | -                | -                | -         |    -1.25 | arcade, Lake, micro, Seb, wiz |
|            2 |     4299 | 2024-02-13 | FLUFFY AIMERS    | W   | 0.047      | 0.477        | 0.010 (0.000)    | 0.101 (0.002)    | 0 (0.000) |     0.92 | arcade, Lake, micro, Seb, wiz |
|            1 |     4302 | 2024-02-13 | FLUFFY AIMERS    | L   | 0.047      | -            | -                | -                | -         |    -0.57 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,652.78)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
