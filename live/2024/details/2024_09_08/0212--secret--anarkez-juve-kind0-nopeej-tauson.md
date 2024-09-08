### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [212](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [132]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  506.7<br />
<br />
Final Rank Value (506.7) = Starting Rank Value (511.3) + Head To Head Adjustments (-4.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.3
- 400 + ( ( 0.057 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 511.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3321 | 2024-05-14 | WOPA         | L   | 0.420      | -            | -                | -                | -         |    -4.34 | anarkez, Juve, Kind0, NOPEEJ, Tauson |
|            9 |     3333 | 2024-05-13 | LEON         | L   | 0.415      | -            | -                | -                | -         |    -4.04 | anarkez, Juve, Kind0, NOPEEJ, Tauson |
|            8 |     3877 | 2024-04-19 | Portugal     | L   | 0.255      | -            | -                | -                | -         |    -3.02 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            7 |     3932 | 2024-04-18 | Nemiga       | L   | 0.247      | -            | -                | -                | -         |    -0.21 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            6 |     3943 | 2024-04-18 | 500          | W   | 0.246      | 0.143        | 0.001 (0.000)    | 0.025 (0.001)    | 0 (0.000) |     5.40 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            5 |     3966 | 2024-04-17 | Illuminar    | L   | 0.241      | -            | -                | -                | -         |    -3.98 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            4 |     4016 | 2024-04-16 | Sampi        | L   | 0.232      | -            | -                | -                | -         |    -0.76 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            3 |     4031 | 2024-04-15 | PGE Turow    | W   | 0.226      | 0.371        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     3.49 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            2 |     4103 | 2024-04-11 | ENCE Academy | L   | 0.199      | -            | -                | -                | -         |    -1.93 | anarkez, Kind0, Maze, NOPEEJ, Tauson |
|            1 |     4290 | 2024-04-05 | 9 Pandas     | W   | 0.160      | 0.384        | 0.059 (0.004)    | 0.732 (0.045)    | 0 (0.000) |     4.78 | anarkez, Kind0, Maze, NOPEEJ, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
