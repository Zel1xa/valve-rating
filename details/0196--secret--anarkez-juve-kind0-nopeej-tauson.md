### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
<br />
Final Rank Value:  534.1<br />
<br />
Final Rank Value (534.1) = Starting Rank Value (538.2) + Head To Head Adjustments (-4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.2
- 400 + ( ( 0.067 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 538.2


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
|           20 |     2186 | 2024-05-14 | WOPA          | L   | 0.641      | -            | -                | -                | -         |    -7.83 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2198 | 2024-05-13 | LEON          | L   | 0.636      | -            | -                | -                | -         |    -6.19 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           18 |     2742 | 2024-04-19 | Portugal      | L   | 0.475      | -            | -                | -                | -         |    -4.81 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2797 | 2024-04-18 | Nemiga        | L   | 0.468      | -            | -                | -                | -         |    -0.47 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2808 | 2024-04-18 | 500           | W   | 0.467      | 0.143        | 0.001 (0.000)    | 0.093 (0.006)    | 0 (0.000) |    10.97 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2831 | 2024-04-17 | Illuminar     | L   | 0.462      | -            | -                | -                | -         |    -7.89 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2881 | 2024-04-16 | Sampi         | L   | 0.453      | -            | -                | -                | -         |    -1.70 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2896 | 2024-04-15 | PGE Turow     | W   | 0.447      | 0.371        | 0.001 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     9.09 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     2968 | 2024-04-11 | ENCE Academy  | L   | 0.420      | -            | -                | -                | -         |    -3.71 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3155 | 2024-04-05 | 9 Pandas      | W   | 0.381      | 0.384        | 0.081 (0.012)    | 0.716 (0.105)    | 0 (0.000) |    11.19 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3674 | 2024-03-12 | Endpoint      | L   | 0.220      | -            | -                | -                | -         |    -0.85 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|            9 |     3759 | 2024-03-08 | Metizport     | L   | 0.194      | -            | -                | -                | -         |    -0.67 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3789 | 2024-03-07 | ex-Preasy     | L   | 0.186      | -            | -                | -                | -         |    -1.16 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3870 | 2024-03-04 | Fraud5        | L   | 0.168      | -            | -                | -                | -         |    -1.88 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3906 | 2024-03-03 | Zero Tenacity | L   | 0.160      | -            | -                | -                | -         |    -0.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3926 | 2024-03-02 | Zero Tenacity | L   | 0.153      | -            | -                | -                | -         |    -0.20 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3968 | 2024-02-28 | Permitta      | W   | 0.134      | 0.143        | 0.023 (0.000)    | 0.940 (0.018)    | 0 (0.000) |     3.87 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4027 | 2024-02-25 | Entropiq      | L   | 0.114      | -            | -                | -                | -         |    -1.76 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4223 | 2024-02-17 | Sampi         | L   | 0.061      | -            | -                | -                | -         |    -0.24 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4378 | 2024-02-10 | 500           | W   | 0.014      | 0.358        | 0.001 (0.000)    | 0.093 (0.000)    | 0 (0.000) |     0.31 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
