### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Global Rank: [170](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  665.1<br />
<br />
Final Rank Value (665.1) = Starting Rank Value (675.0) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.0
- 400 + ( ( 0.134 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 675.0


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
|           18 |     2956 | 2024-04-11 | Mythic           | W   | 0.423      | 0.477        | 0.010 (0.002)    | 0.285 (0.057)    | 0 (0.000) |     8.79 | arcade, Lake, micro, Seb, wiz |
|           17 |     2958 | 2024-04-11 | Mythic           | L   | 0.422      | -            | -                | -                | -         |    -4.59 | arcade, Lake, micro, Seb, wiz |
|           16 |     3046 | 2024-04-09 | NRG              | L   | 0.409      | -            | -                | -                | -         |    -3.26 | arcade, Lake, micro, Seb, wiz |
|           15 |     3049 | 2024-04-09 | NRG              | L   | 0.409      | -            | -                | -                | -         |    -3.35 | arcade, Lake, micro, Seb, wiz |
|           14 |     3173 | 2024-04-04 | Phoenix          | L   | 0.376      | -            | -                | -                | -         |    -4.82 | arcade, Lake, micro, Seb, wiz |
|           13 |     3178 | 2024-04-04 | Phoenix          | L   | 0.376      | -            | -                | -                | -         |    -4.97 | arcade, Lake, micro, Seb, wiz |
|           12 |     3352 | 2024-03-27 | Party Astronauts | L   | 0.323      | -            | -                | -                | -         |    -1.99 | arcade, Lake, micro, Seb, wiz |
|           11 |     3355 | 2024-03-27 | Party Astronauts | L   | 0.323      | -            | -                | -                | -         |    -2.03 | arcade, Lake, micro, Seb, wiz |
|           10 |     3571 | 2024-03-15 | Elevate          | L   | 0.243      | -            | -                | -                | -         |    -1.13 | arcade, Lake, micro, Seb, wiz |
|            9 |     3573 | 2024-03-15 | Elevate          | L   | 0.243      | -            | -                | -                | -         |    -1.14 | arcade, Lake, micro, Seb, wiz |
|            8 |     3631 | 2024-03-13 | Party Astronauts | L   | 0.228      | -            | -                | -                | -         |    -1.47 | arcade, Lake, micro, Seb, wiz |
|            7 |     3671 | 2024-03-12 | NRG              | W   | 0.223      | 0.143        | 0.020 (0.001)    | 0.502 (0.016)    | 0 (0.000) |     5.06 | arcade, Lake, micro, Seb, wiz |
|            6 |     3805 | 2024-03-06 | Limitless        | W   | 0.183      | 0.477        | 0.001 (0.000)    | 0.159 (0.014)    | 0 (0.000) |     2.70 | arcade, Lake, micro, Seb, wiz |
|            5 |     3808 | 2024-03-06 | Limitless        | W   | 0.183      | 0.477        | 0.001 (0.000)    | 0.159 (0.014)    | 0 (0.000) |     2.74 | arcade, Lake, micro, Seb, wiz |
|            4 |     4302 | 2024-02-14 | Rocket           | W   | 0.043      | 0.477        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.35 | arcade, Lake, micro, Seb, wiz |
|            3 |     4304 | 2024-02-14 | Rocket           | L   | 0.043      | -            | -                | -                | -         |    -1.00 | arcade, Lake, micro, Seb, wiz |
|            2 |     4342 | 2024-02-13 | FLUFFY AIMERS    | W   | 0.036      | 0.477        | 0.010 (0.000)    | 0.095 (0.002)    | 0 (0.000) |     0.71 | arcade, Lake, micro, Seb, wiz |
|            1 |     4345 | 2024-02-13 | FLUFFY AIMERS    | L   | 0.036      | -            | -                | -                | -         |    -0.44 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,631.11)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
