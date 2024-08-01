### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
<br />
Final Rank Value:  537.7<br />
<br />
Final Rank Value (537.7) = Starting Rank Value (540.2) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 540.2
- 400 + ( ( 0.068 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 540.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2091 | 2024-05-14 | WOPA          | L   | 0.673      | -            | -                | -                | -         |    -8.29 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           20 |     2104 | 2024-05-13 | LEON          | L   | 0.669      | -            | -                | -                | -         |    -6.55 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2662 | 2024-04-19 | Portugal      | L   | 0.508      | -            | -                | -                | -         |    -5.04 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           18 |     2718 | 2024-04-18 | Nemiga        | L   | 0.501      | -            | -                | -                | -         |    -0.53 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2729 | 2024-04-18 | 500           | W   | 0.500      | 0.143        | 0.001 (0.000)    | 0.127 (0.009)    | 0 (0.000) |    12.15 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2753 | 2024-04-17 | Illuminar     | L   | 0.495      | -            | -                | -                | -         |    -8.48 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2804 | 2024-04-16 | Sampi         | L   | 0.486      | -            | -                | -                | -         |    -1.79 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2819 | 2024-04-15 | PGE Turow     | W   | 0.480      | 0.371        | 0.001 (0.000)    | 0.026 (0.005)    | 0 (0.000) |     9.82 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2892 | 2024-04-11 | ENCE Academy  | L   | 0.453      | -            | -                | -                | -         |    -3.72 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     3079 | 2024-04-05 | 9 Pandas      | W   | 0.413      | 0.384        | 0.083 (0.013)    | 0.578 (0.092)    | 0 (0.000) |    12.18 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3616 | 2024-03-12 | Endpoint      | L   | 0.253      | -            | -                | -                | -         |    -0.89 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3702 | 2024-03-08 | Metizport     | L   | 0.227      | -            | -                | -                | -         |    -0.79 | anarkez, innocent, Kind0, Maze, Tauson |
|            9 |     3732 | 2024-03-07 | ex-Preasy     | L   | 0.219      | -            | -                | -                | -         |    -1.28 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3818 | 2024-03-04 | Fraud5        | L   | 0.201      | -            | -                | -                | -         |    -2.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3854 | 2024-03-03 | Zero Tenacity | L   | 0.193      | -            | -                | -                | -         |    -0.26 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3874 | 2024-03-02 | Zero Tenacity | L   | 0.186      | -            | -                | -                | -         |    -0.25 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3918 | 2024-02-28 | Permitta      | W   | 0.167      | 0.143        | 0.024 (0.001)    | 0.801 (0.019)    | 0 (0.000) |     4.76 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3979 | 2024-02-25 | Entropiq      | L   | 0.147      | -            | -                | -                | -         |    -2.25 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4180 | 2024-02-17 | Sampi         | L   | 0.093      | -            | -                | -                | -         |    -0.36 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4345 | 2024-02-10 | 500           | W   | 0.047      | 0.358        | 0.001 (0.000)    | 0.127 (0.002)    | 0 (0.000) |     1.09 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4416 | 2024-02-04 | Alliance      | W   | 0.008      | 0.358        | 0.014 (0.000)    | 0.319 (0.001)    | 0 (0.000) |     0.20 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
