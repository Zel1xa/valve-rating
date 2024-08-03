### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
<br />
Final Rank Value:  666.6<br />
<br />
Final Rank Value (666.6) = Starting Rank Value (675.5) + Head To Head Adjustments (-8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.5
- 400 + ( ( 0.135 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 675.5


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
|           17 |     2806 | 2024-04-11 | Mythic           | W   | 0.443      | 0.477        | 0.010 (0.002)    | 0.311 (0.066)    | 0 (0.000) |     9.23 | arcade, Lake, micro, Seb, wiz |
|           16 |     2808 | 2024-04-11 | Mythic           | L   | 0.442      | -            | -                | -                | -         |    -4.77 | arcade, Lake, micro, Seb, wiz |
|           15 |     2896 | 2024-04-09 | NRG              | L   | 0.429      | -            | -                | -                | -         |    -3.39 | arcade, Lake, micro, Seb, wiz |
|           14 |     2899 | 2024-04-09 | NRG              | L   | 0.429      | -            | -                | -                | -         |    -3.49 | arcade, Lake, micro, Seb, wiz |
|           13 |     3023 | 2024-04-04 | Perseverance     | L   | 0.396      | -            | -                | -                | -         |    -5.04 | arcade, Lake, micro, Seb, wiz |
|           12 |     3028 | 2024-04-04 | Perseverance     | L   | 0.396      | -            | -                | -                | -         |    -5.21 | arcade, Lake, micro, Seb, wiz |
|           11 |     3202 | 2024-03-27 | Party Astronauts | L   | 0.343      | -            | -                | -                | -         |    -2.02 | arcade, Lake, micro, Seb, wiz |
|           10 |     3205 | 2024-03-27 | Party Astronauts | L   | 0.343      | -            | -                | -                | -         |    -2.05 | arcade, Lake, micro, Seb, wiz |
|            9 |     3417 | 2024-03-15 | Elevate          | L   | 0.263      | -            | -                | -                | -         |    -1.59 | arcade, Lake, micro, Seb, wiz |
|            8 |     3475 | 2024-03-13 | Party Astronauts | L   | 0.248      | -            | -                | -                | -         |    -1.55 | arcade, Lake, micro, Seb, wiz |
|            7 |     3514 | 2024-03-12 | NRG              | W   | 0.242      | 0.143        | 0.020 (0.001)    | 0.538 (0.019)    | 0 (0.000) |     5.52 | arcade, Lake, micro, Seb, wiz |
|            6 |     3647 | 2024-03-06 | Limitless        | W   | 0.203      | 0.477        | 0.001 (0.000)    | 0.174 (0.017)    | 0 (0.000) |     2.99 | arcade, Lake, micro, Seb, wiz |
|            5 |     3650 | 2024-03-06 | Limitless        | W   | 0.203      | 0.477        | 0.001 (0.000)    | 0.174 (0.017)    | 0 (0.000) |     3.04 | arcade, Lake, micro, Seb, wiz |
|            4 |     4143 | 2024-02-14 | Rocket           | W   | 0.063      | 0.477        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     0.52 | arcade, Lake, micro, Seb, wiz |
|            3 |     4145 | 2024-02-14 | Rocket           | L   | 0.063      | -            | -                | -                | -         |    -1.46 | arcade, Lake, micro, Seb, wiz |
|            2 |     4183 | 2024-02-13 | FLUFFY AIMERS    | W   | 0.056      | 0.477        | 0.010 (0.000)    | 0.106 (0.003)    | 0 (0.000) |     1.09 | arcade, Lake, micro, Seb, wiz |
|            1 |     4186 | 2024-02-13 | FLUFFY AIMERS    | L   | 0.056      | -            | -                | -                | -         |    -0.68 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,670.65)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
