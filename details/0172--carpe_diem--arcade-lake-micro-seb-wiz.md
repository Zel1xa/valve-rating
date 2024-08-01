### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: arcade, Lake, micro, Seb, wiz<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
<br />
Final Rank Value:  667.0<br />
<br />
Final Rank Value (667.0) = Starting Rank Value (678.1) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.304[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.1
- 400 + ( ( 0.135 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 678.1


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
|           20 |     2229 | 2024-05-08 | M80              | L   | 0.635      | -            | -                | -                | -         |    -0.69 | arcade, Lake, micro, Seb, wiz |
|           19 |     2230 | 2024-05-08 | M80              | L   | 0.635      | -            | -                | -                | -         |    -0.70 | arcade, Lake, micro, Seb, wiz |
|           18 |     2871 | 2024-04-11 | Mythic           | W   | 0.456      | 0.477        | 0.010 (0.002)    | 0.303 (0.066)    | 0 (0.000) |     9.55 | arcade, Lake, micro, Seb, wiz |
|           17 |     2873 | 2024-04-11 | Mythic           | L   | 0.455      | -            | -                | -                | -         |    -4.85 | arcade, Lake, micro, Seb, wiz |
|           16 |     2961 | 2024-04-09 | NRG              | L   | 0.442      | -            | -                | -                | -         |    -3.47 | arcade, Lake, micro, Seb, wiz |
|           15 |     2964 | 2024-04-09 | NRG              | L   | 0.442      | -            | -                | -                | -         |    -3.57 | arcade, Lake, micro, Seb, wiz |
|           14 |     3088 | 2024-04-04 | Perseverance     | L   | 0.409      | -            | -                | -                | -         |    -5.18 | arcade, Lake, micro, Seb, wiz |
|           13 |     3093 | 2024-04-04 | Perseverance     | L   | 0.409      | -            | -                | -                | -         |    -5.36 | arcade, Lake, micro, Seb, wiz |
|           12 |     3275 | 2024-03-27 | Party Astronauts | L   | 0.356      | -            | -                | -                | -         |    -2.10 | arcade, Lake, micro, Seb, wiz |
|           11 |     3278 | 2024-03-27 | Party Astronauts | L   | 0.356      | -            | -                | -                | -         |    -2.14 | arcade, Lake, micro, Seb, wiz |
|           10 |     3499 | 2024-03-15 | Elevate          | L   | 0.276      | -            | -                | -                | -         |    -1.26 | arcade, Lake, micro, Seb, wiz |
|            9 |     3501 | 2024-03-15 | Elevate          | L   | 0.276      | -            | -                | -                | -         |    -1.28 | arcade, Lake, micro, Seb, wiz |
|            8 |     3563 | 2024-03-13 | Party Astronauts | L   | 0.261      | -            | -                | -                | -         |    -1.61 | arcade, Lake, micro, Seb, wiz |
|            7 |     3603 | 2024-03-12 | NRG              | W   | 0.255      | 0.143        | 0.020 (0.001)    | 0.519 (0.019)    | 0 (0.000) |     5.82 | arcade, Lake, micro, Seb, wiz |
|            6 |     3739 | 2024-03-06 | Limitless        | W   | 0.216      | 0.477        | 0.001 (0.000)    | 0.170 (0.017)    | 0 (0.000) |     3.17 | arcade, Lake, micro, Seb, wiz |
|            5 |     3742 | 2024-03-06 | Limitless        | W   | 0.216      | 0.477        | 0.001 (0.000)    | 0.170 (0.017)    | 0 (0.000) |     3.23 | arcade, Lake, micro, Seb, wiz |
|            4 |     4251 | 2024-02-14 | Rocket           | W   | 0.076      | 0.477        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.63 | arcade, Lake, micro, Seb, wiz |
|            3 |     4253 | 2024-02-14 | Rocket           | L   | 0.076      | -            | -                | -                | -         |    -1.76 | arcade, Lake, micro, Seb, wiz |
|            2 |     4291 | 2024-02-13 | FLUFFY AIMERS    | W   | 0.069      | 0.477        | 0.010 (0.000)    | 0.104 (0.003)    | 0 (0.000) |     1.36 | arcade, Lake, micro, Seb, wiz |
|            1 |     4294 | 2024-02-13 | FLUFFY AIMERS    | L   | 0.069      | -            | -                | -                | -         |    -0.82 | arcade, Lake, micro, Seb, wiz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,696.67)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
