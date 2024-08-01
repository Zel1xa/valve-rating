### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
<br />
Final Rank Value:  537.3<br />
<br />
Final Rank Value (537.3) = Starting Rank Value (539.9) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.259[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 539.9
- 400 + ( ( 0.068 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 539.9


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
|           21 |     2097 | 2024-05-14 | WOPA          | L   | 0.672      | -            | -                | -                | -         |    -8.27 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           20 |     2110 | 2024-05-13 | LEON          | L   | 0.667      | -            | -                | -                | -         |    -6.53 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2668 | 2024-04-19 | Portugal      | L   | 0.507      | -            | -                | -                | -         |    -5.02 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           18 |     2724 | 2024-04-18 | Nemiga        | L   | 0.499      | -            | -                | -                | -         |    -0.53 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2735 | 2024-04-18 | 500           | W   | 0.498      | 0.143        | 0.001 (0.000)    | 0.126 (0.009)    | 0 (0.000) |    12.11 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2759 | 2024-04-17 | Illuminar     | L   | 0.493      | -            | -                | -                | -         |    -8.45 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2810 | 2024-04-16 | Sampi         | L   | 0.484      | -            | -                | -                | -         |    -1.79 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2825 | 2024-04-15 | PGE Turow     | W   | 0.478      | 0.371        | 0.001 (0.000)    | 0.026 (0.005)    | 0 (0.000) |     9.78 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2898 | 2024-04-11 | ENCE Academy  | L   | 0.451      | -            | -                | -                | -         |    -3.71 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     3085 | 2024-04-05 | 9 Pandas      | W   | 0.412      | 0.384        | 0.083 (0.013)    | 0.577 (0.091)    | 0 (0.000) |    12.13 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3622 | 2024-03-12 | Endpoint      | L   | 0.251      | -            | -                | -                | -         |    -0.89 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3708 | 2024-03-08 | Metizport     | L   | 0.225      | -            | -                | -                | -         |    -0.78 | anarkez, innocent, Kind0, Maze, Tauson |
|            9 |     3738 | 2024-03-07 | ex-Preasy     | L   | 0.217      | -            | -                | -                | -         |    -1.27 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3824 | 2024-03-04 | Fraud5        | L   | 0.199      | -            | -                | -                | -         |    -2.19 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3860 | 2024-03-03 | Zero Tenacity | L   | 0.191      | -            | -                | -                | -         |    -0.26 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3880 | 2024-03-02 | Zero Tenacity | L   | 0.184      | -            | -                | -                | -         |    -0.25 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3924 | 2024-02-28 | Permitta      | W   | 0.165      | 0.143        | 0.024 (0.001)    | 0.801 (0.019)    | 0 (0.000) |     4.70 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3985 | 2024-02-25 | Entropiq      | L   | 0.145      | -            | -                | -                | -         |    -2.22 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4186 | 2024-02-17 | Sampi         | L   | 0.092      | -            | -                | -                | -         |    -0.35 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4351 | 2024-02-10 | 500           | W   | 0.045      | 0.358        | 0.001 (0.000)    | 0.126 (0.002)    | 0 (0.000) |     1.05 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4422 | 2024-02-04 | Alliance      | W   | 0.006      | 0.358        | 0.014 (0.000)    | 0.319 (0.001)    | 0 (0.000) |     0.16 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
