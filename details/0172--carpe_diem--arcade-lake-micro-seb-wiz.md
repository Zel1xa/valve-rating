### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  667.5<br />
<br />
Final Rank Value (667.5) = Starting Rank Value (678.5) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.5
- 400 + ( ( 0.135 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 678.5


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
|           20 |     2223 | 2024-05-08 | M80              | L   | 0.637      | -            | -                | -                | -         |    -0.70 | arcade, Lake, micro, Seb, wiz |
|           19 |     2224 | 2024-05-08 | M80              | L   | 0.637      | -            | -                | -                | -         |    -0.70 | arcade, Lake, micro, Seb, wiz |
|           18 |     2865 | 2024-04-11 | Mythic           | W   | 0.457      | 0.477        | 0.010 (0.002)    | 0.304 (0.066)    | 0 (0.000) |     9.59 | arcade, Lake, micro, Seb, wiz |
|           17 |     2867 | 2024-04-11 | Mythic           | L   | 0.457      | -            | -                | -                | -         |    -4.87 | arcade, Lake, micro, Seb, wiz |
|           16 |     2955 | 2024-04-09 | NRG              | L   | 0.444      | -            | -                | -                | -         |    -3.48 | arcade, Lake, micro, Seb, wiz |
|           15 |     2958 | 2024-04-09 | NRG              | L   | 0.444      | -            | -                | -                | -         |    -3.58 | arcade, Lake, micro, Seb, wiz |
|           14 |     3082 | 2024-04-04 | Perseverance     | L   | 0.411      | -            | -                | -                | -         |    -5.20 | arcade, Lake, micro, Seb, wiz |
|           13 |     3087 | 2024-04-04 | Perseverance     | L   | 0.410      | -            | -                | -                | -         |    -5.38 | arcade, Lake, micro, Seb, wiz |
|           12 |     3269 | 2024-03-27 | Party Astronauts | L   | 0.357      | -            | -                | -                | -         |    -2.11 | arcade, Lake, micro, Seb, wiz |
|           11 |     3272 | 2024-03-27 | Party Astronauts | L   | 0.357      | -            | -                | -                | -         |    -2.15 | arcade, Lake, micro, Seb, wiz |
|           10 |     3493 | 2024-03-15 | Elevate          | L   | 0.278      | -            | -                | -                | -         |    -1.27 | arcade, Lake, micro, Seb, wiz |
|            9 |     3495 | 2024-03-15 | Elevate          | L   | 0.277      | -            | -                | -                | -         |    -1.28 | arcade, Lake, micro, Seb, wiz |
|            8 |     3557 | 2024-03-13 | Party Astronauts | L   | 0.263      | -            | -                | -                | -         |    -1.62 | arcade, Lake, micro, Seb, wiz |
|            7 |     3597 | 2024-03-12 | NRG              | W   | 0.257      | 0.143        | 0.020 (0.001)    | 0.519 (0.019)    | 0 (0.000) |     5.86 | arcade, Lake, micro, Seb, wiz |
|            6 |     3733 | 2024-03-06 | Limitless        | W   | 0.217      | 0.477        | 0.001 (0.000)    | 0.170 (0.018)    | 0 (0.000) |     3.19 | arcade, Lake, micro, Seb, wiz |
|            5 |     3736 | 2024-03-06 | Limitless        | W   | 0.217      | 0.477        | 0.001 (0.000)    | 0.170 (0.018)    | 0 (0.000) |     3.25 | arcade, Lake, micro, Seb, wiz |
|            4 |     4245 | 2024-02-14 | Rocket           | W   | 0.077      | 0.477        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.64 | arcade, Lake, micro, Seb, wiz |
|            3 |     4247 | 2024-02-14 | Rocket           | L   | 0.077      | -            | -                | -                | -         |    -1.80 | arcade, Lake, micro, Seb, wiz |
|            2 |     4285 | 2024-02-13 | FLUFFY AIMERS    | W   | 0.071      | 0.477        | 0.010 (0.000)    | 0.105 (0.004)    | 0 (0.000) |     1.39 | arcade, Lake, micro, Seb, wiz |
|            1 |     4288 | 2024-02-13 | FLUFFY AIMERS    | L   | 0.071      | -            | -                | -                | -         |    -0.84 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,700.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
