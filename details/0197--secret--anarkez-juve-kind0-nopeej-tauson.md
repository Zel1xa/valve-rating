### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [197](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  534.2<br />
<br />
Final Rank Value (534.2) = Starting Rank Value (538.4) + Head To Head Adjustments (-4.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.4
- 400 + ( ( 0.068 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 538.4


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
|           20 |     2154 | 2024-05-14 | WOPA          | L   | 0.652      | -            | -                | -                | -         |    -8.00 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2166 | 2024-05-13 | LEON          | L   | 0.647      | -            | -                | -                | -         |    -6.32 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           18 |     2710 | 2024-04-19 | Portugal      | L   | 0.487      | -            | -                | -                | -         |    -4.91 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2765 | 2024-04-18 | Nemiga        | L   | 0.480      | -            | -                | -                | -         |    -0.48 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2776 | 2024-04-18 | 500           | W   | 0.478      | 0.143        | 0.001 (0.000)    | 0.097 (0.007)    | 0 (0.000) |    11.27 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2799 | 2024-04-17 | Illuminar     | L   | 0.474      | -            | -                | -                | -         |    -8.09 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2849 | 2024-04-16 | Sampi         | L   | 0.464      | -            | -                | -                | -         |    -1.74 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2864 | 2024-04-15 | PGE Turow     | W   | 0.458      | 0.371        | 0.001 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     9.34 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     2936 | 2024-04-11 | ENCE Academy  | L   | 0.432      | -            | -                | -                | -         |    -3.78 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3123 | 2024-04-05 | 9 Pandas      | W   | 0.392      | 0.384        | 0.081 (0.012)    | 0.690 (0.104)    | 0 (0.000) |    11.54 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3642 | 2024-03-12 | Endpoint      | L   | 0.232      | -            | -                | -                | -         |    -0.90 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|            9 |     3727 | 2024-03-08 | Metizport     | L   | 0.206      | -            | -                | -                | -         |    -0.98 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3757 | 2024-03-07 | ex-Preasy     | L   | 0.198      | -            | -                | -                | -         |    -1.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3838 | 2024-03-04 | Fraud5        | L   | 0.179      | -            | -                | -                | -         |    -2.00 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3874 | 2024-03-03 | Zero Tenacity | L   | 0.172      | -            | -                | -                | -         |    -0.22 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3894 | 2024-03-02 | Zero Tenacity | L   | 0.165      | -            | -                | -                | -         |    -0.22 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3936 | 2024-02-28 | Permitta      | W   | 0.146      | 0.143        | 0.024 (0.000)    | 0.876 (0.018)    | 0 (0.000) |     4.17 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     3995 | 2024-02-25 | Entropiq      | L   | 0.126      | -            | -                | -                | -         |    -1.93 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4191 | 2024-02-17 | Sampi         | L   | 0.072      | -            | -                | -                | -         |    -0.28 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4346 | 2024-02-10 | 500           | W   | 0.025      | 0.358        | 0.001 (0.000)    | 0.097 (0.001)    | 0 (0.000) |     0.57 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
