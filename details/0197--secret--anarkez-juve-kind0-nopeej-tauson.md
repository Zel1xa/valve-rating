### Roster Details<br />
Team Name: Secret<br />
Roster: anarkez, Juve, Kind0, NOPEEJ, Tauson<br />
Global Rank: [197](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [125]( ../standings_europe.md)<br />
<br />
Final Rank Value:  534.1<br />
<br />
Final Rank Value (534.1) = Starting Rank Value (538.4) + Head To Head Adjustments (-4.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 538.4
- 400 + ( ( 0.068 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 538.4


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
|           20 |     2171 | 2024-05-14 | WOPA          | L   | 0.646      | -            | -                | -                | -         |    -7.92 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           19 |     2183 | 2024-05-13 | LEON          | L   | 0.642      | -            | -                | -                | -         |    -6.26 | anarkez, Juve, Kind0, NOPEEJ, Tauson   |
|           18 |     2727 | 2024-04-19 | Portugal      | L   | 0.481      | -            | -                | -                | -         |    -4.86 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           17 |     2782 | 2024-04-18 | Nemiga        | L   | 0.474      | -            | -                | -                | -         |    -0.47 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           16 |     2793 | 2024-04-18 | 500           | W   | 0.473      | 0.143        | 0.001 (0.000)    | 0.096 (0.006)    | 0 (0.000) |    11.12 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           15 |     2816 | 2024-04-17 | Illuminar     | L   | 0.468      | -            | -                | -                | -         |    -7.99 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           14 |     2866 | 2024-04-16 | Sampi         | L   | 0.459      | -            | -                | -                | -         |    -1.73 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           13 |     2881 | 2024-04-15 | PGE Turow     | W   | 0.453      | 0.371        | 0.001 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     9.22 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           12 |     2953 | 2024-04-11 | ENCE Academy  | L   | 0.426      | -            | -                | -                | -         |    -3.75 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           11 |     3140 | 2024-04-05 | 9 Pandas      | W   | 0.387      | 0.384        | 0.081 (0.012)    | 0.727 (0.108)    | 0 (0.000) |    11.37 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|           10 |     3659 | 2024-03-12 | Endpoint      | L   | 0.226      | -            | -                | -                | -         |    -0.88 | anarkez, Kind0, Maze, NOPEEJ, Tauson   |
|            9 |     3744 | 2024-03-08 | Metizport     | L   | 0.200      | -            | -                | -                | -         |    -0.96 | anarkez, innocent, Kind0, Maze, Tauson |
|            8 |     3774 | 2024-03-07 | ex-Preasy     | L   | 0.192      | -            | -                | -                | -         |    -1.19 | anarkez, innocent, Kind0, Maze, Tauson |
|            7 |     3855 | 2024-03-04 | Fraud5        | L   | 0.174      | -            | -                | -                | -         |    -1.94 | anarkez, innocent, Kind0, Maze, Tauson |
|            6 |     3891 | 2024-03-03 | Zero Tenacity | L   | 0.166      | -            | -                | -                | -         |    -0.22 | anarkez, innocent, Kind0, Maze, Tauson |
|            5 |     3911 | 2024-03-02 | Zero Tenacity | L   | 0.159      | -            | -                | -                | -         |    -0.21 | anarkez, innocent, Kind0, Maze, Tauson |
|            4 |     3953 | 2024-02-28 | Permitta      | W   | 0.140      | 0.143        | 0.024 (0.000)    | 0.873 (0.017)    | 0 (0.000) |     4.01 | anarkez, innocent, Kind0, Maze, Tauson |
|            3 |     4012 | 2024-02-25 | Entropiq      | L   | 0.120      | -            | -                | -                | -         |    -1.85 | anarkez, innocent, Kind0, Maze, Tauson |
|            2 |     4208 | 2024-02-17 | Sampi         | L   | 0.066      | -            | -                | -                | -         |    -0.26 | anarkez, innocent, Kind0, Maze, Tauson |
|            1 |     4363 | 2024-02-10 | 500           | W   | 0.020      | 0.358        | 0.001 (0.000)    | 0.096 (0.001)    | 0 (0.000) |     0.44 | anarkez, innocent, Kind0, Maze, Tauson |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
